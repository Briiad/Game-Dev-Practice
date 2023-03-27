# Game Dev Requirements
This is a list of requirements for game development. It is not a list of requirements for game development in general, but rather a list of requirements for game development in the context of the <b>Game Dev Requirements</b> project using <b>Phaser Framework</b>.

## Installation Requirements
- [Node.js 14.18.3](https://nodejs.org/dist/v14.18.3/node-v14.18.3-x64.msi)
- [Git](https://git-scm.com/downloads)
- [Visual Studio Code](https://code.visualstudio.com/download)

## Mandatory Requirements
- [Github Account](https://github.com/signup)
  
Github account is required to create a repository for the project. It is also required to create a project board for the project.

## Steps
### Node JS
1. After Installing the above requirements, open the vscode and open the terminal using `Ctrl + Shift + ~`
2. Check if node is installed by typing `node -v` in the terminal. If it is installed, it will show the version of node installed. It should be <b>14.18.3</b>.

### Git
1. After Installing the above requirements, open the vscode and open the terminal using `Ctrl + Shift + ~`
2. Check if git is installed by typing `git --version` in the terminal. If it is installed, it will show the version of git installed.

### Vscode Extensions
1. Click on the extensions icon on the left side of the vscode.
2. Search for the following extensions and install them.
    - Code Runner
    - Prettier
    - Rainbow Indent

### Vscode sync settings with Github
1. Open the vscode settings by clicking on the gear icon on the left side of the vscode.
2.  Search for `Sync` and click on `Settings Sync`.
3.  Select `Sign in with Github`

## Project Setup
1. Create a new empty folder with the folder name of `Timedoor Project` for the project on your Laptop / PC.
2. Open the vscode
3. Open the folder `Timedoor Project` in the vscode by clicking on `File` and then `Open Folder` and then selecting the folder `Timedoor Project`.
4. Open the terminal using `Ctrl + Shift + ~`
5. Clone the project repository by typing this command in the terminal.
   ```bash
   git clone https://github.com/ourcade/phaser3-parcel-template.git
    ```
6. After cloning the project repository, open the folder `phaser3-parcel-template` in the vscode by clicking on `File` and then `Open Folder` and then selecting the folder `phaser3-parcel-template`.
7.  Install the dependencies by typing this command in the terminal.
    ```bash
    npm install
    ```
    and then,
    ```bash
    npm install -g parcel-bundler
    ```
8.  Run the project by typing this command in the terminal.
    ```bash
    npm run dev
    ```