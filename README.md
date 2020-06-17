# Formation Simplon - Projet : **mini-projet SQL**
> SQL-ShoesSales - SQL Database project for Shoes Sales

### Livrables : 
    Le lien vers votre dépôt GitHub (public !) contenant : - un script SQL de création de la base.
    
### Contexte du projet : 

L'objectif est de créer la **structure d'une base de données** d'un site de vente de chaussures.

Quelques _contraintes_ concernant les données qui doivent être présentes dans la base :

    - les chaussures ont un modèle, une marque, une couleur et un prix ;
    - les clients ont simplement un nom, un prénom et une adresse email ;
    - les commandes doivent permettre d'envoyer un colis au client (donc adresse de livraison) 
    contenant l'ensemble des produits commandés ;
    - la gestion des pointures est laissé libre (seule contrainte, elles doivent être présente).

Bien entendu, l'utilisation des **clés primaires et étrangères** est nécessaire.

Avant d'écrire le script de création de la base, il est recommandé de créer un ___schéma relationnel___ type MCD ou équivalent.

Le script que vous fournirez devra créer l'ensemble des tables et champs sans erreur. 
Il sera importé de la manière suivante : 
> mysql -p < votre_fichier.sql
