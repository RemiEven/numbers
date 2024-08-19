# Enoncé
Le but de cet exercice est d'écrire le code Java d'un convertisseur pour les nombres romains. Il se décompose en deux sous-exercices indépendants et complémentaires, correspondant aux deux sens de conversion.

Dans les deux cas, les règles de conversion sont assez simples :

On ne considère que les nombres entre 1 et 3000. Les romains utilisaient majoritairement ces nombres pour de petites quantités ou pour compter les années et n'avaient ni de nombres négatifs, ni de 0.

Les chiffres romains n'utilisent que les symboles suivants :

- I (1)
- V (5)
- X (10)
- L (50)
- C (100)
- D (500)
- M (1000).

Les unités sont traduites comme suit :

- I
- II (1+1)
- III (1+1+1)
- IV (5-1)
- V (5)
- VI (5+1)
- VII (5+1+1)
- VIII (5+1+1+1)
- IX (10-1).

Les dizaines sont traduites de manière similaire : 'X', 'XX', 'XXX', 'XL', 'L', 'LX', 'LXX', 'LXXX', 'XC'.

Même chose pour les centaines avec 'C' (100), 'D' (500), 'M' (1000).

Les nombres plus complexes s'écrivent en concaténant les conversions de leur chiffres des milliers, centaines, dizaines et unités. Par exemple, '1984' s'écrit 'M' (1000) + 'CM' (900) + 'LXXX' (80) + 'IV' (4) => 'MCMLXXXIV'.

## Nombre arabes vers nombres romains

Le premier sous-exercice est le plus facile. Il correspond à la conversion des nombres arabes (comme '1', '42' ou '1984') vers les nombres romains ('I', 'XLII' ou 'MCMLXXXIV').

Il n'y a qu'une seule méthode à implémenter, `ArabicToRoman#convert()`. L'objectif est de faire passer les tests contenus dans ArabicToRomanTest.java.

## Nombre romains vers nombres arabes

Le deuxième sous-exercice est plus compliqué. Il correspond à l'autre sens de conversion, des nombres romains vers les nombres arabes.

Il n'y a qu'une seule méthode à implémenter, `RomanToArabaic#convert()`.
