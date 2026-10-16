# Linux_Mint
This repository contains all relevanted stuff to setup a new Linux machine.


## Allgemeines Update
>sudo apt-get update  
>sudo apt-get upgrade  


## Git installieren
Git Installieren  
> sudo apt install git   

Repository klonen  
> git clone https://github.com/08Daniel15/LinuxMint.git  

Benutzername global setzen  
> git config --global user.name "Deine Name"  
> git config --global user.email "deine.Email@beispiel.com"  

Token fuer git erzeugen  
github.com - Benutzer - Settings - Developer Settings - Personal Access Tokens - Generate new token > Generate new token (classic) - Namen vergeben - Haken bei repos setzen - Token sofort kopieren  
Beim naechsen git push mit Benutzername anmelden und anstelle des Passwortes den Token eingeben.  



## SSH
Pruefen ob ssh bereits installiert ist.  
>ssh -V  

Falls noch nicht, ssh installieren  
>sudo apt install openssh-client  

Verbindung ueber  
>ssh Benutzername@IPAdresse  


Einrichtung auf dem Raspberry Pi.  
Puefen ob ssh installiert ist  
>ssh -V  
 
ssh Verbindung ermoeglichen   
>sudo raspi-config 
 
Anschliessend Interface Options - ssh - enable   
Pruefe ob der ssh-Dienst laeuft  
> sudo sytemctl status ssh 
 
Befehl aktivieren  
> sudo sytemctl enable --now ssh 

 


##VS Code 
Anleitung zur Installation von VS Code.  
Herunterladen des .deb Packet   
> https://code.visualstudio.com/docs/setup/linux  
Installation mit
> sudo apt install ./<fiel.deb>  



##Python Packages
Python packages koennen mit dem pip installer installiert werden.  
> python3 --version  
> pip install numpy   
oder alternativ 
> sudo apt install python3-numpy   

 
