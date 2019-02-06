> Note: Dans le monde des <a href="https://fr.wikipedia.org/wiki/Coding_dojo">coding dojo</a>,
> ceci est la donnée d'un "<a href="https://fr.wikipedia.org/wiki/Coding_dojo#Kata">kata</a>"
> dans le sens d'un _exercice de programmation_. Il est destiné à toute personne 
> voulant apprendre et parfaire ses connaissances sur le sujet.
>
> Ce document est en cours d'élaboration, toutes propositions, idées, pull request, 
> etc... seront très appréciées.


# kata-coins
Kata d'exploration du [Problème du rendu de monnaie](https://fr.wikipedia.org/wiki/Probl%C3%A8me_du_rendu_de_monnaie).

## But
Le but de ce kata est de voir les algorithmes de rendu de monnaie, comme la [méthode glouton](https://fr.wikipedia.org/wiki/Algorithme_glouton) ou cela du [sac à dos — KP](https://fr.wikipedia.org/wiki/Probl%C3%A8me_du_sac_%C3%A0_dos). Il est aussi intéressant de voir comment on peut améliorer le système, par exemple en modifiant la situation de départ.

## Comment procéder
[Forker](https://github.com/epfl-dojo/kata-coins/#fork-destination-box) le repo et créer une branche (`git checkout -b username-langage` par exemple `git checkout -b dojo-nodejs`, depuis votre fork). Faites ensuite une pull request pour l'ajouter à ce repo en vous ajoutant comme contributeur en bas de ce fichier.

## Donnée
Notre distributeur accepte les pièces de 10, 20 et 50 centimes, 1, 2 et 5 francs et les billets de 10 et 20 francs. Par contre il donne le change qu'en pièces. La situation de départ est de 25 pièces par montant.

Les utilisateurs peuvent acquérir des AAA à 1.70, des BBB à 2.10, des CCC à 2.30, des DDD à 2.50, des EEE à 2.90 et des FFF à 3.40.

Note: le stock est infini.

## Problème 1
La liste suivante présente par ordre chronologique les achats effectués par les utilisateurs. A partir de la situation initiale, quel est le montant restant dans l'appareil et quelle est la répartition de pièces/billets ?

| Achats | Montant donné | Change |
| --- | --- | --- |
| AAA | 2.- | 2 x 1.- |
| BBB | 5.- | 1 x 5.- |
| A compléter... |

## Problème 2
A compléter... (Remplir des tests languages agnostiques / [Gerkins](https://docs.cucumber.io/gherkin/reference/) ?)

## Contributeurs (langages par ordre alphabétique)
  * [aaa](./bbb.sh) → [@ccc](https://github.com/ccc)
  * ...
