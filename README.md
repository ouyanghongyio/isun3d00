Basic use of md syntax

## README.md

”-“  The minus sign effect adds a dot in front of the text, as shown below

## README.md
- en [English](README.md)
- zh [Chinese](README_ZHCN.md)

Blank line wrap

“##” The symbol represents the second-level title, and the font size decreases step by step.
## Preface
“``” Symbols (tabs) can be highlighted, similar to the following effect

`ligangxiaodian` It is a static navigation website based on html and css.
It only has basic display functions and does not have dynamic configuration functions.

”```“  The text included in the two lines above and below the three indicators will all be highlighted, which is the effect of highlighting the entire code block.

```
Code quick highlighting
```
## Project online address

“**” or “__”  Include text bold before and after

**Project online demonstration address**

__Project demonstration__

"[]" + ” () “，Front description, following jump address, hyperlink syntax

[Project portal](https://ouyanghongyio.github.io/ligangxiaodian/)

”*“ or ”_“  Include text italics before and after

*background*

”~~“ includes text before and after showing strikethrough

~~In the early stage, you need a convenient page to attract traffic, but it is actually not important.~~

_Purpose_

"<u>" and </u> Include text underline before and after

<u>Promote traffic and focus on online store sales</u>

”sup“ and ”/sup“  Add <> before and after including text superscripts

Use technology<sup>html,css</sup>

"sub" and "/sub"  Add <> before and after including text subscripts.

Functions <sub>Shop display, product display, course display</sub>

"|" A few rows will generate a table with several columns. The similar effect is as follows. If there are several columns, the second row needs to be divided into as many columns as the first row using "|" and "---"

“img src="url""” Add <> before and after to display the image, the effect is as follows

| index                                                                | store                                                                | goods                                                                | courses                                                              
|----------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|
| <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> | <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> | <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> | <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> 
| second line1                                                                 | second line2                                                                 | second line3                                                                 | second line4                                                                 |

##Project structure

“|” and “-” A tree structure diagram with the following effect can be obtained

📂  Folder icon

📄  File icon

Used together, the project structure can be displayed more intuitively.

```agsl
📂ligangxiaodian
|-📂docs
|   |-📄index.html
|   |-laba.npg
|   |-📄store.html
|-📂idea
|-📄README.md
|-📄README_ZHCN.md

```

"!" plus "[]" plus "()" can get the effect of hyperlink image

![Speaker pictures](https://ouyanghongyio.github.io/ligangxiaodian/laba.png)





