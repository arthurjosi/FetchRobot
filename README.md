**Projet : FetchRobot**

**Developpeurs : Arthur Josi - Thibaut Desfachelles** 

Description du projet :
==
L'objectif de ce projet est de travailler avec un robot fetch et d'en faire un robot d'acceuil. 
Description plus poussée à venir.

Configuration de la connexion au fetch :
==
Ouvrir le bashrc :  
cd ~/.bashrc  
Copier les lignes suivantes en fin de fichier :  
export ROS_MASTER_URI=http://freight100.local:11311  
export ROS_IP=<my_address_ip>  

Ouvrir ensuite le fichier hosts :  
sudo nano /etc/hosts  
Ajouter l'invité correspondant au robot via la ligne suivante :   
10.1.16.68	freight100  
 
