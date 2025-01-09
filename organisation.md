# Organisation d'un challenge

Prenons un exemple tout simple : créer une fonction qui vérifie si un nombre est pair ou impair. Voyons comment l'organiser en trois temps.

## Premier temps : La réflexion globale

Commençons par écrire en langage naturel ce que nous voulons faire :
```
# 1. Recevoir un nombre
# 2. Vérifier s'il est divisible par 2
# 3. Donner la réponse "pair" ou "impair"
```

C'est simple, mais cette étape nous permet déjà de visualiser les trois moments clés de notre fonction.

## Deuxième temps : Le pseudo-code

Maintenant, transformons ces étapes en instructions plus détaillées :
```
DÉBUT
    prendre un nombre en entrée
    
    si le reste de la division par 2 est zéro
        dire que le nombre est pair
    sinon
        dire que le nombre est impair
FIN
```

Remarquez comme chaque ligne décrit une action simple et claire. Nous n'avons pas besoin de connaître la syntaxe d'un langage particulier pour comprendre ce que fait le programme.

## Troisième temps : L'implémentation

Enfin, écrivons le code dans un langage de programmation, par exemple en Python :
```python
def est_pair(nombre):
    # Si le reste de la division par 2 est 0, le nombre est pair
    if nombre % 2 == 0:
        return "pair"
    # Sinon, il est impair
    else:
        return "impair"
```

## Pourquoi cette approche est utile ?

Même pour un problème aussi simple, cette méthode nous aide à :
1. Clarifier ce que nous voulons faire avant de commencer à coder
2. Structurer notre pensée étape par étape
3. Écrire un code clair et bien commenté

C'est comme construire une maison : on commence par le plan général, puis on précise les détails, et enfin on construit. Cette approche sera encore plus précieuse quand vous aborderez des problèmes plus complexes !

N'hésitez pas à commencer par des problèmes très simples comme celui-ci. C'est en pratiquant sur des cas simples qu'on développe de bonnes habitudes pour les cas plus difficiles.
