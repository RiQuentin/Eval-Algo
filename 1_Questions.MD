Quentin Richefeu DMMW

# QUESTIONS

## Définissez ce qu'est une variable

Une variable est une donnée que nous allons manipuler en programation (attribuer et modifier sa valeur).

 let monAge = 34;

 monAge est la variable ici et elle prend comme valeur 34

## Quels sont les trois types principaux de variables

Les trois types de variables sont :
Les nombres : entier(int), à virgule (float)
les booléen : Vrai(true) ou faut (false)
les chaines de caractéres : une plusieurs lettres (string)

## Combien de valeurs différentes peut prendre une variable de type booléen ?

Cette variable peut prendre deux valeurs différentes vrai(true), ou faut (false)

## Que se passe-t-il si l'on execute le code suivant ? Comment cela s'appelle-t-il ?

```
let debut = 0;

while (debut > 0) {
    console.log("Je continue");
    debut += 1;
}

console.log("J'arrête");
```

Nous allons effectuer un tour de boucle (debut est à 0 avant la boucle et 1 aprés).

## Si je veux stocker une suite d'éléments dans une variable, que dois-je utiliser ?

Nous allons utiliser un tableau pour stocker ces éléments, il est possible d'utiliser un objet litteral javascript pour stocker des elements plus complexe

## Qu'est ce que les paramètres d'une fonction ? Qu'est ce que le retour (return) d'une fonction ?

Les paramètres d'une fonction ou argument sont les variables que nous allons donnée à celle-ci pour qu'elle puisse les traité. le retour de la fonction est la variable qui va etre retourné par la fonction c'est-à-dire que c'est le resultat du traitement de la fonction.

exemple:
 fonction (parametre1,parametre2)   // passage de parametre
{
    return (parametre1 + parametre2)  // le retour à l'interieur de la fonction aprés un traitement ici une simple adittion
}
let retour = fonction (1,2)   // ici dans la variable retour on reçois la retour de la fonction (1+2 soit 3)
 