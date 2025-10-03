# GITLOADER - Interactive GitHub Upload Tool

Et avanceret interaktivt CLI værktøj til at uploade projekter til GitHub med templates og guides.

## Installation

```bash
# Kopier GITLOADER til din PATH
sudo cp GITLOADER /usr/local/bin/

# Eller brug det direkte
./GITLOADER
```

## Brug

Start GITLOADER:
```bash
./GITLOADER
```

## Kommandoer

- `upload` - Upload nuværende projekt til GitHub
- `new` - Opret nyt projekt og upload
- `status` - Tjek GitHub CLI status
- `setup` - Setup GitHub CLI authentication
- `help` - Vis hjælp
- `exit` - Afslut GITLOADER

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
