# vscode-ext-cspell
Custom dictionaries settings for *Code Spell Checker* extension for *VSCode* editor
## Instructions
Inside a *.vscode* directory, which is in a project root directory, run on a command line the following:

**git clone --depth 1 git@github<span></span>.com:BlueRoadMedia/vscode-ext-cspell.git . && rm -rf README.md && rm -rf .git**

To add a *workspace* specific words, create the *VSCode* workspace *settings.json* file in the projects *.vscode* directory and add
the following entry:
  ```
  {
    "cSpell.userWords": ["word"]
  }
  ```
