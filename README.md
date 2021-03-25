# Dany Css Reset
> Un reset très puissant qui reset tout le css de base sur tous les navigateurs.

[![license][license-image]][license-url]

**Download**

Voir [le lien pour download](https://raw.githubusercontent.com/ddanygagnon/DanyCssReset/main/reset.css)

## Pourquoi?

J'ai besoin d'un reset pour tous mes projets. Cependant, les resets qui étaient accessible comme le [Meyer CSS Reset](https://meyerweb.com/eric/tools/css/reset/)
ne répondais pas à mes besoins. Dany Css Reset est tellement agressif, il enlève tous les styles par défault que les navigateurs utilise.
Pour moi, c'est très utilise car j'aime commencer mes projets de 0 pour créer mes propres composants comme les boutons, les tables, les liens, etc. Aussi, on reset
juste se qu'on as besoin. Par exemple, si tous les navigateurs applique un `background: vert;`, le reset va réinitialiser la propriété `background`.

## Support des navigateurs
- Chrome
- Edge
- Firefox ESR+
- Internet Explorer 10+
- Safari 8+
- Opera

## Informations de base

- Applique tous les éléments en border box
- Enlève le style par défaut sur les liens
- Enlève le border spacing défaut sur les tables
- Enlève le contenu des quotes
- Applique un `background: transparent;` sur les éléments ayant un background.
- Reset le vertical-align des éléments
- Reset le text-align
- Reset le align-items
- Enlève les borders
- Enlève le padding et le margin
- Mets la couleur de défaut à inherit
- Enlève les décorations de texte
- Applique le `font: inherit;` sur les balises ayant modifié le font.

**J'ai regardé tous les styles par défauts sur le site** [browser default styles](https://browserdefaultstyles.com/)

[license-image]: https://img.shields.io/github/license/ddanygagnon/danycssreset
[license-url]: LICENSE.md
