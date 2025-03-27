This repo is a LAB for tools to try.

## Dev environnment

wsl 2 Debian
Docker Engine
Vscode

## Commands

### wsl

#### Installation : 
Lancer powershell en admin : 
wsl.exe --list --online
wsl.exe --install <Distro>
wsl.exe --install Debian
wsl.exe -d Debian

#### Lancement debian
wsl.exe
wsl.exe -l -v

connaitre la ram cpu
Get-process *vmmem*

terminer la vm
wsl -t DISTRO-NAME



#### à éviter, ces commandes utilisent le microsoft store
wsl --list --online
wsl --update
wsl --status
wsl --install -d <Distribution Name>

### Debian 
sudo
apt update
apt install 
apt list

### Debian
pour accéder au répertoire windows sur la machine Debian :
/mnt/c/Users/username

   
