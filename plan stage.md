# Génération de formulaire de masse avec Orbeon Form

## 1 - Introduction


## 2 - L'entreprise d'accueil et contexte générale du stage
DSI
### 2.1 Organigramme

<img src="organigramme.png"
     alt="Markdown Monster icon"
     style=" width: 480px;  height: 320px; text-align: center;  display: table-cell; margin-left:auto; margin-right:auto">
### 2.2 Fonction de la DSI
### 2.3 L'équipe du projet
### 2.4 Présentation du projet
Contexte:

<img src="concept.png"
     alt="Markdown Monster icon"
     style=" width: 480px;  height: 320px; text-align: center;  display: table-cell; margin-left:auto; margin-right:auto" />


### 2.5 Open project
Def : Moyen de communication, de gestion de projet, ...
Gantt, tâches, ...
### 2.6 GitLab
Echange de code source

## 3 - Présentation des outils et technologies utilisées
### 3.1 Environnement de travail
Serveur linux (debian 9)
Configuration accès : ssh (keygen, vpn)
Installation et configuration serveur (serveur applicatif, web, ...)
### 3.2 Outil de développement
Présentation Orbeon Form : Form Builder et Form Runner
Basé sur du XML (Xpath, XSLT, ...)
Base de données eXist-db
### 3.3 Choix de l'outil
 - Pour Orbeon : form, APi, ...
 - Pour eXist-db : native, ...


## 4 - Mis en oeuvre technologique
### 4.1 - Environnement de travail
Serveur linux (debian 9)
Accès au serveur : ssh (sécurisation par clé), tunneling)
Configuration de l'environnement : installation java (jdk, jre version 1.7), serveur web (apache2), serveur applicatif (tomcat8).
N.B : importance de la version logiciel dans le serveur.

### 4.2 - Formulaire avec Orbeon
Drag and Drop, architecture Form Builder -> Form runner -> eXist-db
### 4.3 - Gestion de la base de donnée (extraction, exploitation de données)
Accès à la base de données (3 type : direct, APi, interracion avec la base)
Traitement de l'information


## 5 - Mission effectué
### 5.1 - Projet BV
Devellopement d'un outil de gestion de la BV
#### 5.1.1 Contexte 
BV : limite de la licence, mis à jour utilisateurs, gestion groupe et compte utilisateur (Nombre max d'utilisateur, capacité du serveur, utilisateurs fantôme...)

Problème : changement d'environnement, 
#### 5.1.2 Solution proposé
Developper un outil qui permet de gerer les  comptes utilisateurs du BV
#### 5.1.3 - Outil Talend Open Studio
Outil en java, utilisant plusieurs composant (java) qui permet le traitement et l'intégration de données.
Conçue pour la communication, la manipulation de données entre plusieurs serveurs.

### 5.1.4 - Choix de l'outil
 - Moins de develloppement donc rend le developpeurs  plus productif.

 - fonctionne avec l'environnement Java
 - Conteneur Talend : compilateur java, fonction APi Rest  

## 5.2 Traitement de fichier

#### 5.2.1 Contexte
Transformation d'un fichier csv en XML (format TEI : Text Encoding Initiative)

#### 5.2.2 Solution proposé
Utilisé Talend Open Studio
Il existe en effet des logicoel permettant ce traitement mais très limité, en capacité, licence, ... \
