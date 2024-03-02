# Projet_cytruck

******************************************* Présentation ***************************************************

Ce programme est un outil gérant l’ensemble de la logistique une société nationale de transport routier

Il est codé en Unix/Shell et en C

Pour le code C : 

Il contient les bibliothèques suivantes : 


- stdio.h
- stdlib.h
- string.h


Il est modulé en 3 fichiers .c

- main.c 
- traitT_42.c
- traits_22.c

Avec 2 fichiers header qui reprennent les noms des fichiers .c

- traitT_42.h
- traits_22.h


Ce programme propose 5 fonctionnalités : 

Le traitement D1 : qui affiche les 10 conducteurs avec le plus de trajets

Le traitement D2 : qui affiche les 10 conducteurs avec la plus grande distance parcourue

Le traitement L : qui affiche les 10 trajets les plus longs

Le traitement T : qui affiche les 10 villes les plus traversées avec le nombre de fois
où elles sont ville de départ de trajet

Le traitement S : qui affiche les statistiques des routes ID


***************************** Un petit instant avant de pouvoir utiliser le programme : ) *******************************

 Pour utiliser le programme :
- Télécharger tous les fichiers du github
- Créer un dossier projet et transférer tous les fichier du github dans ce dossier (projet)
- ATTENTION : Renomer votre fichier à trier "data.csv" et ajouter le dans dossier projet
- Accéder avec le terminal au fichier projet
- Entrer dans le terminale "bash CY_Truck"
- entrer le chiffre correspondant au traitement pour l'executer
- Petite précision pour des raisons techniques avec le Makefile les traitements T et S doivent être confirmer avant de
  pouvoir être lancé, veillez donc bien à confirmer le traitement que vous avez choisi
  



********************************************* BUG ************************************************************************

Mise à part dans le traitement T le problème avec les villes qui ont des arrondissement aucun bug n'a été observé pour le moment. 

Si vous rencontrez un bug veuillez le signaler à une des adresses mails suivantes : 

blardoneti@cy-tech.fr 
chhibielya@cy-tech.fr
muraleeswa@cy_tech.fr
