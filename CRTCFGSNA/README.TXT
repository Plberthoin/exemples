*---------------------------------------------------------------------*
* Ce logiciel permet de créer une configuration SNA simplement        *
*    CRTCFGSNA                                                        *
*---------------------------------------------------------------------*

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
