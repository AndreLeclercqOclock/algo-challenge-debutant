# Le pseudo-code sans prise de tête

Imagine que tu expliques ton algorithme à un ami. Tu n'as pas besoin d'utiliser un langage de programmation particulier, juste des mots simples qui décrivent ce que tu veux faire. C'est ça, le pseudo-code !

## Les bases pour commencer

### Comment écrire tes instructions
Écris comme tu parles ! Par exemple :
```
RÉPÉTER jusqu'à la fin du tableau
    SI le nombre actuel est plus grand que le suivant
        échanger les deux nombres
    SINON
        passer au nombre suivant
```

### Les mots que tu peux utiliser
Tu peux utiliser des mots comme :
- DÉBUT et FIN pour délimiter ton code
- SI... ALORS... SINON pour les conditions
- TANT QUE ou RÉPÉTER pour les boucles
- RETOURNER pour donner un résultat

Mais franchement, utilise les mots qui te semblent naturels. L'important est que ce soit clair pour toi !

### Un exemple concret
Imaginons que tu veuilles trouver le plus grand nombre dans une liste. Tu pourrais écrire :
```
DÉBUT
    mettre le premier nombre dans "plus_grand"
    
    pour chaque nombre de la liste
        si ce nombre est plus grand que "plus_grand"
            remplacer "plus_grand" par ce nombre
        
    donner "plus_grand" comme résultat
FIN
```

## Quelques conseils sympas

### Indente ton code
Rentre un peu le texte quand tu es "à l'intérieur" d'une condition ou d'une boucle. Ça rend ton code plus facile à lire :
```
SI il pleut
    prendre un parapluie
    mettre des bottes
SINON
    mettre des lunettes de soleil
```

### Commente ton code
Tu peux ajouter des explications avec des #. C'est super utile pour se souvenir de ce que tu voulais faire :
```
# On vérifie d'abord si le nombre est pair
SI le nombre est divisible par 2
    écrire "c'est pair !"
```

### N'hésite pas à décomposer
Si une étape est compliquée, découpe-la en plus petites étapes. C'est comme une recette de cuisine !

## Le plus important
- Écris comme ça te vient naturellement
- Pas besoin d'apprendre des mots clés par cœur
- Si quelqu'un peut comprendre ce que tu veux faire en lisant ton code, c'est gagné !

Souviens-toi : le pseudo-code, c'est juste une façon d'écrire tes idées avant de les transformer en vrai code. Pas de stress, écris simplement ce que tu veux que l'ordinateur fasse, étape par étape, comme si tu l'expliquais à quelqu'un.
