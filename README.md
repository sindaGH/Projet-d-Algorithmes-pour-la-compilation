# Projet-d-Algorithmes-pour-la-compilation
Le but de ce projet est d’écrire en C un programme prenant en entrée un automate fini non-déterministe,
et fournissant en sortie un automate fini déterministe.
## Pour commencer
prendre en entrée un fichier texte contenant la description d’un automate fini non-déterministe,le fichier doit respecter la forme suivante:
la première ligne contient un entier, |Q|, et les états de l’automate sont numérotés de 0 à |Q| − 1 ;
l’état numéroté 0 est l’état initial s ;
— la deuxième ligne contient des entiers séparés par des espaces, qui sont les éléments de F ; si l’automate
n’a pas d’état accepteur, cette ligne est vide ;
— chaque ligne suivante contient un entier, un caractère, et un autre entier, séparés par des espaces,
et décrit une transition de ∆.

### Installation

Pour installer le projet il suffit d'éxécuter cette commande :
git clone "lien"
vous obtenez au final un dossier "...".tgz
### Compiler le programme
$ tar xvfz "".tgz
$ cd ""
$ make

#Lancer le programme
$ ./DetMin ./AFN1 "ChainedeCaractères"


## Auteurs
Hidouri Balkis
Gharsi Sinda Chams el ghozlen
