# Learn CSS

**HTML** just by itself is boring and bland. There's no life to it! **CSS** puts the life into it, with *✨style✨* by allowing the user to style the colors, size, and everything about **HTML**!

# Classes, IDs, and Elements

To use CSS first you need a Class, ID or Element name. 
An element name is like this: `<h1>`'s element name is `h1`. The element name is in between the `<>` symbols.
What are classes and IDs? Well, they are *attributes* you can add to HTML elements. Like this: `<h1 attribute="value">` but you can replace `attribute` with either `class` or `id`! Using ***classes*** for a lot of things is very common practice. The `"value"` however is a ***value*** for your class/ID.
Here is an example of a ***class*** in use:
```html
<h1 class="myClass"></h1>
```
Once you have applied a class on your element you can identify it in your **CSS** and alter the styling, a example is this:
```css
.myClass {
	
}
```

Here is an example of a ***ID*** in use:
```html
<h1 id="myClass"></h1>
```
Once you have applied an ID on your element you can identify it in your **CSS** and alter the styling a example is this:
```css
#myClass {
	
}
```
To use element names in **CSS** do the following:
```css
body {
	
}
```
But replace `body` with the element name.

# Linking CSS
To link your **CSS** put the following code in the `<head>`:
```html
<link rel="stylesheet" href="style.css">
```
Replace `style.css` with the name of your **CSS** file.
# The basics of coloring in CSS

Let's start with styling ✨color✨ 
> `background-color` *and* `color`

### Background Color
`background-color` is important if you want to customize the background in your website(s). In order to use `background-color` you need to apply it to a class, ID or element. We'll use the `<body>` element as an example:
```css
body {
	background-color:red;
}
```
Change `red` with a **hex**, **rgb**, or any supported [color value](https://www.w3schools.com/tags/ref_colornames.asp) .
Me using `red` gives this outcome:

![[Pasted image 20240308220537.png]]

### Color
`color` refers to the color of the *text*. In order to use `color` you need to apply it to a class, ID or element. We'll use the `<body>` element as an example:
```css
body {
	color:white;
}
```
Change `white` with a **hex**, **rgb**, or any supported [color value](https://www.w3schools.com/tags/ref_colornames.asp) .
Me using `white` gives this outcome:

![[Pasted image 20240308234458.png]]

# All about fonts in CSS

Let's discuss changing fonts using `font-family` and `font-weight`
> *[Get fonts for CSS here](https://fonts.google.com/)* (Google Fonts)

To apply a font to a piece of text or all text in said element use the following code, I'll use an element as an example:
```css
body {
	font-family:sans-serif;
}
```
There are a lot of built-in preset fonts like `sans-serif` and a lot more! [Click here to view them all](https://www.w3.org/Style/Examples/007/fonts.en.html)

### Font weight
To use `font-weight` it's super easy! Follow like this:
```css
body {
	font-weight:400;
}
```
Replace the `400` value with any number between 100 and 800 (100-800)!
The higher the value the more **boldness** the text will have.
