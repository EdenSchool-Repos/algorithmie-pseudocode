# 1. Exercices simples
Exercice 1 :
Écrire un algorithme d’une action qui échange deux variables A et B

Exercice 2 :
Écrire une fonction qui donne les carré d’un réel

Remarques :
Dans une fonction, la seule variable qui est définie est celle du résultat, les autres sont définies dans la fonction mère, et apparaissent ici en tant qu’entrées.
Dans une fonction, ne pas oublier de retourner le résultat.

# 2. Exercice en utilisant les structures SI…ALORS…SINON et SELON…QUE
Exercice 3 :
Écrire une action qui fournit les félicitations ou l’ajournement d’un élève suivant sa note en utilisant Si-alors-sinon.

Exercice 4 :
Écrire un programme qui donne la valeur absolue de 2 réels :

Remarque : on peut aller plus vite en créant une fonction valeur absolue et en faisant appel à cette fonction dans une action :

Et

Écrire 5 :
Faire un programme qui donne le volume d’un cylindre en faisant appel à une fonction ‘aire d’un cercle’.

Exercice 6 :
Écrire un algorithme permettant de résoudre une équation du premier degré

Exercice 7 :
Écrire un algorithme permettant de résoudre une équation du second degré en utilisant des si alors..

Écrire le même algorithme avec des selon-que :

Exercice 8
Écrire un algorithme qui donne la durée de vol en heure minute connaissant l’heure de départ et l’heure d’arrivée.
 1. On considère que le départ et l’arrivée ont lieu même jour
 2. Idem mais sans faire les conversions en minutes
 3. On suppose que la durée de vol est inférieure à 24 heures mais que l’arrivée peut avoir lieu le lendemain.

Remarque : l’opération % (modulo) permet de calculer le reste de la division entière.

Exercice 9
 1. Écrire une fonction max3 qui retourne le maximum de trois entiers
 2. Écrire une fonction min3 qui retourne le minimum de trois entiers
 3. Écrire une fonction max2 qui retourne le maximum de deux entiers
 4. Écrire une fonction max3 qui retourne le maximum de trois entiers en faisant appel à max2

Exercice 10
Écrire avec des Si Alors Sinon une action permettant la saisie d’une note n (0≤n≤20) et qui affiche la mention (n≥16 : TB, n≥14 : B, n≥12 : AB, n≥10 : Passable, n≥10 : Ajourné)

Alternative : écrire le même programme avec des Selon Que :

Exercice 11
Soit l’algorithme suivant :
Action : Permis_voiture
Var : permis, voiture : booléen
Début :    Écrire (« avez-vous le permis ? (0/1) »)
Lire (permis)
Écrire (« avez vous une voiture ? (0/1) »)
Lire (voiture)
Si non permis ou voiture alors
Si voiture alors écrire (« conduisez moi à la gare »)
Sinon écrire (« j’ai une voiture pas chère »)
Sinon
Si voiture alors écrire (« vous êtes hors la loi »)
Sinon écrire (« vive le vélo »)
Fin

 1. Écrire l’arbre des conditionnelles
 2. Corriger les tests pour que tous les cas soient couvert de manière cohérente
 3. Faites correspondre les actions et les tests correctement
 4. Si possible, écrire cet algorithme avec des selon que.

Exercice 12
Écrire un programme calculatrice permettant la saisie de deux entiers et une opération –booléen- ( +, - , / , x ) et affichant le résultat. Donner avant cela les spécifications, la solution en langage naturel, les structures de données.

Spécifications :

Solution en langage naturel :

Structure de données :

# 3. Exercices en utilisant les structures répétitives TANT QUE et REPETER…JUSQU'A et POUR
Exercice 13
Écrire le programme qui affiche la somme d’une suite d’entiers saisie par l’utilisateur se terminant par zéro.
Exemple : l’utilisateur entre 1, puis 5, puis 2, puis 0 : affiche : 8
 1. Donner les spécifications
 2. Donner la solution en langage naturel
 3. Indiquer les structures de données
 4. Faites l’algorithme

Spécifications :
Solution en langage naturel : 
Structure de données :
Algorithme :

Exercice 14
Écrire un algorithme qui affiche la moyenne d’une suite d’entiers se terminant par zéro (le zéro n’entrant pas en compte dans la moyenne : il est juste la pour indiquer la fin de saisie)
 1. Donner les spécifications
 2. Donner la solution en langage naturel
 3. Indiquer les structures de données
 4. Faites l’algorithme

Spécification :
données : suite d’entier se terminant par zéro
résultat : la moyenne de ces entiers (zéro exclu)

Exercice 15
Écrire un algorithme permettant la saisie d’une suite d’entiers se terminant par zéro et vérifier si cette suite contient deux entiers consécutifs égaux en utilisant les structures tant que.
 1. Donner les spécifications
 2. Donner la solution en langage naturel
 3. Indiquer les structures de données
 4. Faites l’algorithme

Refaire le même algorithme en utilisant une structure répéter jusqu'à

Exercice 16
Écrire un algorithme qui affiche le maximum d’une suite se terminant par zéro
 1. Donner les spécifications
 2. Donner la solution en langage naturel
 3. Indiquer les structures de données
 4. Faites l’algorithme

Exercice 17
Écrire un programme mettant en œuvre le jeu suivant :
Le premier utilisateur saisi un entier que le second doit deviner. Pour cela, il a le droit à autant de tentatives qu’il souhaite. A chaque échec, le programme lui indique si l’entier cherché est plus grand ou plus petit que sa proposition.
Un score indiquant le nombre de coups joués est mis à jour et affiché lorsque l’entier est trouvé.
 1. Donner les spécifications
 2. Donner la solution en langage naturel
 3. Indiquer les structures de données
 4. Faites l’algorithme

Exercice 18
Écrire un algorithme permettant de calculer le PGCD de deux nombres en utilisant l’astuce suivante : soustraite le plus petit des deux entiers du plus grand jusqu'à ce qu’ils soient égaux
Écrire le même programme en utilisant l’algorithme d’Euclide : d’une part en utilisant uniquement les structures TANT QUE, d’autre part en utilisant uniquement les structures REPETER JUSQU'A.

Même programme avec Euclide et des TANT QUE :

Même programme avec Euclide et des REPETER JUSQU'A :

Exercice 19
Écrire avec la commande POUR un algorithme qui permet de faire la somme d’une suite de nombre entrée par l’utilisateur. Faire la même chose en comptant par pas de –1.

Même programme par pas de –1 :

Exercice 20
Traduire le POUR de l’algorithme suivant en REPETER JUSQU'A :
Action : bidon
Var : k, nb : entiers
Début
Lire (nb)
Pour k de 1 à nb faire
Écrire (k)
Fin

Exercice 21
Écrire une fonction qui fait la somme des entiers compris dans un intervalle.

Exercice 22
Écrire une fonction multiplication de a et b par addition successives.

# Exercices sur les Tableaux

Exercice 23
Écrire une action qui permette la saisie d’un tableau croissant : si T[k]<T[k+1] on enregistre, si T[k]>T[k+1] on redemande la saisie d’un nombre plus grand

Exercice 24
Écrire une fonction retournant le maximum d’un tableau de taille n.
Faire le même algorithme mais qui ne retourne que l’indice de la case du tableau contenant le maximum du tableau.

# Exercices généraux sur les actions paramétrées

Exercice 25
Écrire une fonction Afficher qui affiche a l’écran le contenu d’un tableau. Écrire aussi l’action principale qui permettra de comprendre comment fonctionne cette fonction afficher.

{Ne pas oublier d’indiquer les paramètres du tableau !}

Action principale

Résultat à l’écran :

Exercice 26
Écrire une fonction qui permet la saisie d’un tableau. Faite aussi l’action principale qui permettra d’accéder a cette fonction saisie mais aussi d’afficher dans un second temps le résultat

Ou afficher est la fonction de l’exercice 1.


Exercice 27
Écrire une fonction qui calcule le nombre d’inversion d’un tableau de taille n (c’est à dire i<j et tab[i]>tab[j] pour tout i et j.)

Exercice 28
Écrire une action qui affiche les n premiers éléments de la suite définie par u0=1 et un+1=somme de k=0 jusqu'à n de (uk*un-k)
Aide : stocker les éléments dans un tableau toto avec toto[0]=1. Puis on utilise une boucle imbriquée pour calculer toto[n+1]=somme k=0 à k=n de toto[k]*toto[n-k].

Exercice 29
Voyons maintenant quelques exercices rudimentaires de changements dans un tableau
Écrire une action permettant de remplacer toutes les occurrences de x par y dans un tableau de taille n.
Écrire un algorithme qui échange les valeurs des cases i et j dans un tableau.
Écrire un programme qui inverse un tableau. (exemple : 1 5 6 7 3 devient 3 7 6 5 1)

# Entités : types structurés
Explications 1 :
Les types structurés sont :
 - les tableaux (voir les exercices précédents)
 - les entités (ou l’on regroupe plusieurs types sous un même objet)

Exemple :
Etudiant (nom, groupe, note)
Type : Etd : entité (
Nom : chaîne de caractère ;
Groupe : caractère ;
Note : entier ;
) ;

Pour faire appel à ce type d’entité on fera dans la fonction :
Var : Tetd toto ;
Toto.nom=alex
Toto.groupe=A
Toto.note=15
Écrire (« l’étudiant », toto.nom, « du groupe », toto.groupe, « a eu », toto.note)

Exercice 30
Proposer une entité de données pour stocker un point dans le plan

Exercice 31
Écrire les en-têtes des fonctions/actions suivantes :
 - saisie d’un point
 - affichage d’un point
 - calcul de la distance entre deux points
 - projection d’un point sur l’axe des abscisses

Écrire ensuite les algorithmes de ces fonctions.
Faire une action principale qui demande la saisie de deux points, calcule la distance entre ces deux points et affiche les résultats.

Explications 2 :
Nous ne rentrerons pas ici le tableau comme nous l’avons fait précédemment :
Nous utiliserons les entités. Ainsi la déclaration se fera de la manière suivante :
Const MAX=100
Type : TtabVar=entité (
Tab : tab[MAX] d’entier
Taille : entier
)

Ainsi, dans une fonction, on aura :
TtabVar : toto
Toto.tab[15]<=1 {pour entrer une valeur de tableau}
Toto.taille++ {On augmente la taille du tableau au fur et a mesure
Avantage de cette nouvelle manière d’entrer un tableau : on peu avoir un tableau de taille variable.


Exercice 32
Écrire un algorithme qui permet de rentrer les données d’un tableau de type TtabVar et dont on connaît la taille.
Écrire ensuite un algorithme qui permet de rentrer les données d’un tableau de type TtabVar et ou l’on ne connaît pas la taille.

Exercice 33
Écrire un algorithme qui permet de rentrer un tableau de taille variable de Tpoint (voir exercice 30 et 31). Pour cela, il faudra au préalable créer un nouveau type d’entité.

Exercice 34
Écrire un algorithme qui détermine le point ( ( !) c’est à dire son indice)le plus au nord et le point le plus a l’ouest dans un tableau de Tpoint.
Faire ensuite une action principale qui demande la saisie d’un tableau de Tpoint à l’utilisateur (voir exercice 33) et affiche l’élément le plus au nord et l’élément le plus à l’ouest.

Exercice 35
Écrire un algorithme qui détermine la distance maximale entre deux points d’un tableau de Tpoint

# Tableaux triés et découpages fonctionnels
Exercice 36
Le but de l’exercice est de créer une action de saisie de tableau, qui trie, au fur et à mesure des entrées, les valeurs par ordre croissant dans le tableau.
Exemple :
Soit le tableau suivant :

0 1 2 3

2 5 7 9

Comment insérer 6 dans le tableau trié (en supposant qu’il n’y a pas de doublon dans le tableau) ?
 - Je cherche la bonne position (ici : la case d’indice 2)
 - Décalage à droite si nécessaire :

0 1 2 3 4

2 5 7 7 9
   
Insertion de l’élément

0 1 2 3 4

2 5 6 7 9

On a donc ici le découpage fonctionnel :

On va donc créer une fonction IndiceEltSup qui cherche la bonne position, une action Insérer qui inclue le nombre entré dans la bonne case du tableau, et une action DécalageDroite qui décale comme dans l’exemple toutes les cases d’un rang vers la droite si nécessaire.

Exercice 37
Faire un algorithme qui fait une recherche dichotomique dans un tableau trié. On pourra utiliser les fonctions de l’exercice précédent.

Nous allons créer une action qui définie la zone de recherche, puis l’action RechercheDicho qui opérera la recherche dichotomique dans l’intervalle définie par la zone de recherche.

Exercice 38
Faire un algorithme qui supprime une valeur dans un tableau trié. On pourra utiliser des fonctions des deux exercices précédents.

Le but est d’utiliser la recherche dichotomique de l’exercice précédent pour trouver dans le tableau l’indice de la valeur que l’on veut supprimer puis faire un décalage à gauche pour remettre en place les valeurs (sans qu’il y ait de vide dans une case du tableau)

# Les Chaînes
On va maintenant faire des exercices sur les chaînes de caractères. En pratique on pourra définir une chaîne de caractères de deux manières :

Const MAX entier = 100
Type Tchaine = entité (    tab : tableau[MAX] de caractères
Longueur : entier)

Ou bien :

Const MAX entier = 100
Type Tchaine = tableau [MAX] de caractères
{Avec la sentinelle END}

Exercice 39
Faire un algorithme qui détermine la longueur d’une chaîne de caractères.
Faire ensuite de deux manières différentes, une fonction qui permet de copier la chaîne d’une source dans une chaîne destination.

Exercice 40
Faire une fonction de concaténation (ajoute à la fin de la première chaîne de caractères le contenu de la deuxième chaîne de caractères.)
Faire une fonction de Comparaison qui compare deux chaînes de caractères suivant l’ordre lexicographique.
Faire une fonction qui efface une partie de la chaîne en spécifiant une longueur d’effacement et un indice à partir duquel il faut effacer.

Exercice 41
Écrire l’en-tête d’une action multi décalage à droite qui décale à droite les éléments d’une chaîne à partir d’un certain indice et insère des cases vides à la place. (des actions de multi décalage ont déjà été vue avec les tableaux, on ne demande pas d’en refaire une ici, ce référer aux exercices sur les tableaux)
Faire une action d’insertion. On pourra pour cela utiliser au paravent la fonction multi décalage à droite précédente.
Faire une action de remplacement d’une partie d’une chaîne de caractères par une autre chaîne de caractères dont la longueur n’est pas forcément la même. On pourra utiliser des fonctions des exercices 39 et 40.
Faire une fonction Extraire qui prend une partie de chaîne de caractères à partir d’un certain indice et la met dans une chaîne destination.
Faire une fonction de recherche qui recherche une chaîne dans une chaîne de caractère et retourne un indice si à partir de cette case on a la chaîne cherchée. Sinon, elle retourne –1.
Faire une action qui changent toutes les occurrences d’une chaîne dans une chaîne de caractères par une autre chaîne tampon.

# Les fichiers
Rappelons tout d’abord comment on manipule les fichiers en ASD.
On ne manipule que les identificateurs de fichiers. On ne se soucie donc pas des fichiers sources.

Pour ouvrir un fichier :
OuvrirFichier (IdFic, ModeOuverture)
Avec ModeOuverture = lecture ou écriture ou rajout.

Pour fermer un fichier
FermerFichier (IdFic)

Pour lire un fichier
LireFichier (IdFic, élément) cela correspond à Lire(n) ⬄ cin>>n

Pour écrire un fichier
ÉcrireFichier (IdFic, élément) cela correspond à Écrire(n) ⬄ cout<<n

Exercice 42
Faire l’algorithme d’une action qui lit un fichier d’entiers et affiche tous les entiers de ce fichiers qui sont pairs.
Écrire une action qui lit un fichier d’entiers et met dans un autre fichier d’entiers les valeurs paires.
Faire une fonction qui recherche un entier x dans un fichier d’entiers et retourne vrai si x est dans le fichier.

Exercice 43
Faire une action de fusion de deux fichiers d’entiers. Le fichier de sortie doit être trié.

Exercice 44
Soit le type suivant :
Type : Tetd = entité (    Nom : chaîne
Numéro : étudiant
Notes : tableau [5] d’entiers
Moyenne : entier)
On suppose que la fonction de saisie
Fonction SaisieEtd () : Tetd
Permettant de saisir un tableau de Tetd existe. On pourra donc s’en servir

Écrire une fonction qui permet de saisir un groupe d’étudiant dans un fichier.
Écrire une fonction qui permet de calculer la moyenne générale d’un groupe d’étudiant.
