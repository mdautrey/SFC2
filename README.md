# Travaux pratiques Spring mai 2016 / JOUR 1
## Introduction Projet SFC2 : San Francisco Crime Classification
### Quel est l'objectif du projet ?
Le but du projet est 
- de se familiariser avec les données SFC2 fournies dans le cadre de la compétition Kaggle (https://www.kaggle.com/c/sf-crime/data)
- de développer des fonctions simples de synthèse de ces données en Java : liste des fichiers, nombre de lignes, liste des colonnes, contenu des colonnes, calcul de quelques indicateurs
- d'importer les données dans une base de données relationnelle
- de porter les fonctions réalisées directement sur le CSV en SQL en ajoutant des fonctions supplémentaires
- de développer un algorithme de recherche de solution optimale sur les données SFC2

Les développements seront réalisés en Java. Ils permettront de revoir les notions suivantes de Java apprises lors de la formation :
- Build du projet avec Maven (06-Maven)
- Création, organisation du domaine objet de l'application (02 - Java fondamentaux / P00, P01, P02)
- Gestion des fichiers et répertoires (02 - Java fondamentaux / P05)
- Choix des structures de données (01-Algorithmes et structure de données + 05-TP1)
- Gestion des exceptions (02-Java fondamentaux / P03)
- JDBC (02 - Java fondamenaux / P04  + 04 SQL)
- Test unitaire de l'application (05-TP1)
- Conception de l'application (code => test => design => refactor =>...) (03-UML)

Ce projet est la première partie du projet JAVA. Il fait l'objet d'une journée de travail en groupe.
Une seconde partie (JOUR 2) dédiée à la programmation Web consistera à publier les fonctions réalisées en JOUR 1 dans une interface Web.

### Quel est l'intérêt du projet ?
- Il permet de revenir sur l'ensemble des notions étudiées dans le cadre du cours Java.
- Il permet de montrer que l'on peut, en peu de temps et un peu de code Java, découvrir la structure d'un ensemble de données. Les exemples choisis sont donc à la fois simples - pour être réalisables rapidement - et utiles - vous pourriez les utiliser dans le cadre d'un "vrai" projet d'analyse de données.
- Il permet également d'aborder des notions avancées : volume de données d'un vrai fichier, problématiques éventuelles de format des données, gestion des entrées/sorties
- Au delà des aspects purement techniques de programmation, le projet vous offre l'opportunité de découvrir les données de San Francisco et de commencer à participer à une vraie compétition Kaggle
 
### Java est-il un langage adapté à ce projet ?
Oui et non :
- Non parce que la plupart des analystes de données vous suggéreraient de travailler avec R ou python qui fournissent des bibliothéques avancées de traitement des données et permettent d'aboutir plus rapidement à un résultat
- Oui parce que vous participez à ce TP pour apprendre Java, parce que Java est aussi le langage utilisé pour développer beaucoup de bibliothèques d'analyse de données (hadoop, spark, etc...), parce que travailler sur des fichiers de données permet d'aborder des aspects de la programmation que l'on ne trouve pas dans un projet "helloworld" en Java/JEE

