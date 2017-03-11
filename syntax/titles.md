# Titles

Quand nous commençons la rédaction d'un document en markdown, nous avons besoin d'ajouter titre et sous-titres.
As we started writing a markdown document, we need to add a title and some sub-headers.

Markdown supporte deux styles de titres, Setext et atx.
Markdown supports two styles of headers, Setext and atx.

Le style des titres Setext sont "soulignés" via l'utilisation de signe égal (pour le premier niveau de titre) et de tirets (pour le second niveau). Par exemple:
Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). For example:

```
This is an H1
=============

This is an H2
-------------
```

Peu importe le nombre d'éléments = ou - soulignant, ça marchera.
Any number of underlining =’s or -’s will work.

Le style des titres Atx utilise de 1 à 6 dièse au commencement de la ligne, correspondant au niveau du titre. Par exemple:
Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```

Eventuellement, vous pouvez "fermer" un titre atx. C'est uniquement visuel - vous pouvez l'utiliser si vous pensez que cela rend mieux. Les dièses fermant n'ont même pas besoin d'être égaux à ceux ouvrant le titre. (Le nombre de # ouvrant détermine le niveau du titre. ) :
Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Voici un quiz sur les titres markdown.
Here's a quiz about markdown titles.

Selectionne le titre valide:
Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Les titres requièrent des espaces entre le # et le texte.
> Headers need space between the hash characters and the text.

Selectionne le titre valide:
Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seul = et - sont acceptés pour souligner un titre.
> Only '=' and '-' are accepted for underlining an header.

---
