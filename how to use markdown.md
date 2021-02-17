---
title: How to use markdown syntax
nav_order: 1
---
Using markdown is very easy. Let's start from the very beginning: a title of the document. Create it by inserting a few characters like this: =
below the title.

This is title
=============
Here the note really starts. As you can see, using markdown is very simple. 

And here's the way you create an *italics*.
Italics in the text are created by inserting the word(s) between single asterisks, like this: 
```
*word*
```

Here we have **bold** in our introduction.
You can create bold in a very similar way - insert the word(s) between the double asterisks.
```
**word**
```

# And this is chapter 1 

The chapter title is created by inserting the # sign and a space.

## 1.1. Let's start the note

As you can see, you can create a subchapter by inserting two # characters. And what about the bullet points?

* point - * sign and a space
* point - and so on

Ordered list - it's even easier. Write a number, a dot and a space.

1. Here we continue writing
2. And again

## 1.2 Quotes and notations 

And here's a clever quote: create it using this character: 
```
>
```
For example:

> Clever quote.  

End of the quote. Let's check something else, for example the notation of mathematical operations. Take your favourite mathematical operation and place it between characters like: ``

See the example:

`x=2`

Between such characters ` you can put all the formulas, equations, etc.

## 1.3. A table - see how to do it!

To add a table into your document, use three or more hyphens: 
```
--- 
```
to create each column’s header, and use pipes (|) to separate each column. You can add pipes on either end of the table, but it's not obligatory. 


| title   | title   |
|---------|---------|
| content | content |
| content | content |


## 1.4 Table of contents

To successfully generate a table of contents, you must have the extension "Markdown All in One" installed.

That's how it looks:

- [This is title](#this-is-title)
- [And this is chapter 1](#and-this-is-chapter-1)
  - [1.1. Let's start the note](#11-lets-start-the-note)
  - [1.2 Quotes and notations](#12-quotes-and-notations)
  - [1.3. A table - see how to do it!](#13-a-table---see-how-to-do-it)
  - [1.4 Table of contents](#14-table-of-contents)
- [And last but not least... images and links!](#and-last-but-not-least-images-and-links)

If you would like to update your table of content or need any suggestions, try ctrl+space.

# And last but not least... images and links!

Adding an image from the internet works when you put it this way: 

```
![alt text](link to the image)
```
See example:

![This is a random image from the internet](https://4rooms.com.pl/userdata/public/gfx/1279cded36c5a39ffac5a8b86ffa654c.jpg)

If you'd like to add an image from your local disc, just do the same. You should provide a relative path to image file in parentheses.

See example:

![And this is an image from my computer](sowbrak.jpg)

And finally - some useful links:

[Link - documentation](https://daringfireball.net/projects/markdown/)

[Link - documentation 2](https://www.markdownguide.org/extended-syntax/)


