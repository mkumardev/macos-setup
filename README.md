# macos-setup
# Project Name

This project uses a Taskfile to manage the installation of various tools and applications using Homebrew.

## Getting Started

To get started with this project, you'll need to have [Homebrew](https://brew.sh/) installed on your machine.

## Tasks

The `Taskfile.yaml` file defines the following tasks:

### Install Tools

This task checks if the specified tools are already installed. If not, it installs them using Homebrew. The tools include:

- chef-workstation
- devtoys
- google-cloud-sdk
- maccy

To run this task, use the following command:

```sh
task install-tools
```

### Install Apps
This task checks if the specified applications are already installed. If not, it installs them using Homebrew Cask. The applications include:

google-chrome
brave-browser
slack
iterm2
notion
sublime-text
evernote
zoom
todoist
docker
visual-studio-code
tableplus
alfred
whatsapp
rectangle
tunnelblick
bitwarden
dropbox
fing
folx
hiddenbar
lens
multipass
teamviewer
warp
To run this task, use the following command:

```sh
task install-apps
```
