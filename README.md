# projet-angular-2026

## Identification

L'application n'est accessible uniquement après s'être identifié. La gestion du user se fait via une sauvegarde dans le LocalStorage. Pour se connecter, l'utilisateur devra renseigner un login et un mot de passe identique qui devront contenir 5 caractères minimum, 1 chiffre et un 1 caractère spécial parmis ceux là ./*-+

Depuis n'importe quelle page, vous devez fournir à l'utilisateur la possibilité de se déconnecter.

## Fonctionnalités attendues

Votre application web doit se composer des éléments suivantes :
- une page d'accueil qui liste les 5 dernières recettes. On affichera uniquement le nom et les 15 premiers caractères de la description.
- une page listant toutes les recettes via une pagination. Une recherche via le nom d'une recette doit être possible.
- une page permettant la création de recette

Chaque page doit être accessible via une URL différente et le TITLE (ce qui s'affiche sur l'onglet du navigateur) doit se mettre à jour.

## Modèle de données

Afin qu'une recette soit valide, elle doit avoir obligatoirement 1 nom, avoir 1 description de 30 caractères minimum et être composé de minimum 2 quantité d'ingrédients.

## API

- API recettes : https://6ab976bcf84897980b729a5b.mockapi.io/recipies
- API ingrédients : https://6ab976bcf84897980b729a5b.mockapi.io/ingredients

Les fonctionnalités de tri et de filtre sont accessibles via la documentation de l'API : [https://github.com/mockapi-io/docs/wiki/Code-examples#sorting](https://github.com/mockapi-io/docs/wiki/Code-examples)

## Rendu graphique

L'intégration d'une bibliothèque CSS, de votre choix, est obligatoire.

## Rendu

Le projet, par groupe de 2, doit être rendu pour le dimanche 18 octobre 2026 à 23h59.
