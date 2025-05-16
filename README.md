## **The Pterodactyl Wings for FreeVPS!**

Wings:

 ___**First Step**___ :-
 * cd pterodactyl
 
 **Second Step** :-
 * cd wings

 **Third Step** :- 
 * ssh -R 80:localhost:443 serveo.net 
 
## *Create new tewrminal*

 **Fourth Step** :-
 * cd pterodactyl
 
 **Fifith Step** :-
 * sudo su

___On The Sixth Step Put Your Pterodactyl Wings Node Config On The config.yml___

 **Sixth Step** :- 
 * nano /etc/pterodactyl/config.yml 

* ls  ___Check The docker file is there___

**Seventh Step** :- 
* cd wings

**Final Last Step** :- 
* docker-compose up -d --force-recreate

## Now Your Node Is Up! Create an server an Enjoy
