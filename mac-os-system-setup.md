# MacOS Setup

## Softwares

### Sublime Text

- Install Sublime Text 3.x
- Install Package Control - Cmd + Shft + P - Choose 'Install Package Control'
- Install Sqlbeautifier - Cmd + Shft + P - Choose 'Package Control: Install Package' - Choose 'Sqlbeautifier'
- Install Pretty JSON - Cmd + Shft + P - Choose 'Package Control: Install Package' - Choose 'Pretty JSON'
- Install Git - Cmd + Shft + P - Choose 'Package Control: Install Package' - Choose 'Git'
- Install GitGutter - Cmd + Shft + P - Choose 'Package Control: Install Package' - Choose 'GitGutter'
- Install Emmet - Cmd + Shft + P - Choose 'Package Control: Install Package' - Choose 'Emmet'

### Google Chrome

- Install Google Chrome for MacOS
- Install uBlock Origin
- Install Evernote Web Clipper
- Install Grammarly for Chrome
- Install Just Read
- Install Simple Allow Copy
- Install Tabs Backup & Restore
- Save the following sites as bookmarks in the Bookmark bar - Evernote, Gmail, Trello, Sheets, Github, Wikipedia, Quora, Reddit, Twitter, Devrant, MyVisualStudio, Splitwise, ClearTax, Sketchboard.me, Amazon Music, Airtable.
- Pin Evernote, Gmail, Trello, Whatsapp.

### Mozilla Firefox

- Install Mozilla Firefox for MacOS
- Login with Mozilla account for sync-up across all devices

### Microsoft Edge

- Install Microsoft Edge for MacOS
- Login with Microsoft account for sync-up across all devices

### IntelliJ IDEA

- Install IntelliJ IDEA Community Edition

### Xcode

- Install Xcode IDE from App Store

### DBeaver

- Install DBeaver Community Edition for MacOS

### vscode

- Download vscode for Mac
- Install extensions - ESLint, GitLens, Jupyter, Python

### iTerm

- Download iTerm 2
- Install zsh shell
- Install Oh-my-zsh framework for managing zsh shell
- Download xcode-select tools
- Open Applications in Finder, right-click on the iTerm application, choose Get Info and select 'Open with Rosetta' option

### Zoom.us

- Download Zoom for Mac

### Spotify

- Download Spotify for Mac
- Login with Spotify account

## Dock preference

- At bottom of the screen and fixed
- Finder, Sublime, Chrome, Safari, Firefox, Edge, IDEA, Xcode, DBeaver, vscode, iTerm, Zoom, Spotify, Notes, Reminders, Mail, Calendar, Messages, Contacts, Launchpad, App Store, System Preferences, PhotoBooth

## Environment

### Package manager for MacOS

- Install brew - /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### Javascript

- Install nvm - curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
- Install node - nvm install 14.15.2 (npm is automatically installed)
- nvm use 14.15.2

### Python

- Install pyenv - brew install pyenv
- Install python 3.9.1 - pyenv install 3.9.1
- Use python 3.9.1 - pyenv global 3.9.1
- Install python 2.7.18 - pyenv install 2.7.18

### SSH

- Setup ssh keys pair - ssh-keygen -t rsa
- Save SSH public key to github account

### Java

- Install jabba package manager - curl -sL https://github.com/shyiko/jabba/raw/master/install.sh | bash && . ~/.jabba/jabba.sh
- Install Adopt Java JDK for Java 11 - jabba install adopt@1.11.0-9

### Golang

- Install Golang with Homebrew - brew update && brew install golang
- Include the below in .zshrc

```sh

# Golang env variables
export GOPATH=$HOME/go-workspace
export GOROOT=/usr/local/opt/go/libexec
export PATH=$PATH:$GOPATH/bin
export PATH=$PATH:$GOROOT/bin
export GOBIN=$GOPATH/bin

```