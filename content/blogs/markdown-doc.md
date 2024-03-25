---
title: "Markdown Syntax"
date: 2021-04-03T23:29:21+05:30
draft: false
github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Gurusabarish"
tags:
  - Syntaxe Markdown
  - Code
  - Hugo
image: /images/Markdown.webp
description: ""
toc:
---

## Introduction
Une brève introduction sur le **Balisage Markdown** en utilisant la syntaxe Markdown :

---

Le **Markdown Markup** est un langage de balisage léger qui simplifie la création de contenu pour le Web. Contrairement aux balises HTML complexes, le Markdown permet de formater du texte de manière simple et intuitive. Il est largement utilisé par les blogueurs, les écrivains et les développeurs pour rédiger des articles, des documents et des pages Web.

En utilisant le Markdown, vous pouvez :

- Créer des **titres** et **sous-titres** :
    Utilisez des symboles `#` pour créer des titres de différents niveaux. Par exemple :

- Mettre en forme du texte en **gras**, en **italique** ou en **souligné** :
   - Utilisez des astérisques (`*`) ou des tirets bas (`_`) pour mettre en forme le texte. Par exemple :
     - `**Texte en gras**` pour afficher du texte en gras.
     - `*Texte en italique*` pour afficher du texte en italique.
     - `__Texte souligné__` pour afficher du texte souligné.

3. Créer des **listes ordonnées** et **non ordonnées** :
   - Utilisez `-` ou `1.` suivi d'un espace pour créer des listes. Par exemple :
     - `- Élément 1`
     - `- Élément 2`
     - `1. Élément A`
     - `1. Élément B`

4. Insérer des **liens** et des **images** :
   - Pour les liens, entourez le texte du lien avec des crochets `[]` et ajoutez l'URL entre parenthèses `()`. Par exemple :
     - `[Texte du lien](https://www.example.com)`
   - Pour les images, utilisez la même syntaxe, mais ajoutez un point d'exclamation devant les crochets. Par exemple :
     - `![Texte alternatif de l'image](https://www.example.com/image.jpg)`



---

[**Lien vers l'article complet**](https://fastercapital.com/fr/contenu/Markdown-Markup---simplifier-la-creation-de-contenu-avec-le-balisage-Markdown.html)


## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use _Markdown syntax_ within a blockquote.

### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

| Name  | Age |
| ----- | --- |
| Bob   | 27  |
| Alice | 23  |

### Inline Markdown within tables

| Inline&nbsp;&nbsp;&nbsp; | Markdown&nbsp;&nbsp;&nbsp; | In&nbsp;&nbsp;&nbsp;                | Table  |
| ------------------------ | -------------------------- | ----------------------------------- | ------ |
| _italics_                | **bold**                   | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code` |

## Code Blocks

### Code block with backticks

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

### Code block indented with four spaces

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

### Code block with Hugo's internal highlight shortcode

{{< highlight html >}}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## List Types

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- List item
- Another item
- And another item

### Nested list

- Item
  1. First Sub-item
  2. Second Sub-item

## Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
