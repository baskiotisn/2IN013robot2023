# 2IN013 Groupe 3 - Projet Robotique 2023-2024

* Emails : (nicolas.baskiotis|olivier.sigaud) [@] sorbonne-universite.fr
    
* Template Trello pour Scrum/Agile : [https://trello.com/b/OjUJheXD/2i013-template](https://trello.com/b/OjUJheXD/2i013-template)

Se connecter au robot

    wifi : GOPIGO0X (X=1..5) , password : GOPIGO2IN013
    Connection par ssh : ssh pi@192.168.13.1 , password : pi
    Transferer un repertoire local vers le robot : scp -r mon_repertoire pi@192.168.13.1:
    Transferer un repertoire du robot vers local : scp -r pi@192.168.13.1:repetoire repertoire_dest
    Monter un repertoire du robot sur sa machine : sshfs pi@192.168.13.1:repetoire repertoire_dest (ne pas oublier de faire un umount repertoire_dest à la fin)


N'oubliez pas de mettre votre code dans un répertoire à vous sur le robot (dans le /home/pi).

Pour plus de facilité, vous pouvez aussi créer des clés ssh pour ne pas avoir à taper le mdp à chaque fois.
