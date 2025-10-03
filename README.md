# GITLOADER - Simple GitHub Upload Tool

Et simpelt og elegant CLI værktøj til at uploade projekter til GitHub med ét kommando.

## Installation

```bash
# Kopier GITLOADER til din PATH
sudo cp GITLOADER /usr/local/bin/

# Eller brug det direkte
./GITLOADER /path/to/your/project
```

## Brug

Super simpelt - bare giv det stien til dit projekt:
```bash
./GITLOADER /home/user/my-project
./GITLOADER ./my-website
./GITLOADER /var/www/html/my-app
```

## Hvad sker der?

1. **Logo vises** - Smukt ASCII art logo
2. **Guide vises** - Hurtig guide til hvad der sker
3. **Interaktive prompts** - Repository navn, beskrivelse, osv.
4. **Automatisk upload** - Git init, commit, push til GitHub

## Funktioner

### 🎯 **Interaktiv Projekt Oprettelse**
- Python Script templates
- Bash Script templates  
- Web Project templates
- CLI Tool templates
- Custom projects

### 🚀 **Automatisk Upload**
- Git initialization
- README.md generation
- MIT License addition
- Public/Private repositories
- Smart file detection

### 🎨 **User Experience**
- ASCII art logo
- Farvet output
- Step-by-step guides
- Error handling
- Interactive prompts

## Eksempler

### Opret Python Script:
```bash
./GITLOADER
> new
> Enter project name: my-python-tool
> Enter description: Awesome Python tool
> Select type: 1 (Python Script)
```

### Upload Eksisterende Projekt:
```bash
cd /path/to/your/project
./GITLOADER
> upload
> Enter repo name: my-project
> Enter description: My awesome project
```

## Projekt Templates

### Python Script
- Main Python file med shebang
- requirements.txt
- setup.sh script
- Executable permissions

### Bash Script  
- Main bash file
- install.sh script
- Executable permissions

### Web Project
- index.html
- style.css
- script.js
- Responsive design

### CLI Tool
- Python CLI med argparse
- setup.sh til installation
- requirements.txt
- System PATH integration

## Krav

- GitHub CLI (`gh`)
- Git
- Bash shell
- Internet forbindelse

## Features

✅ **Interaktiv Interface** - Guided workflow  
✅ **Project Templates** - Ready-to-use templates  
✅ **Smart Detection** - Automatisk fil detection  
✅ **Error Handling** - Robust fejlhåndtering  
✅ **Colored Output** - Bedre UX med farver  
✅ **Auto Setup** - Automatisk git og GitHub setup  
✅ **License & README** - Automatisk dokumentation  
✅ **Public/Private** - Repository visibility options
