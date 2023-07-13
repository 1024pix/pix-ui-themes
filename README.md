# Pix-UI-Themes

Pix-UI-Themes est un ensemble de thèmes css. Il en existe deux :
- le thème par défaut (pix-theme-default)
- le thème Pix1D (pix-theme-pluto)

Il est utilisable par la librairie de composants [Pix-UI](https://github.com/1024pix/pix-ui)(https://github.com/1024pix/pix-ui/pull/436).
Le thème par défaut est le thème parent. Il est surchargeable par les thèmes enfants.

## Installation du package npm @1024pix/pix-ui-themes
Pour utiliser le style sur une application Ember externe, il faut installer le package npm pix-ui-themes avec la commande :

```npm install @1024pix/pix-ui-themes@<tag_souhaité>```

Quel tag choisir ?
`<tag_souhaité>` doit correspondre au numéro de version à installer. Ce numéro de version correspond à une release. Par exemple, on peut remplacer `<tag_souhaité>` par `v0.1.1`.

### Installation par défaut
Il est possible d'installer Pix UI Themes sans `#<tag_souhaité>`, auquel cas ce sera la dernière version qui sera installée.

## Développement de Pix-UI-Themes
```
git clone git@github.com:1024pix/pix-ui-themes.git
cd pix-ui-themes
npm install
```

Les design-tokens sont créés via des variables css.

### Lancement de storybook en local
Pour visualiser les composants créés, il faut lancer storybook :

`npm run storybook`

On peut alors changer de thèmes pour visualiser les différents designs.

<img src="/Users/clarisse.damon/Downloads/Capture d’écran 2023-07-13 à 15.00.09.png" width="350"/>

## Déploiement et versioning

Pour créer le package npm, il faut :
- Modifier la version dans le `package.json` selon la norme Semver
- Faire un `npm run build` puis un `npm run publish`
