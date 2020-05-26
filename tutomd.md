---
layout: single
title: Tutoriel Markdown
typo: oui
permalink: /tuto/
---

*Cette page vous aidera à comprendre et à utiliser le Markdown, langage de balisage utilisé pour écrire et publier les textes sur INTERNET EXPLOREUR.*

## Markdown, c'est quoi ?

Comme évoqué dans l'introduction, [Markdown](https://www.markdownguide.org/getting-started/) est un langage de balisage. Pour faire très simple, il permet de mettre en forme votre texte, par exemple pour des pages web, sans avoir l'impression de lire un texte technique, et ce grâce à des symboles lisibles par toutes et tous.

Il permet également d'écrire en texte brut, et donc de rendre plus lisible la mise en page de votre document lors de sa rédaction (on connaît toutes et tous ces espaces Word bizarres qu'on ne parvient pas à modifier ou à supprimer).

Les textes écrits en Markdown sont directement convertis en HTML, et leur mise en forme est définie par un fichier CSS écrits à part.

## Avec quel logiciel écrire en Markdown ?

Beaucoup de logiciels permettent d'écrire en Markdown. L'un d'entre eux se trouve sur tous les ordinateurs : le bloc-notes. D'autres logiciels, appelés éditeurs de texte, comme [Atom](https://atom.io/), [Sublime Text](https://www.sublimetext.com/) ou [Notepad++](https://notepad-plus-plus.org/), offrent des fonctionnalités plus avancées (codes couleur, mise en forme immédiate, etc). Enfin, des logiciels prévus spécifiquement pour rédiger en Markdown, comme [iA Writer](https://ia.net/writer), [Typora](https://typora.io/) ou [Dillinger](https://dillinger.io/), sont les plus intuitifs, car ils offrent une interface sur mesure et une prévisualisation en direct de vos brouillons.

**Attention** : pour rédiger en Markdown, il ne faut jamais utiliser de logiciels de traitement de texte comme Word, Libre Office ou Pages. En effet, ces logiciels ne vous permettent pas d'écrire de textes en brut. Ce que vous voyez sur votre page Word est déjà le résultat d'un langage brut mis en forme avec tout un ensemble de balises.

## Préparer son fichier Markdown

Avant de commencer à écrire dans votre fichier, il faut préciser son format, et son en-tête. 

Le format est `.md` ou `.markdown` (les deux fonctionnent). Un fichier type s'appelle donc : `mon-article.md`. Sur INTERNET EXPLOREUR, nous nommons tous nos fichiers sur le même type : `annee–mois–jour-mon-article.md` ; donc, par exemple : `2020-05-30-un-super-texte.md`.

L'en-tête reprend les informations nécessaires pour connaître le titre de votre texte, sa date, sa catégorie et sa mise en page. L'en-tête est délimité par deux lignes, symbolisées par trois tirets. Un en-tête type sur INTERNET EXPLOREUR est donc (les mentions entre parenthèses ne sont pas à écrire dans votre document) :

> `---`  
> `layout: post`  
> `title: "Votre Titre"`  
> `date: 2020-05-29 (la date du jour)`  
> `categories: Nom-Prenom (sans accent)`  
> `---`

Et voilà, une fois le nom de votre fichier indiqué, et cet en-tête intégré au début de votre document, vous pouvez commencer à rédiger.

## Rédiger en Markdown

Pour rédiger en Markdown, c'est très simple. Il vous suffit de taper votre texte comme à votre habitude, puis de le mettre en forme grâce à diverses balises. Toutes les balises, des plus simples aux plus compliquées, sont listées [sur ce site de référence](https://www.markdownguide.org/basic-syntax/).

Pour ne pas vous assommer avec des dizaines de balises inutiles, voici les principales qui pourront vous être utiles sur INTERNET EXPLOREUR, et qui sont déjà intégrées dans notre mise en page.

Titre : écrire deux `##` avant votre titre.  
Exemple : `## Mon titre` 

Italique : encadrer votre texte avec `*`.  
Exemple : `*mon texte à mettre en italique*`

Gras : encadrer votre texte avec `**`.  
Exemple : `**mon texte à mettre en gras**`

Retourner à la ligne : faire suivre votre ligne de deux espaces, puis appuyer sur Entrée.

Citation : précéder vos lignes du symbole `>`.  
Exemple : `> le texte à citer`

Lien : `[ceci est mon lien](https://monlien.com/).`

Note de bas de page : `La phrase que je souhaite annoter[^1].  
[^1]: Ma note de bas de page.`

Séparateur : faire se suivre trois astérisques ainsi : `***`.

Paragraphes : inutile de passer plus d'une ligne entre deux paragraphes, car Markdown ne les reconnaît pas.

Et voilà pour les balises principales.

## Besoin d'aide ?

Si jamais vous éprouvez des difficultés à rédiger en Markdown, et que cela vous semble trop difficile, ne vous inquiétez pas, nous nous chargerons de le faire nous-mêmes de notre côté à partir de votre fichier texte habituel.

Si vous avez une question précise à propos de ce tutoriel, écrivez-nous à <mail@internetexploreur.com>, et on tachera de vous aider du mieux possible pour résoudre votre problème.

N'oubliez pas que, comme tout langage, le Markdown demande un temps d'apprentissage et d'adaptation. Mais apprendre ce langage, simple au demeurant, pourra sans doute vous aider plus tard autant dans vos projets de site internet personnels, que dans la rédaction de documents associatifs ou universitaires à mettre en ligne et à partager.
