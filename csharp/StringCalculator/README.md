# StringCalculator Kata

## Objectif

Le but de ce Kata est de créer une "calculatrice" qui accepte une chaîne de caractère en entrée.

Dans cet exercice, on veut pratiquer le TDD (Test-Driven Development) ainsi que l'utilisation des tests unitaires.

## Requis

1. Créer une classe *Calculatrice* qui contient une fonction *Ajouter*.
  - cette fonction doit accepter un paramêtre de type chaîne de caractère.
  - Si on passe une chaîne vide, la fonctoin retourne zéro (0).
  - Si on reçoit un seul nombre, il faut retourner ce nombre, sinon on retourne 0.  
1. Le paramêtre doit accepter plusieurs arguments délimités par une virgule.
1. On devrait pouvoir séparer les nombres par un retour de chariot (newline).
1. La fonction doit être modifiée afin de pouvoir spécifier quel est le caractère délimiteur.
1. Si un des nombres est négatif, il faut lever une exception "Les nombres négatifs ne sont pas permis.".
1. La liste des nombres rejetés doit être incluse dans l'exception.
