Projet Master 2 (Prolog) : Petit jeu sur le temps de participe passé.
===================

####Description

Ce projet consiste à une application développé en Prolog dont les acteurs sont l’enseignant et l’apprenant. L’objectif de cette application est de créer un petit jeu sur le temps de participe passé.

L’enseignant donne des phrases sous la forme Participe passé, qu’ils sont stockées dans un fichier s’appel copier.txt
Et l’apprenant doit conjuguer les phrases qui s’affichent sous forme infinitif et qui sont stocké dans le fichier inf.txt.

#####J’ai utilisé 4 fichiers texte :

- Copier.txt : contient les phrases sous forme Participe Passé.
- Inf.txt : contient les phrases sous infinitif.
- Fiche.txt : contient le résultat de tokinisation.
- Nom.txt : contient le nom de l’enseignant ou l’apprenant.

#####Mon application est composée par 8 fichiers .p2

######Fichier_Genarale.p2 :
Permet d’appeler tous les fichiers.

######Essaie.pl :
1. Lire la phrase entrée par l’enseignant.
2. Tokoniser la phrase, et mettre le résultat dans le fichier fiche.txt
3. Convertir la phrase tokinisé à une liste (L).
4. Vérifier la forme de phrase contient participe passé ou non à l’aide le prédicat RDUCE_SHIFT qu’il prend comme entrer la liste L
5. Si le teste est vraie Sauvegarder la phrase dans le fichier copier.txt
6. Convertir le verbe de phrase tokinisé à un verbe infinitif avec prédicat sauv(X)
######Jeu.pl :
1- Afficher les phrases phrase par phrase qu'ils sont sous la forme infinitive
2- Demander la réponse de l'étudiant
3- Lire la réponse
4- lire la correction du fichier copier.txt
5- comparer la réponse par la correction
6- Si le test vrai passer à la phrase suivante

######Afficher.pl :
Afficher la correction.

######Etapes.pl :
Afficher les étapes de l’application.

######Eleve.p2
Afficher manu étudiant.

######Ensg.p2
Afficher menu enseignant.

######Menu. P2
Afficher menu générale

####Perspectives :

On peut faire plusieurs améliorations et évolutions restent envisageables pour compléter ce travail et lui rendre assez satisfaisant.
Améliorer l’utilisation et les interfaces utilisateur.
Enrichir les dictionnaires.
Améliorer le prédicat RDUCE_SHIFT pour tester des autre formes.
