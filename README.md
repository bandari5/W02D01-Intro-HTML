# INTRODUCTION TO HTML


HTML is known as Hyper Text Markup Language. <br>
This is the language used to create Web pages. <br>
Using HTML, you can create a Web page with text, graphics, sound, and video. <br>
What is Static and Dynamic Webpages?

## Tags
The essence of HTML programming is tags. <br>
A tag is a keyword enclosed by angle brackets. 
```html
( Example: <I> )
``` 
  <br>
There are opening and closing tags. <br>
The affected text is between the two tags. <br>
The opening and closing tags use the same command except the closing tag contains an additional forward slash /. <br>

  
 ## Nested Tags
Whenever you have HTML tags within other HTML tags, you must close the nearest tag first
Example:
```html
<H1> <I> The Nation </I> </H1>
```
<br>

## Structure of a Webpage
All Web pages share a common structure <br>
All Web pages should contain a pair of 

```html
<HTML>, <HEAD>, <TITLE>, and <BODY> tags
```
  
  <br>
  For Example:
  
```html
<HTML>
<HEAD>
<TITLE> Example </TITLE>
</HEAD>
<BODY>
      This is where you would include the text and images on your Web page.
</BODY>
</HTML>
  ```
  <br>

## The Title Tag
Choose the title of your Web page carefully. <br>
The title of a Web page determines its ranking in certain search engines. <br>
The title will also appear on Favorite lists, History lists, and Bookmark lists to identify your page. <br>

## Text Formatting
Manipulating text in HTML can be tricky; Oftentimes, what you see is NOT what you get. <br>
For instance, special HTML tags are needed to create paragraphs, move to the next line, and create headings. <br>

## Text Formatting Tags

```html
<B> Bold Face </B>
<I> Italics </I>
<U> Underline </U>
<P> New Paragraph </P>
<BR> Next Line
  ```
  
  ## Changing the Font
The expression:

```html
<FONT FACE = “fontname”> … </FONT>
```
can be used to change the font of the enclosed text.<br>
To change the size of text use the expression: 

```html 
<FONT SIZE=n> …. </FONT>
```
where n is a number between 1 and 7.

To change the color, use:
```html 
<FONT COLOR=“red”>…. </FONT>
```
The color can also by defined using hexadecimal representation. ( Example: #ffffff ) <br>
These attributes can be combined to change the font, size, and color of the text all at once:
For example:

```html 
<FONT SIZE=4 FACE=“Courier” COLOR=“red”> …. </FONT>
```

## Headings
Web pages are typically organized into sections with headings; To create a heading use the expression 

```html 
<Hn>….</Hn>
``` 
<br>
where n is a number between 1 and 6. <br>
In this case, the 1 corresponds to the largest size heading while the 7 corresponds to the smallest size. <br>

## Aligning Text
The ALIGN attribute can be inserted in the <P> and <Hn> tags to right justify, center, or left justify the text. <br>
For example:
```html 
  <H1 ALIGN=CENTER> The New York Times </H1> 
```
  would create a centered heading of the largest size. <br>
  
  
 ## Comment Statements
Comment statements are notes in the HTML code that explain the important features of the code. <br>
The comments do not appear on the Web page itself but are a useful reference to the author of the page and other programmers. <br>
To create a comment statement use the 
```html 
<!-- …. --> 
```
<br>
tags




