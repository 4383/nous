# Noûs

Introduction et analyse de l'intelligence artificielle.

## Origine du nom

En philosophie et dans l'Antiquité grecque, le noûs (νοῦς), plus rarement nous 
ou noos, est l'esprit, l'intellect, la raison. Pour Platon, noûs désigne le 
plus souvent la partie la plus divine de l'âme, l'intelligence

## Objet de ce document

Ce document/projet vise à analyser comprendre l'intelligence artificielle 
et à introduire sa mise en oeuvre.

Il a pour objectif principal de m'aider personnellement à comprendre les 
rouages de cette science et également de partager mon analyse avec les
personnes désireuses d'en faire de même.

## Poser un problème de datascience

L'objectif du machine learning est d'apprendre à partir de données 
issues d'observations réelles.

Les données peuvent-être de diverses natures et provenir de différentes sources.
Selon le cas, elles sont plus ou moins complexes à manipuler.

Les algorithmes visent à en extraire des régularités qui permettront
l'apprentissage. On distingue :
- les algorithmes supervisés (quand il existe une valeur à prédire)
- les algorithmes nons suppervisés (quand il n'y a pas de valeur à prédire)
- les algorithmes de régression (quand la valeur à prédire est continue)
- les algorithmes de classification (quand la valeur à prédire est catégorielle)

Pour utiliser ces algorithmes, les données doivent être mises en forme sous une
représentation matricielle.

Source: Data science - fondamentaux et études de cas - 
Eric Biernat, Michel Lutz - Editions Eyrolles 2016

## Représentation matricielle des données

### Les matrices

En mathématiques, les matrices sont des tableaux de nombres qui servent à 
interpréter en termes calculatoires et donc opérationnels les résultats 
théoriques de l'algèbre linéaire et même de l'algèbre bilinéaire. 
Toutes les disciplines étudiant des phénomènes linéaires utilisent les matrices.

#### Définition

Une matrice à m lignes et n colonnes est un tableau rectangulaire de 
m × n nombres, rangés ligne par ligne. 
Il y a m lignes, et dans chaque ligne n nombres.

Plus formellement et plus généralement, soient I, J et K trois ensembles 
(K sera souvent muni d'une structure d'anneau ou même de corps commutatif).

On appelle matrice de type (I, J) à coefficients dans K, toute famille 
d'éléments de K indexée par le produit cartésien I × J, c'est-à-dire toute 
application A de I × J dans K.

Le plus souvent, comme dans toute la suite de cet article, les ensembles I 
et J sont finis et sont respectivement les ensembles de nombres entiers 
{1, …, m} et {1, …, n}. Dans ce cas, on dit que la matrice a m lignes et n 
colonnes, ou qu'elle est de dimension ou taille (m, n). 

ou plus simplement (ai,j) si le contexte s'y prête.

On représente généralement une matrice sous la forme d'un tableau 
rectangulaire. Par exemple, est représentée ci-dessous une matrice A, à 
coefficients entiers, et de dimension (3,4) :

![exemple de matrice](/static/matrice.png)

Dans cette représentation, le premier coefficient de la dimension est le 
nombre de lignes, et le deuxième, le nombre de colonnes du tableau. 
Une matrice pour laquelle le nombre m de lignes est égal au nombre n de 
colonnes sera dite matrice carrée de taille (ou d’ordre) n. 
Une matrice ne comportant qu'une seule ligne et n colonnes est appelée 
matrice ligne de taille n. 

Une matrice comportant m lignes et une seule colonne est appelée matrice 
colonne de taille m.

#### Les vecteurs

En mathématiques, un vecteur est un objet généralisant plusieurs notions 
provenant de la géométrie (couples de points, translations, etc.), de 
l'algèbre (« solution » d'un système d'équations à plusieurs inconnues), 
ou de la physique (forces, vitesses, accélérations, etc.).

Rigoureusement axiomatisée, la notion de vecteur est le fondement de la 
branche des mathématiques appelée algèbre linéaire. À ce sens, un vecteur est 
un élément d'un espace vectoriel, ce qui permet d'effectuer des opérations 
d'addition et de multiplication par un scalaire. Un n-uplet peut constituer 
un exemple de vecteur, à condition qu'il appartienne à un ensemble muni des 
opérations adéquates.

## Licence

Ce document est sous licence GNU GPL V3.

Cela signifie que vous pouvez partager et modifier librement ce document mais 
vous avez obligation de partager et publier librement à votre tour les 
modifications que vous seriez suceptible d'introduire dans ce document.
