# DevOps Engineer Setup
<p align="left"> <img src="https://komarev.com/ghpvc/?username=gghgh&label=Profile%20views&color=0e75b6&style=flat" alt="gghgh" /> </p>

## 📖 Table of Contents
- [💾 Macbook](#computer-macbook)
- [💻 Mac Setup](#-picker)
- [🙃 Emoji component](#-emoji-component)
- 


### :computer: Windows Laptop

#### Spotify
winget install --id=Spotify.Spotify  -e


#### NodeJS 16.12.0
winget install --id=OpenJS.NodeJS.LTS  -e --accept-package-agreements --accept-source-agreements

### Winget

#### Google Chrome
winget install -e --id Google.Chrome


### Azure 

https://learn.microsoft.com/en-us/azure/cosmos-db/emulator-command-line-parameters


##### Microsoft AzureStorageEmulator
winget install -e --id Microsoft.AzureStorageEmulator

##### Azure Data Studio
winget install --id Microsoft.AzureDataStudio -e --source winget


##### Azure CLI
winget install -e --id Microsoft.AzureCLI -e --source winget

##### Bicep Installation
winget install -e --id=Microsoft.Bicep --source winget

##### Power BI
winget install -e --id Microsoft.PowerBI


##### Windows Terminal
winget install -e --id Microsoft.WindowsTerminal

##### Microsoft PowerShell
winget install --id Microsoft.PowerShell -e --source winget


##### ScreenToGif Installation
winget install -e --id NickeManarin.ScreenToGif


##### Postman
winget install -e --id Postman.Postman

##### Notepad ++
winget install --id Notepad++.Notepad++ -e --source winget

##### Git
winget install -e --id Git.Git

##### Git Credential Manager
winget install -e --id Microsoft.GitCredentialManagerCore

##### Visual Studio Code
winget install --id Microsoft.VisualStudioCode -e --source winget


##### Draw io
winget install -e --id JGraph.Draw

##### Docker 
winget install --id Docker.DockerDesktop -e --source winget

##### minikube
winget install --id=Kubernetes.minikube  -e

##### kubectl
winget install -e --id Kubernetes.kubectl

#### az Copy
choco install azcopy10 -y

#### SQL Server Management Studio
winget install --id Microsoft.SQLServerManagementStudio -e --source winget

# chocolatey

#### Google Chrome
choco install googlechrome

#### Node.js
choco install nodejs-lts


#### Graphviz
choco install graphviz -y


#### Azure Storage Explorer
choco install microsoftazurestorageexplorer -y

##### Microsoft AzureCosmosEmulator
choco install azure-cosmosdb-emulator -y

##### Microsoft AzureCosmosEmulator
choco install azure-cosmosdb-emulator -y

#### Yarn
choco install yarn -y

##### Azure Data Studio
choco install azure-data-studio -y

#### PowerShell Core
choco install powershell-core -y

##### minikube
choco install minikube -y

##### k3d
choco install k3d -y

##### Azure CLI
choco install azure-cli -y

#### PowerShell Az
choco install az.powershell -y


##### Power BI
choco install powerbi -y

#### Screen to Gif
choco install screentogif.install -y

#### Spotify
choco install spotify -y


##### Postman
choco install postman -y

##### Terraform

choco install terraform -y

##### Golang
choco install golang


##### Notepad ++
choco install notepadplusplus -y

#### Git
choco install git -y


##### Git Credential Manager
choco install git-credential-manager-for-windows -y

#### KubeLogin
choco install azure-kubelogin -y

#### SQL Server Management Studio
choco install sql-server-management-studio -y

#### Visual Studio Code
choco install vscode -y

#### Helm Install
choco install kubernetes-helm

# Additional Setups

# Install Posh-Git
Install-Module posh-git -Scope CurrentUser -Force
Add-PoshGitToProfile -AllUsers -AllHosts

# :fire: Non work related

#### Etcher
choco install etcher -y


#### Steam
choco install steam -y

##### Lnes Kubernetes
winget install -e --id Mirantis.Lens

##### Mongo db
winget install -e --id MongoDB.Compass.Community

##### Mongo DB Shell
winget install -e --id MongoDB.Shell


##### Apple Itunes Installer
winget install -e --id Apple.iTunes


#### Splah Display
winget install -e --id Splashtop.SplashtopWiredXDisplay


##### Discord
winget install -e --id Discord.Discord

##### Get chatting with Slack
winget install --id SlackTechnologies.Slack -e --source winget

##### VLC Player
winget install -e --id VideoLAN.VLC

##### Nord VPN
winget install -e --id NordVPN.NordVPN

##### Reponsively
winget install -e --id ResponsivelyApp.ResponsivelyApp

##### WhatsApp Desktop
winget install -e --id WhatsApp.WhatsApp

##### Notion
winget install -e --id Notion.Notion

##### Klite Codec
winget install -e --id CodecGuide.K-LiteCodecPack.Mega

##### Splash Desktop
winget install -e --id Splashtop.SplashtopWiredXDisplay

##### Google Drive
winget install -e --id Google.Drive

# VS code Extentions
```
code --install-extension aaron-bond.better-comments
code --install-extension aaronthomas.vscode-snazzy-operator
code --install-extension ahmadalli.vscode-nginx-conf
code --install-extension andrejunges.Handlebars
code --install-extension Azurite.azurite
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
code --install-extension cosminalco.pomodoro
code --install-extension cschleiden.vscode-github-actions
code --install-extension dbaeumer.vscode-eslint
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension dzannotti.vscode-babel-coloring
code --install-extension dzhavat.bracket-pair-toggler
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-close-tag
code --install-extension GitHub.github-vscode-theme
code --install-extension GitHub.vscode-pull-request-github
code --install-extension hashicorp.terraform
code --install-extension humao.rest-client
code --install-extension icrawl.discord-vscode
code --install-extension jebbs.plantuml
code --install-extension jock.svg
code --install-extension kisstkondoros.vscode-gutter-preview
code --install-extension mongodb.mongodb-vscode
code --install-extension ms-azure-devops.azure-pipelines
code --install-extension ms-azuretools.azure-dev
code --install-extension ms-azuretools.vscode-azureappservice
code --install-extension ms-azuretools.vscode-azurefunctions
code --install-extension ms-azuretools.vscode-azureresourcegroups
code --install-extension ms-azuretools.vscode-azurestorage
code --install-extension ms-azuretools.vscode-azurevirtualmachines
code --install-extension ms-azuretools.vscode-bicep
code --install-extension ms-azuretools.vscode-cosmosdb
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-dotnettools.csharp
code --install-extension ms-dotnettools.vscode-dotnet-runtime
code --install-extension ms-kubernetes-tools.vscode-aks-tools
code --install-extension ms-kubernetes-tools.vscode-kubernetes-tools
code --install-extension ms-mssql.data-workspace-vscode
code --install-extension ms-mssql.mssql
code --install-extension ms-mssql.sql-bindings-vscode
code --install-extension ms-mssql.sql-database-projects-vscode
code --install-extension ms-playwright.playwright
code --install-extension ms-python.isort
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension ms-toolsai.jupyter
code --install-extension ms-toolsai.jupyter-keymap
code --install-extension ms-toolsai.jupyter-renderers
code --install-extension ms-toolsai.vscode-jupyter-cell-tags
code --install-extension ms-toolsai.vscode-jupyter-slideshow
code --install-extension ms-vscode-remote.remote-containers
code --install-extension ms-vscode-remote.remote-ssh-edit
code --install-extension ms-vscode-remote.remote-wsl
code --install-extension ms-vscode.azure-account
code --install-extension ms-vscode.azurecli
code --install-extension ms-vscode.powershell
code --install-extension ms-vscode.vscode-node-azure-pack
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension ms-vsliveshare.vsliveshare-audio
code --install-extension ms-vsliveshare.vsliveshare-pack
code --install-extension msazurermtools.azurerm-vscode-tools
code --install-extension Orta.vscode-jest
code --install-extension paulober.pico-w-go
code --install-extension PKief.material-icon-theme
code --install-extension Pluralsight.pluralsight
code --install-extension pranaygp.vscode-css-peek
code --install-extension rangav.vscode-thunder-client
code --install-extension redhat.ansible
code --install-extension redhat.vscode-yaml
code --install-extension ritwickdey.LiveServer
code --install-extension sdras.night-owl
code --install-extension shardulm94.trailing-spaces
code --install-extension TabNine.tabnine-vscode
code --install-extension TeamsDevApp.ms-teams-vscode-extension
code --install-extension TTOOWA.in-your-face-incredible
code --install-extension VisualStudioExptTeam.intellicode-api-usage-examples
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension vscode-icons-team.vscode-icons
code --install-extension WakaTime.vscode-wakatime
```

## :computer: Macbook


### Brew Install

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### Google Chrome
brew install --cask google-chrome

### Spotify

brew install --cask spotify


### NodeJS

brew install node

### Visual Studio Coder

brew install --cask visual-studio-code

### Draw IO

brew install --cask drawio

### Postman

brew install --cask postman

### Docker

brew install docker

### K3D

curl -s https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | TAG=v5.0.0 bash

### Slack

brew install --cask slack

### Helm

brew install helm

# Ubuntu

#### Azure CLI
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
