Objectif

Vos goûts cinématographiques sont très moyens, à tel point que lorsque vous demandez à vos K meilleurs copains quelle note ils ont donnée à un film, vous l'avez généralement évalué à la moyenne de leurs notes.

Un nouvel épisode, Rocky VI, arrive au cinéma. Est-il vraiment mieux que les précédents ?
Pour protéger votre santé mentale, vous décidez de prédire votre appréciation de Rocky VI avant d'aller (ou non) le voir.

Vos N copains ont tous vus les 5 premiers épisodes Rocky (sinon ils ne seraient pas vos copains) ainsi que le nouvel épisode.
Mais pour vous, vos K meilleurs copains (K≤N) sont ceux qui comptent vraiment, même si vous n'avez pas encore décidé qui ils sont.
Pour choisir ces K copains parmi N, vous allez prendre ceux qui ont des goûts les plus similaires aux vôtres sur les 5 premiers épisodes Rocky.

La distance entre vos goûts et ceux d'un copain donné est calculée comme suit :

- pour chacun des 5 premiers Rocky, on regarde l'écart entre votre note et la note donnée par le copain en question (plus précisément, la valeur absolue de la différence) ;
- on prend ensuite la somme des écarts pour les 5 épisodes.

Les K meilleurs copains sont alors ceux dont les goûts sont à plus petite distance de vous. Pour vous épargner un terrible dilemme on vous garantit que le choix est unique, ainsi il ne peut pas y avoir deux K-ièmes plus proches copains ex æquo. Vous calculerez la moyenne de leurs notes pour le nouveau Rocky arrondie à l'entier inférieur : ceci vous donnera une prédiction de la note que vous risquez de mettre à cet épisode si vous le regardez.

Données

Entrée

Ligne 1 : cinq entiers entre 0 et 10 inclus séparés par des espaces, les notes que vous avez données aux cinq premiers Rocky.
Ligne 2 : un entier N compris entre 1 et 20 inclus, représentant votre nombre de copains.
Ligne 3 : un entier K compris entre 1 et N inclus, représentant votre nombre de meilleurs copains.
Lignes 4 à N+3 : six entiers compris entre 0 et 10 séparés par des espaces, chaque ligne correspond à un de vos copains, les cinq premiers entiers sont les notes des premiers Rocky, le sixième la note du nouvel épisode.

Sortie

Un entier, indiquant la moyenne des notes que vos K meilleurs copains ont donnée au nouvel épisode, arrondie à l'entier inférieur.

Exemple

Pour l'entrée suivante :
10 7 3 4 3
4
2
9 4 7 2 1 1
2 1 3 2 10 5
9 10 10 9 10 10
8 9 2 4 3 4

Vos deux meilleurs copains sont le premier (distance 12 = (10-9)+(7-4)+(7-3)+(4-2)+(3-1)) et le dernier (distance 5) de la liste, ils ont donné les notes 1 et 4 au nouvel épisode, vous allez donner la moyenne (1+4)/2 arrondie à l'entier inférieur, la réponse est donc 2.
