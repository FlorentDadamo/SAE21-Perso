
#  SAE 21

## DHCP


Lors de cette SAE j'ai pu m'occuper du serveur dhcp , je me suis donc d'abord renseigner sur la fonctionnalité du dhcp avec plusieurs forum et site internet.

Je me suis donc lancer dans la configuration du dhcp avec ce que j'avais pu lire sur les forums.

J'ai donc fait ma premiere configuration.

<img src="conf_dhcp.png">

Enfin j'ai branché un PC pour faire le test et mon dhcp fonctionne bien .

photo pc dhcp 



## Apache2

Pour la suite de cette SAE j'ai pu fair ele serveur web externe
j'ai donc utliser les commande suivantes : 

    apt-get purge apache2

    apt-get install apache2

    cd var/www/html/

    nano index.html 

    rm -r index.html 

    nano index.html

    nano style.css

J'ai ensuite modifier le fichier host.

photo host apache

Enfin nous pouvons voir le site en tapant l'addresse ip du PC qui sert de serveur.

photo site apache


## DNS 
