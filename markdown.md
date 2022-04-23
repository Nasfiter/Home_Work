# __What Is Markdown?__
 
* Lightweight markup language a plain text formating ayntax
* Can be converted into HTML/XHTML and other formats.
* It's main purpose is readability and easy of use.

## What Is It Used For? 
* Readme Files (Github, etc)
* Forum & Blog Posts 
* Used In Many Static Site Generators

## Some Things You Can Format 
* Headings 
* Lists
* Emphasis 
* Links 
* Blocks os Code
* Images 
* Blockquotes
* Horizontal Rules

# __Headings__ 
# Heading 1 
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5 
###### heading 6

## _Italics_
*This text* is italic

_This text_ is italic

## **Strong**
This text* is **strong**

This text* is __strong__

## __Strikethrough__

~~This text~~ is strikethrough

## __Horizontal Rule__ 

---
___

## __Blockquote__

> This is a quote

## __UL__

* Item 1 
* Item 2
* Item 3 
    * Nested item 1
    * Nested item 2

## __OL__

1. Item 1
2. Item 2
3. Item 3

## __Inline Code BLOCK__

`<p>This is a paragraph</p>`

## __Images__

![GB Logo](GB_logo.jpeg)

# Instraction for work with Markdown

## Makking the text strong 

In case to make the text ITALIC  you have to suraound it with stars (*) or with (_) 
_for example_ 

To make text **STONG** have to make it surounded by (**) or (__)

__For example__
 

## Listes 

To make lists as UL you have to put (*) or (+) at the begining.

* Item 1
* Item 2
* Item 3 
    * Item 3.1
    * Item 3.2
+ Item 4

To make lists as OL you have to put (1. 2. 3. ...) at the begining.

EXP:

1. Item 1
2. Item 2 

## Images

In case to insert needs 

![Cakes](cakes.jpeg)


## Links

to make link do next: 

[mail.ru](https://www.mail.ru)

## Tables 

Tables aren't part of the core Markdown spec, but they are part of *GFM* and *MARKDOWN*. 

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


## Quotes 

To male Blockquotes simply use this simvol (>) at the beginig of the line 

> exp of Blockquotes 

### Conclusion 

# _Pull Request instractions_ 

## Клонируем репозиторий 
git clone https://github.com/gogoleff/verstka-tasks-1.git verstka-tasks-1

### Заходим в созданную папку с клоном
cd verstka-tasks-1

### Решаем задачу в любимом редакторе...

### Добавляем все изменённые файлы через пробел
git add index.html

### Коммитим (утверждаем изменения)
git commit -m "Моё решение задачи"

### Отправляем ветку с коммитом в удалённый личный (origin) репозиторий
### (может попросить ввод логина и пароля)
git push origin master


