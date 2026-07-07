# Osuny

[Documentation officielle sur developers.osuny.org](https://developers.osuny.org/docs/website/)

This project is tested with BrowserStack.

## Navigation entre les projets à vendre

Lorsque l'on est dans la page d'un piano (projet) vendu, il faut restreindre la navigation aux autres pianos à vendre uniquement.
Pour cela, on ajoute à la catégorie de projet "à vendre" la class `scoped-siblings-navigation`.
On ajoute aussi deux clefs de traductions "piano à vendre précédent/suivant".
