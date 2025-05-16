## **The Pterodactyl Wings for FreeVPS!**

Wings:

 ___**First Step**___ :-
 * cd pterodactyl
 
 ___**Second Step**___ :-
 * cd wings

 ___**Third Step**___ :- 
 * ssh -R 80:localhost:443 serveo.net 
 
## *Create new tewrminal*

 ___**Fourth Step**___ :-
 * cd pterodactyl
 
 ___**Fifith Step**___ :-
 * sudo su

___On The Sixth Step Put Your Pterodactyl Wings Node Config On The config.yml___

 ___**Sixth Step**___ :- 
 * nano /etc/pterodactyl/config.yml 

* ls  ___Check The docker file is there___

___**Seventh Step**___ :- 
* cd wings

___**Final Last Step**___ :- 
* docker-compose up -d --force-recreate

## Now Your Node Is Up! Create an server an Enjoy
