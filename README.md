# PICS-Ccloud
 
Auteurs : 
* Mehdi Shita
* Saruhan Sathananthan
* Henri Delille

## Adresse : cloud.pics-cloud.duckdns.org

## Prérequis :

_Compte Google Cloud Platform_
_VM Debian 11 avec Docker et Docker Compose_

## Installation :
1. Dans le dossier Docker Compose modifier les fichiers pour qu'ils correspondent à vos paramètres
2. Dans la VM exécuter, ```docker compose -f swag.yml up```
3. Dans la VM exécuter, ```docker compose -f nexcloud.yml up```
4. Dans la VM exécuter, ```docker compose -f duckdns.yml up```
