⚫ Guide de configuration du serveur web sous Linux

## INTRODUCTION
Ce guide fournit des instructions détaillées pour configurer un serveur web sous Linux.
Il s'adresse aux administrateurs système, aux étudiants curieux et aux développeurs qui 
souhaitent déployer un serveur web sur une machine Linux.

## PRÉREQUIS
- Une machine Linux avec un accès root ou un utilisateur disposant de privilèges administratifs.
- Connexion Internet pour installer les packages et les dépendances nécessaires.

## Configuration du serveur web
1. Installation du serveur web
   - Étape 1 : Mettez à jour les paquets système (https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).
   - Étape 2 : Installez Apache(si nécessaire PHP, MySQL...)_(https://github.com/kanishkamakhija/Configuring-Linux-Web-Server ).
   - Étape 3 : Configurez les fichiers de configuration du serveur web [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).

2. Configuration du pare-feu
   - Étape 1 : Activez les ports nécessaires pour le serveur web [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).
   - Étape 2 : Configurez les règles de pare-feu pour autoriser le trafic HTTP/HTTPS [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).

3. Configuration du domaine
   - Étape 1 : Enregistrez un nom de domaine [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).
   - Étape 2 : Configurez les enregistrements DNS pour pointer vers votre serveur web [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).

4. Configuration de la sécurité
   - Étape 1 : Activez HTTPS en installant un certificat SSL [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).
   - Étape 2 : Configurez les règles de pare-feu pour autoriser le trafic HTTPS [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).
   - Étape 3 : Appliquez les bonnes pratiques de sécurité pour le serveur web [[2](https://github.com/kanishkamakhija/Configuring-Linux-Web-Server).

## TEST DE CONFIGURATION
- Ouvrez un navigateur web et accédez à votre site web pour vérifier si la configuration fonctionne correctement.

## Ressources supplémentaires
- [Lien vers la documentation officielle d'Apache](https://httpd.apache.org/docs/)
