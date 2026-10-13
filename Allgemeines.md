#Hier stehen allgemeine Linux Dinge 

# scp
Secure-Copy-Protocol    
Mit dem Befehl scp koennen Dateien und Files ueber ssh kopiert werde.  
> scp raspi@IP-Adresse:/Pfad/Datei.txt Ziel  
Einen ganzen Ordner kopieren mit -r  
> scp -r raspi@IP-Adresse:/PfadZumOrdner .  
  
 Dateien auf einen Server kopieren  
> scp Datei.txt raspi@IP-Adresse:/Pfad  

