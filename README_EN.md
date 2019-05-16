# Windows 10 Developer Machine Setup

This is the script forked from Edi Wang to setup a new dev box. You can modify the scripts to fit your own requirements.

## Prerequisites

- A clean install of Windows 10 Pro v1903 en-us.
- If you are in China: a stable "Internet" connection.

> This script has not been tested on other version of Windows, please be careful if you are using it on other Windows versions.

## How to Use

### Optional

Import "Add_PS1_Run_as_administrator.reg" to your registry to enable context menu on the powershell files to run as Administrator.

### Run Install.ps1 as Administrator

- Set a New Computer Name
- Disable Sleep on AC Power
- Add 'This PC' Desktop Icon (need refresh desktop)
- Remove "Microsoft Edge" desktop shortcut icon
- Install Chocolatey for Windows (Use the packages.config file here to configure the software you need to install and the specified version number)
    - Google Chrome
    - Pot Player
    - TeamViewer
    - Notepad++
    - Visual Studio Code
	- jdk8
	- intellijidea-ultimate
    - Git
	- dejavufonts
	- python
	- tim
	- dropbox
	- nextcloud-client
- Remove a few pre-installed UWP applications
    - Messaging
    - CandyCrush
    - Bing News
    - Solitaire
    - People
    - Feedback Hub
    - Your Phone
    - My Office
    - FitbitCoach
    - Netflix
