# HTML
- HTML is termed as Hyper Text Markup Language.
- HTML is used for creatig web pages.
- HTML is a markup language which is being used for creating a structure of a web page.

```<!DOCTYPE html>``` is used at top of the HTML document to notify the browser that existing webpage is a HTML5 document.
```<html lang="en">``` is used to start the HTML document, lang attribute is used to inform that content of the webpages is in English. ```</html>``` is used to notify that HTML document has ended. All content of the webpage is written between them. HTML document has two separate element for different purposes.

- ```<head></head>``` is used to provide information or to link other files for the browser and search engine.
- ```<body></body>``` is used to create webpage structure which is visible to the user.

- ```<meta charset="UTF-8">``` is used for defining character encoding to the browser. 

- ```<meta name="viewport" content="width=device-width, initial-scale=1.0">``` is used for making website responsive.

- ```<title></title>``` is used for providing title to HTML document.

## HTML Elements  

It is defined by a start tag, some content, and an end tag.
```<tagname>content</tagname>``` 

HTML elements can be nested (this means that element can have other elements).

**NOTE**: Never  miss the end tag otherwise it will distort the structure of the webpages. HTML tags are not case-sensitive.

## ATTRIBUTES

Attributes are used for providing additional information about HTML elements. All HTML elements can have attributes. Attributes are always defined in start tag. It consists of name-value pair. e.g. name="value".

### HEADINGS

HTML headings are titles or subtitles that we want to display on a webpage. HTML headings are defined with ```<h1>``` to ```<h6>``` tags.

### PARAGRAPHS

A paragraph always starts on a new line, and is usually a block of text. Paragraph automatically removes extra space and lines when the page is displayed.

- ```<pre></pre>``` is used for pre formatted text.

- ```<hr>``` is used for horizontal lines. It is an empty tag that's  why end tag is not required.
- ```<br>``` is used for line breaks. It is an empty tag that's  why end tag is not required.

- ```&nbsp;``` is used for adding single space in between paragraphs.
- ```&emsp;``` is used for adding tab space in between paragraphs.

### STYLES

The HTML **style** attribute is used to add style to an element, such as color, font, size and more.

### FORMATTING

HTML contains several elements for defining text with a special meaning.

- ```<b>``` : Bold Text
- ```<i>``` : Italic Text
- ```<u>``` : Underline Text
- ```<q>``` : Quotation
- ```<blockquote>``` : Block Quote
- ```<em>``` : Emphasized Text
- ```<mark>``` : Highlighted Text
- ```<small>``` : Small Text
- ```<del>``` : Deleted Text
- ```<ins>``` : Inserted Text
- ```<sub>``` : Subscript Text
- ```<sup>``` : Superscript Text
- ```<strong>``` : Important Text
- ```<abbr>``` : Abbriviation
- ```<cite>``` : Title of creative work
- ```<address>```: Address
- ```<bdo>``` : Bi-directional override

### Comments 

In HTML we write comments in between ```<!-- Comment -->```