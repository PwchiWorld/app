# Markdown 

Some of the stuff you'll probably want to use.


<p align="right"><b>[*]</b> <a href="https://github.com/PwchiWorld/app/blob/main/docs/emoji_v5.md">Emoji GitHub</a></p>

# Table of Contents

* [Headings](#headings)
* [Alternate Headings](#alternate-headings)
* [Paragraphs](#paragraphs)
* [Line Breaks](#line-breaks)
* [Emphasis](#emphasis)
* [Inline Code](#inline-code)
* [Code Block](#code-block)
* [Code Block with Syntax Highlighting](#code-block-with-syntax-highlighting)
* [Blockquotes](#blockquotes)
* [Ordered Lists](#ordered-lists)
* [Unordered Lists](#unordered-lists)
* [Task Lists](#task-lists)
* [Horizontal Line](#horizontal-line)
* [URLs and Email Addresses](#urls-and-email-addresses)
* [Links](#links)
* [Images](#images)
* [Subscript and Superscript](#subscript-and-superscript)
* [Tables](#tables)
* [Emojis](#emojis)
* [HTML](#html)
* [Comments](#comments)
* [Banner](#banner)
* [Align](#align)
* [User Card](#usercard)


## Headings
Similar to HTML, there are 6 headings in Markdown:

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

Try to use heading level 1 for the title of your document, h2 for the sections, h3 for subsections, and so on.

## Alternate Headings
There is an alternate way of creating headings that only supports two levels:

```markdown
Heading Level 1
===============

Heading Level 2
---------------
```

## Paragraphs
Paragraphs are chunks of text separated by at least a blank line:

```markdown
This is paragraph 1.

This is paragraph 2.
```

## Line Breaks
Line break is less know to the Markdown world.  
It is achieved by adding at least two spaces to the end of the line:

```markdown
This is line 1.  
This is line 2.
```

It's less known, because it's invisible. But, try it out.

## Emphasis

There are three ways to emphasize:
- Bold
- Italic
- Bold and italic

Making bold can be done by double underscores or double asterisks:

```markdown
This is __bold__, so is **this**.
```

But inside a word, only the asterisks work:

```markdown
**Thi**s **i**s a **GitH**ub-**flavor**ed **Markdo**wn **cheatshe**et **focusi**ng **o**n **les**s-**kno**wn **featur**es.
```

To make italic, use one underscore or one asterisk, and again, inside a middle only the asterisk syntax works:

```markdown
This is _italic_, so is *this*. And it's not *un*important.
```

And to make something bold and italic, one can mix the two syntaxes:

```markdown
All of these are: ***bandi***, _**bandi**_, **_bandi_**, __*bandi*__, *__bandi__*, ___bandi___.
And inside the word: b***and***i which means bold***and***italic.
```

## Inline Code

To write code in monospace font inside a regular text, enclose it in backticks:

```markdown
This is `code` inside text.
```

If you want to write a code that has backticks in it, you can use double-backticks:

```markdown
This is the syntax: ``This is `code` inside a text.``
```

## Code Block

To create a code block, put four lines or a tab before it:

```markdown
This is the code:

    for i in range(10):
        pass
```

The alternative syntax is wrapping the code in three backticks.

````markdown
This is the code:

```
for i in range(10):
    pass
```
````

To display triple backticks in a code block, wrap them inside quadruple backticks.

````markdown
The alternative syntax is wrapping the code in three backticks.

``‌``
This is the code:

```
for i in range(10):
    pass
```
``‌``
````

To display triple and quadruple backticks inside a code block, wrap them inside quadruple backticks and put a [zero-width non-joiner](https://unicode-explorer.com/c/200C) inside the quadruple backticks you want to display.

## Code Block with Syntax Highlighting

To create a code block with syntax highlighting, you can use the three backtick syntax and write the language name in front of it:

```markdown
This is the code:

`‌`‌`python
for i in range(10):
    pass
`‌`‌`
```

As of now, some 583 languages are being supported for syntax highlighting. You can access the full list [here](https://github.com/github/linguist/blob/master/vendor/README.md).

## Blockquotes

Blockquotes are designated by a `>` in front of them:

```markdown
> Veniet tempus quo ista quae nunc latent in lucem dies extrahat et longioris aevi diligentia.
```

Use double `>` to create nested blockquotes.

> Georg Cantor quoted:
>
>> Veniet tempus quo ista quae nunc latent in lucem dies extrahat et longioris aevi diligentia.

## Ordered Lists

To create an ordered list:

```markdown
1. First item
2. Second item
3. Third item
```

The number can be out of order:
```markdown
1. First item (indexed 1)
1. Second item (indexed 1)
5. Third item (indexed 5)
```

Markdown still fixes the counters and outputs the correct numbers:

1. First item (indexed 1)
1. Second item (indexed 1)
5. Third item (indexed 5)

## Unordered Lists

To create unordered lists, use any of the following "bullet characters": hyphen `-`, asterisk `*`, or plus sign `+`:

```markdown
- Item
- Another item
- Yet another item
```

One can mix the bullet characters in one list, but it's a bad practice.

## Task Lists

A task list (aka _checklist_ or _todo list_) is an unordered list with each item having a checkbox in front, either checked or unchecked. Tasks lists are very useful when writing issues on GitHub, as one can then check or uncheck them without manually editing the Markdown source of the comment or description.

```markdown
- [x] Write the tests
- [ ] Implement the functions
- [ ] Fix the code formatting
```

Output:

- [x] Write the tests
- [ ] Implement the functions
- [ ] Fix the code formatting


## Horizontal Line

To create a horizontal line, use three or more asterisks (`***`), hyphens (`---`), or underscores (`___`):

```markdown
Some text!

---

Next chapter or something!
```

## URLs and Email Addresses

To turn URLs and email addresses into links, just wrap them into angle brackets:

```markdown
Take a look at my Medium posts: <https://aerabi.medium.com>
You can also email me at <dascent@protonmail.com>
```

## Links

To create a link, enclose the linked text in brackets and then immediately the URL in parentheses:

```markdown
Take a look at main app [Pwchi Generator](https://pwchiworld.github.io/app/).
```

You can also add a title to the link that shows as a tooltip:

```markdown
Take a look at main app [Pwchi Generator](https://pwchiworld.github.io/app/ "A World Full Of Pwchies!").
```

Take a look at main app [Pwchi Generator](https://pwchiworld.github.io/app/ "A World Full Of Pwchies!").

## Images

Image syntax is similar to that of links, only it has an exclamation mark in front and the text is the alt text:

```markdown
![ZA's GitHub avatar](https://avatars.githubusercontent.com/u/116814275?v=4)
```
**Render**

![ZA's GitHub avatar](https://avatars.githubusercontent.com/u/116814275?v=4)

## Subscript and Superscript

One might want to write about H<sub>2</sub>O or Batman<sup>TM</sup>.

```markdown
One might want to write about H<sub>2</sub>O or Batman<sup>TM</sup>.
```

## Mathematics

Onث can write LaTeX-style mathematical formulae in GitHub-flavored Markdown now:

```markdown
I know why $e^{i\pi} + 1 = 0$. And I also know that:

$$ \frac{G}{\mathrm{Ker}(\phi)} \cong \mathrm{Im}(\phi). $$
```

I know why $e^{i\pi} + 1 = 0$. And I also know that:

$$ \frac{G}{\mathrm{Ker}(\phi)} \cong \mathrm{Im}(\phi). $$

## Tables

Tables are cool:

```markdown
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

## Emojis

Emojis can be written by using colons, hurray! :tada:

```markdown
Emojis can be written by using colons, hurray! :tada:
```

[Emoji.md](https://github.com/PwchiWorld/app/blob/main/docs/emoji_v5.md) has the GitHub shortcodes for emojis, e.g. :beach_umbrella: Emojipedia - [Beach with Umbrella](https://emojipedia.org/beach-with-umbrella/).

## HTML

One can use <b>HTML</b> tags in Markdown as well.

```markdown
One can use <b>HTML</b> tags in Markdown as well.
```

## Comments

To hide contents in a Markdown document, one can use the HTML comment syntax:

```markdown
<!-- This is comment and won't be rendered! -->
```

<!-- This is comment and won't be rendered! -->

## Banner

**Markdown**

```
[![PwchiWorld](https://avatars.githubusercontent.com/u/116814275?s=48&v=4)](https://pwchiworld.github.io/app/)
```

**HTML**
```
<a href="https://pwchiworld.github.io/app/" title="ZentasticArts User"><img src="https://avatars.githubusercontent.com/u/116814275?s=48&v=4" alt="ZentasticArts User"></a>
```

**Render**

[![PwchiWorld](https://avatars.githubusercontent.com/u/116814275?s=48&v=4)](https://pwchiworld.github.io/app/)



## Align
Blocks and elements can be aligned (a bit).

**Example**

```<p align="left">This text is aligned to the <b>left</b></p>```

**Render align left**

<p align="left">This text is aligned to the <b>left</b></p>

![hr](https://raw.githubusercontent.com/PwchiWorld/app/main/assets/img/hr.png)

```<p align="right">This text is aligned to the <b>right</b></p>```

**Render align right**

<p align="right">This text is aligned to the <b>right</b></p>

![hr](https://raw.githubusercontent.com/PwchiWorld/app/main/assets/img/hr.png)

```<p align="center">This text is aligned to <b>center/b></p>```

**Render align center**

<p align="center">This text is aligned to the <b>center</b></p>



Combinations can be used like one image element aligned to left and text element to right



![hr](https://raw.githubusercontent.com/PwchiWorld/app/main/assets/img/hr.png)


## User Card
The new trend in markdown use is to have a *magic* usercard ... a niceley `readme.md` file with cool content. 

Have no idea what I'm talking about?

This is an example:

**Markdown**
```
<table>
  <tbody>
    <tr>
      <td align="center">
	  <h3>Hello World</h3>
	  </td>
	  </tr>
    <tr>
      <td align="center">
<div id="aboutme" align="left">
  <a href="https://zentasticarts.ro/profilul-meu/?uid=Dan"><img src="https://raw.githubusercontent.com/Dascent/zaro/main/dan.jpg" width="200" align="left"></a>
  <p><em>Well, I'm multipurpose so I have lots of projects where I enjoy my time.</em><br>
    <em>Due to diversity (I love), my passions are oscilating between making money and making a difference</em><br>
    <em>Cofounder (mostley web designer) at CGC and CEO at <a href="https://zentasticarts.ro/profilul-meu/?uid=Dan">ZentasticArts</a></em></p>
  <p></p>
  <p></p>
  <p></p>
  <p><img src="https://raw.githubusercontent.com/PwchiWorld/app/main/assets/img/hr.png" width="100%"/></p>
  <p align="right">Pseudonim: DAscent</p>
</div>
</td>
</tr>
<tr>
<td align="center">
<div id="badges" align="right">
  <a href="https://www.facebook.com/Dan.ZentasticArts"><img src="https://img.shields.io/badge/Facebook-blue?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook Badge"/></a>
  <a href="https://www.youtube.com/channel/UCRLu-JwrS5GOF15ZCVpUJTQ"><img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/></a>
  <a href="https://twitter.com/DanNita_za"><img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/></a>
  <a href="https://www.tiktok.com/@dascent33"><img src="https://img.shields.io/badge/TikTok-black?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok Badge"/></a>
   <a href="https://www.instagram.com/dan.zentasticarts/"><img src="https://img.shields.io/badge/Instagram-purple?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/></a>
</div>
</td>
</tr>
  </tbody>
</table>

```

**Rendering**

<table>
  <tbody>
    <tr>
      <td align="center">
	  <h3>Hello World</h3>
	  </td>
	  </tr>
    <tr>
      <td align="center">
<div id="aboutme" align="left">
  <a href="https://zentasticarts.ro/profilul-meu/?uid=Dan"><img src="https://raw.githubusercontent.com/Dascent/zaro/main/dan.jpg" width="200" align="left"></a>
  <p><em>Well, I'm multipurpose so I have lots of projects where I enjoy my time.</em><br>
    <em>Due to diversity (I love), my passions are oscilating between making money and making a difference</em><br>
    <em>Cofounder (mostley web designer) at CGC and CEO at <a href="https://zentasticarts.ro/profilul-meu/?uid=Dan">ZentasticArts</a></em></p>
  <p></p>
  <p></p>
  <p></p>
  <p><img src="https://raw.githubusercontent.com/PwchiWorld/app/main/assets/img/hr.png" width="100%"/></p>
  <p align="right">Pseudonim: DAscent</p>
</div>
</td>
</tr>
<tr>
<td align="center">
<div id="badges" align="right">
  <a href="https://www.facebook.com/Dan.ZentasticArts"><img src="https://img.shields.io/badge/Facebook-blue?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook Badge"/></a>
  <a href="https://www.youtube.com/channel/UCRLu-JwrS5GOF15ZCVpUJTQ"><img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/></a>
  <a href="https://twitter.com/DanNita_za"><img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/></a>
  <a href="https://www.tiktok.com/@dascent33"><img src="https://img.shields.io/badge/TikTok-black?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok Badge"/></a>
   <a href="https://www.instagram.com/dan.zentasticarts/"><img src="https://img.shields.io/badge/Instagram-purple?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/></a>
</div>
</td>
</tr>
  </tbody>
</table>


