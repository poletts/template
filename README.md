# template
The intent of this repository is to set a template repository structure (project architecture) for future projects.
Naming conventions is highly dependent on the project itself. The one adopted here is only to serve as future guidance for me and other fellows.

## Table of Contents
1. [Contens of a README file](#contents-of-the-readmemd-file)
2. [Folder Layout](#folder-layout)

## Contents of the README.md file
The following topics descibes some contents that can be covered in the README.md file:
1. Title
2. Description
3. Installation instructions
4. Usage instructions
5. Contributors / credits
6. License information
7. Release history

## Folder layout

This template shows an example of common folders used accross different projects. 
Naming conventions is highly dependent on the project itself.
```
project_name
   ├── .idea                        for Pycharm settings
   ├── .venv                        for virtual environments
   │   └── Include  
   │   └── Lib
   │   └── Scripts
   │   └── pyvenv.cfg
   ├── .vscode                      for Visual Studio Code settings
   │   └── settings.json
   ├── bin                          for compiled exe files
   ├── dat                          for database files
   ├── doc or site                  for documentation
   ├── ext                          for thir-party (external) functions
   │   └── __init__.py
   ├── log                          for user log
   ├── src                          for source files (proprietary functions)
   │   └── __init__.py
   │   └── ui                       for user interface
   │       └── __init__.py
   ├── test
   │   └── __init__.py
   ├── .gitignore
   ├── CHANGELOG.md
   ├── LICENSE
   ├── MANIFEST.in              
   ├── README.md or README.rst
   ├── requirements.txt
   ├── setup.py
```

## License
Check the following resources for guidelines in choosing a license for your project:
- [Choose a license](https://choosealicense.com/)
- [Creative Commons](https://creativecommons.org/choose/)

## Requirements.txt
This file can be uused to freeze the dependencies packages in your project.
```
pip freeze > requirements.txt
```

## Contributors
- [Jean Poletto](https://github.com/poletts)