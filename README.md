Analyse des Tirages du Loto en France

Description

Ce projet a pour but d'analyser les tirages du Loto en France depuis novembre 2019. L'objectif est d'examiner la distribution des numéros tirés, de vérifier l'équité des tirages grâce à un test statistique de Khi², et d'étudier la redistribution des gains afin de vérifier si le Loto respecte la législation française.

Structure du Projet
Le projet est structuré en plusieurs sections :
•	Chargement des données : Importation du fichier contenant l'historique des tirages.
•	Ajout de nouveaux tirages : Possibilité d'ajouter de nouveaux résultats de tirage en respectant les règles du Loto. Il s’agit ici de la possibilité de mettre à jour soit même la base de données concernant les tirages. Il n’y actuellement pas de fonction permettant de mettre à jour les gains des nouveaux tirages.
•	Test statistique de Khi² : Vérification de la régularité des tirages en analysant la distribution des numéros.
•	Analyse financière : Calcul du montant total misé, du montant redistribué aux joueurs, et du taux de retour aux joueurs (TRJ), comparé à la législation française.
Prérequis
Pour exécuter ce projet, vous devez disposer des logiciels et bibliothèques suivants :
•	R version 4.0 ou supérieure
•	Bibliothèques R requises : 
o	ggplot2
o	dplyr
o	stats
•	Le fichier loto_201911.csv contenant les données des tirages du Loto.
Installation et Exécution
1.	Clonez le dépôt GitHub : 
2.	https://github.com/Mbenailly/analyse-loto-m1-mpe.git
3.	Assurez-vous que le fichier loto_201911.csv est bien présent dans le dossier du projet.
4.	Ouvrez le fichier benaillym_Présentation_et_code_M1Mpe avec RStudio.
5.	Exécutez le fichier R Markdown pour générer le rapport d'analyse.

Explication des Résultats

•	Test Khi² : Vérifie si la répartition des numéros est conforme à une distribution uniforme.
•	Taux de Retour aux Joueurs (TRJ) : Permet de vérifier si au moins 50% des mises sont redistribuées aux joueurs, conformément à la législation française.
•	Analyse des participations : Indique combien de joueurs ont participé sur l'ensemble de la période analysée.

Note: Certains résultats ici sont volontairement simplifié pour les besoins du projet on ne prend pas en compte la possibilité pour les joueurs de miser sur plus de 5 boules contre un cout supplémentaire dans le cout de la participation par exemple. Aussi les résultats donnent seulement une approximation de la réalité sans la décrire parfaitement.
