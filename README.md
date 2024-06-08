# JPA Hibernate : Gestion des comptes bancaires 

Objectif : 
L’objectif du TP est d’étudier le mapping objet relationnel et de se familiariser avec les 
annotations JPA à travers l’implémentation des entités JPA d’une application de gestion des 
comptes bancaires. 

Partie I : Création d'une application TRADIV AFRIQUE avec des entités bean de l’application 
L’application gère deux types de comptes : compte courante et compte épargne. Chaque compte 
subit plusieurs opérations de versement ou de retrait. Un client peut posséder plusieurs 
comptes mais un compte est associé à un seul client 
/*********************************************************************************************/
1. Créez un projet Spring Starter Project avec le nom Banque avec com.gestionbanque 
comme package de base et Maven comme gestionnaire de dépendance. Choisir JPA, 
MySQL, Rest Repositories, Thymeleaf et Web comme dépendances. 
2. Créez un package com.gestionbanque.entities et y mettre les différentes classes entité 
de l’application : Client, Compte, CompteCourant, CompteEpargne, Operation, 
Versement et Retrait. 
