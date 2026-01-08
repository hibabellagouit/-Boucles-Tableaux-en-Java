Voici un **fichier README** (contenu prêt à être copié dans un `README.md`) qui résume l’ensemble du travail demandé.

---

# Travaux Pratiques – Programmation (Tableaux & Boucles)

## Description générale

Ce projet regroupe une série d’exercices de programmation visant à maîtriser :

* les boucles,
* les tableaux (simples et à deux dimensions),
* les calculs numériques,
* la manipulation de matrices,
* l’optimisation en temps et en mémoire.

Les solutions respectent les contraintes imposées : utilisation exclusive de boucles et de tableaux, sans structures avancées (List, Map, Set, récursion).

---

## Exercice 1 – Somme de la série harmonique

**Objectif :**
Calculer la somme des *n* premiers termes de la série harmonique :

[
1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n}
]

**Entrée :**

* Un entier `n` saisi par l’utilisateur.

**Sortie :**

* La somme des `n` premiers termes (valeur réelle).

**Notions utilisées :**

* Boucle
* Calcul en virgule flottante

---

## Exercice 2 – Triangle isocèle d’étoiles

**Objectif :**
Afficher un triangle isocèle composé d’étoiles (`*`).

**Entrée :**

* Un entier représentant la hauteur du triangle.

**Contraintes d’affichage :**

* La dernière ligne est alignée sur le bord gauche.
* Chaque ligne contient un nombre impair d’étoiles.

**Exemple (hauteur = 4) :**

```
*
***
*****
*******
```

---

## Exercice 3 – Carrés des nombres impairs

**Objectif :**
Créer un tableau contenant les carrés des `n` premiers nombres impairs et afficher le résultat.

**Entrée :**

* Un entier `n`.

**Sortie :**

* Affichage formaté de chaque nombre impair et de son carré.

**Exemple :**

```
Combien de valeurs : 5
1 a pour carre 1
3 a pour carre 9
5 a pour carre 25
7 a pour carre 49
9 a pour carre 81
```

---

## Exercice 4 – Classe utilitaire pour tableaux 2D

**Objectif :**
Créer une classe utilitaire manipulant des tableaux de tableaux de `double`.

### Méthodes statiques implémentées :

* `affiche(double[][] t)`
  → Affiche le tableau ligne par ligne.
* `regulier(double[][] t)`
  → Vérifie si le tableau est régulier (lignes de même taille).
* `sommeLignes(double[][] t)`
  → Retourne un tableau contenant la somme de chaque ligne.
* `somme(double[][] t1, double[][] t2)`
  → Retourne la somme de deux tableaux s’ils sont compatibles, sinon `null`.

**Bonus :**

* Programme de test pour valider les méthodes.

---

## Exercice 5 – Rotation en place d’une matrice N×N

**Objectif :**
Faire pivoter une matrice carrée d’entiers de 90° dans le sens horaire **en place**, sans tableau auxiliaire.

**Contraintes :**

* `2 ≤ N ≤ 200`
* Complexité mémoire : O(1)
* Pas de récursion ni de structures avancées

**Méthode principale :**

1. Transposition de la matrice
2. Renversement de chaque ligne

**Exemple :**

Entrée :

```
4
1 2 3 4
5 6 7 8
9 10 11 12
13 14 15 16
```

Sortie :

```
13 9 5 1
14 10 6 2
15 11 7 3
16 12 8 4
```

**Bonus :**

* Rotation 90° antihoraire
* Rotation 180°

---

## Exercice 6 – Fenêtre glissante : éléments distincts

**Objectif :**
Calculer le nombre d’éléments distincts dans chaque fenêtre de taille `k` d’un tableau `T`.

**Contraintes :**

* `1 ≤ k ≤ n ≤ 100000`
* Valeurs dans `[0..100000]`
* Complexité : O(n)
* Utilisation d’un tableau de fréquences

**Principe :**

* Initialisation de la première fenêtre
* Glissement de la fenêtre avec mise à jour incrémentale

**Exemple :**

Entrée :

```
8 4
1 2 2 3 2 1 4 2
```

Sortie :

```
3 2 4 4 3
```

---

## Conclusion

Ces exercices permettent de renforcer les bases de l’algorithmique impérative :

* raisonnement par boucles,
* manipulation efficace des tableaux,
* optimisation en temps et en mémoire,
* traitement de problèmes classiques (matrices, fenêtres glissantes).

Ils constituent une base solide pour aborder des structures de données plus avancées par la suite.



