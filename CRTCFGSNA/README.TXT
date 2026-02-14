*---------------------------------------------------------------------*
* Ce logiciel permet de créer une configuration SNA simplement        *
*    CRTCFGSNA                                                        *
*---------------------------------------------------------------------*

Vous avez besoin d'utiliser les commandes savrstx

La meilleur solution est de le faire en IP
Mais si vous êtes en V7R3 ou V7R4 cette option n'existe pas
de plus cette configuration est plus compliquée, vous devrez configurer un
Certificat sur l'application

Si vous voulez utiliser SNA voici ce qu'il vous faut faire    

Attention :

Si vous êtes sur une version ultérieure *HPRIP n'existe pas vous devrez 
configurer en *ANYNET, vous trouverez des exemples sur internet 

Pour le configurer :

Vous devez connaitre :
Le nom SNA de votre système distant
==>DSPNETA
Son adresse IP
==>CFGTCP , option 1

pour tester vous pouvez faire :
==>APING SYSTEME

Vous devrez faire la même chose sur le système en face 

Exemple :

 CRTCFGSNA SYSTEME(SYSTEMB)             
           ADRESSEIP('192.168.1.45')     
 

*** Listes  des sources
CMDCRTCFGSNA CLLE    Création configuration SNA 
CLPCRTCFGSNA CMD     Création configuration SNA
TXTREADME TXT     readme do logiciel 
*** Fin listes des sources
