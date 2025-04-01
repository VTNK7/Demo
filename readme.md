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

   
## Cluster Kubernetes with kubeadm

Je vais créer deux machines debian avec wsl
Commands : 


### Requirements 

To follow this guide, you need:
* One or more machines running a deb/rpm-compatible Linux OS; for example: Ubuntu or CentOS.
* 2 GiB or more of RAM per machine--any less leaves little room for your apps.
* At least 2 CPUs on the machine that you use as a control-plane node.
* Full network connectivity among all machines in the cluster. You can use either a public or a private network

Commands: 

Pour voir combien de cpu disponible
lscpu

Pour vérifier la ram disponible
free -h

Pour vérifier l'espace disque
df -h

