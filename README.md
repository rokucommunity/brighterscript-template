# BrighterScript Template
This is a template project for a Roku app written in [BrighterScript](https://github.com/rokucommunity/brighterscript)

## Setup instructions
1. Install [NodeJS](https://nodejs.org)
2. Make a local copy of the project:
    ```bash
    npx degit rokucommunity/brighterscript-template BrighterScriptApp
    ```
2. navigate to the new app directory
    ```bash
    cd BrighterScriptApp
    ```
4. install npm dependencies
    ```bash
    npm install
    ```
5. Build a zip of the project
    ```bash
    npm run package
    ```

## Debugging
This repository comes pre-configured to work with the [BrightScript Language](https://github.com/rokucommunity/vscode-brightscript-language) extension for Visual Studio Code. So once you have that plugin installed, debugging your project is as simple as clicking the "Start Debugging" button. 