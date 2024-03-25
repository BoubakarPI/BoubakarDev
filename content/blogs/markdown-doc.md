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

## Utilisation de Selenium Driver

Selenium WebDriver est un outil populaire utilisé dans le développement d'applications web pour automatiser les tests sur différents navigateurs. Il permet de contrôler le navigateur et d'effectuer des opérations sur les éléments HTML tels que cliquer, remplir des champs de formulaire, etc. [[3]](https://www.digitalocean.com/community/tutorials/selenium-webdriver)

### Installation de Selenium WebDriver

Pour commencer à utiliser Selenium WebDriver, vous devez d'abord installer les pilotes spécifiques au navigateur que vous souhaitez utiliser. Par exemple, si vous souhaitez exécuter vos tests dans le navigateur Chrome, vous devez installer le pilote ChromeDriver. De même, pour Firefox, vous devez installer le pilote GeckoDriver. Ces pilotes permettent à Selenium WebDriver de communiquer avec les navigateurs. [[2]](https://www.selenium.dev/documentation/)

### Exemple de code en Java

Voici un exemple de code en Java utilisant Selenium WebDriver pour ouvrir le site web de Selenium et ensuite fermer le navigateur :

```java
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class HelloSelenium {
    public static void main(String[] args) {
        WebDriver driver = new ChromeDriver();

        driver.get("https://selenium.dev");

        driver.quit();
    }
}
```
[[2]](https://www.selenium.dev/documentation/)

### Exemple de code en Python

Voici un exemple de code en Python utilisant Selenium WebDriver pour ouvrir le site web de Selenium et ensuite fermer le navigateur :

```python
from selenium import webdriver

driver = webdriver.Chrome()
driver.get("https://selenium.dev")
driver.quit()
```
[[2]](https://www.selenium.dev/documentation/)

### Exemple de code en C#

Voici un exemple de code en C# utilisant Selenium WebDriver pour ouvrir le site web de Selenium et ensuite fermer le navigateur :

```csharp
using OpenQA.Selenium.Chrome;

namespace SeleniumDocs.Hello
{
    public static class HelloSelenium
    {
        public static void Main()
        {
            var driver = new ChromeDriver();
            driver.Navigate().GoToUrl("https://selenium.dev");
            driver.Quit();
        }
    }
}
```
[[2]](https://www.selenium.dev/documentation/)

### Exemple de code en Ruby

Voici un exemple de code en Ruby utilisant Selenium WebDriver pour ouvrir le site web de Selenium et ensuite fermer le navigateur :

```ruby
require 'selenium-webdriver'

driver = Selenium::WebDriver.for :chrome
driver.get 'https://selenium.dev'
driver.quit
```
[[2]](https://www.selenium.dev/documentation/)

### Exemple de code en JavaScript

Voici un exemple de code en JavaScript utilisant Selenium WebDriver pour ouvrir le site web de Selenium et ensuite fermer le navigateur :

```javascript
const {Builder, Browser} = require('selenium-webdriver');

(async function helloSelenium() {
    let driver = await new Builder().forBrowser(Browser.CHROME).build();
    await driver.get('https://selenium.dev');
    await driver.quit();
})();
```
[[2]](https://www.selenium.dev/documentation/)

### Exemple de code en Kotlin

Voici un exemple de code en Kotlin utilisant Selenium WebDriver pour ouvrir le site web de Selenium et ensuite fermer le navigateur :

```kotlin
package dev.selenium.hello

import org.openqa.selenium.chrome.ChromeDriver

fun main() {
    val driver = ChromeDriver()
    driver.get("https://selenium.dev")
    driver.quit()
}
```
[[2]](https://www.selenium.dev/documentation/)

## Conclusion

Selenium WebDriver est un outil puissant pour automatiser les tests sur différents navigateurs. En utilisant les pilotes spécifiques au navigateur et en écrivant du code avec les langages de programmation pris en charge, vous pouvez contrôler le navigateur et effectuer des opérations sur les éléments HTML. Cela facilite le processus de test des applications web sur différentes plates-formes et navigateurs.

## Sources
1. [WebDriver | Selenium](https://www.selenium.dev/documentation/en/webdriver/)
2. [The Selenium Browser Automation Project | Selenium](https://www.selenium.dev/documentation/en/)
3. [Selenium WebDriver | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-use-selenium-with-python-and-3-7)

---
Learn more:
1. [WebDriver | Selenium](https://www.selenium.dev/documentation/webdriver/)
2. [The Selenium Browser Automation Project | Selenium](https://www.selenium.dev/documentation/)
3. [Selenium WebDriver | DigitalOcean](https://www.digitalocean.com/community/tutorials/selenium-webdriver)
## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Bloc de citation

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
