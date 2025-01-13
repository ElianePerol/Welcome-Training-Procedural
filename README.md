# Welcome Training : Application de Gestion de Classes avec Signature en Ligne

## Contexte
Ce projet, réalisé dans le cadre de mon **BTS SIO SLAM**, consiste en une **application web** permettant de gérer les classes, les emplois du temps, les utilisateurs (enseignants, élèves et administrateurs) et la présence en cours. 
L'application est développée en **PHP procédural**, avec une base de données **MySQL** et une interface utilisateur simple et responsive.
Il s'agit d'un projet **non abouti**, encore en cours de développement, qui nécessite des améliorations et des fonctionnalités supplémentaires.

## Fonctionnalités Principales
- **Gestion des utilisateurs** : Création, modification et suppression des enseignants, élèves et administrateurs.
- **Gestion des classes et des matières** : Assigner des enseignants et des élèves aux classes, gérer les matières et l'emploi du temps.
- **Présence** : Permet aux enseignants de faire l'appel et aux élèves de valider leur présence en cours, avec horodatage.
- **Authentification sécurisée** : Connexion avec mot de passe chiffré et gestion des rôles (administrateur, enseignant, élève).

## Technologies Utilisées
- **Backend** : PHP natif (procédural)
- **Frontend** : HTML5, CSS3 (avec Bootstrap), JavaScript
- **Base de données** : MySQL
- **Sécurité** : Cryptage des mots de passe avec `password_hash()`, gestion des sessions sécurisées, HTTPS
