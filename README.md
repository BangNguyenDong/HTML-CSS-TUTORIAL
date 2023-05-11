<img src="https://camo.githubusercontent.com/63d6caa0945a67a2ad7b8c92aa099c920d16adb00032362420f6a0bdd27b08c7/68747470733a2f2f6d617274696e63686176657a2e6769746875622e696f2f4173736574732f4c6f676f732f68746d6c6373732e737667" width="600px" height="400px">
HTML+CSS Tutorial
=================

Hi, I'm Bang Nguyen. I'm a engineer and I've been teaching myself HTML, CSS, and other web development and scripting for over 5 years.
And I want to teach you now.
Because you're good looking.
And because it's useful.

### Editors

So the first thing you'll need is an editor to edit your jazz.  There's tons of options out there.

 * Notepad/TextEdit (that's right, the stupid thing that comes on your computer) - This is about as basic as you can get. It's totally okay if you want to use this, but I recommend one of the editors below just so you can see code highlighting (which will help you out later on). But, if you want to be a purist, this'll work just fine.
 * [Visual Studio Code](https://code.visualstudio.com/) - This is what I typically use. It's open source and has TONS of extensions available.
 * [Sublime Text](https://www.sublimetext.com/) - This is a pretty popular option. Very clean interface.
 * [CodePen Projects](https://codepen.io/project) - This is an in-browser code editor, so you can code directly within the web browser, no downloads required. :)
 * [Glitch](https://glitch.com/) - This is another in-browser code editor. It is meant for larger projects, but it's nice to not have to download anything!
 * [Notepad++](http://notepad-plus-plus.org/) - This is just one step up from Notepad. But it's pretty dece.  Code highlighting is in it, and nothing else too fancy, which is what I like about it.

There's a bunch of others [listed here](http://en.wikipedia.org/wiki/List_of_HTML_editors), I just listed the ones I've used and liked!

### Extension for Visual studio code
1. Code Runner
2. Live Server
3. Live Preview
4. Auto Rename Tag
5. Highlight Matching Tag
6. HTML CSS Support

###You can find html/css documentation on the following pages:
 * [HTML Tag](https://www.w3schools.com/html/default.asp)
 * [CSS Tag](https://www.w3schools.com/css/default.asp)
 * [HTML Dog Tag List](https://www.htmldog.com/references/html/tags/)
 * [Quackit HTML Tag List](https://www.quackit.com/html/tags/)
 
###LESSON1

###What is HTML?
1. HTML stands for Hyper Text Markup Language
2. HTML is the standard markup language for creating Web pages
3. HTML describes the structure of a Web page
4. HTML consists of a series of elements
5. HTML elements tell the browser how to display the content
6. HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.


### HTML Tag Structure

Here is a barebones HTML page, about as simple as you can get. You can open it up in the **1 - Structure** folder in the file part1.html. If you were to open the file in your favorite browser (which you can do, go ahead), you'll see a plain webpage with the title "My Website" and the words, "Hello, World!" written on the page. <br>

You can create this basic structure with the command !+tab or html:5 on an html page.

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<body>
	
</body>
</html>
```
<img src="https://user-images.githubusercontent.com/71707454/236367249-51ad03fa-e6e7-4cde-b6a6-bb4ac40cbf2a.png" width="600px" height="400px">

###HOW TO CREATE A WEB PAGE
To create a true HTML document you will start with three container elements:
```
<html>
<head>
<body>
```
<br>
These three combine to describe the basic structure of the page:
<br>
<html>: This element wraps all the content of the page (except the DTD) <br>
<head>: This element designates the header part of the document. You can include optional information about the Web page, such as the title (the browser shows it in the title bar), optional search keywords and an optional style sheet <br>
<body>: This element contains the content of your Web page, that is, what we want to appear in the navigation area of the browser <br>

Topics
================
 - Comment
 - Heading
 - Paragraph
 - Align
 - Hr
 - Br
 - Blockquote
 - Fonts
 - Formatting
 - Button
 - Label
 - Input
 - Select
 - Checkbox
 - Radio
 - Link
 - Image
 
###LESSON2 <br>
CSS (Cascading Style Sheets) is a formatting language used to style and decorate web pages. It is used to define properties such as color, size, spacing, font, and position of HTML elements on a web page. CSS helps separate the formatting style and content structure of a web page, allowing web designers to easily update, modify, and manage the formatting elements efficiently. CSS also allows for the creation of dynamic effects, animations, and responsive designs to be compatible with various types of devices and screens.

Ways to declare CSS in HTML

There are several ways to declare CSS in HTML, including:

1. Inline styles: Declare styles directly on HTML elements using the `style` attribute. For example:

   ```
   <h1 style="color: red;">Hello World!</h1>
   ```

2. Internal styles: Declare CSS in the `<head>` section of the HTML document using the `<style>` tags. For example:

   ```
   <head>
     <style>
       h1 {
         color: red;
       }
     </style>
   </head>
   <body>
     <h1>Hello World!</h1>
   </body>
   ```

3. External stylesheets: Declare CSS in a separate file and link it to the HTML document using the `<link>` tag. For example:

   ```
   <head>
     <link rel="stylesheet" href="style.css">
   </head>
   <body>
     <h1>Hello World!</h1>
   </body>
   ```

In the third way, the CSS file named `style.css` is stored in the same directory as the HTML document.



Each way of declaring CSS in HTML has its own advantages and disadvantages. Inline styles are easy to understand and apply quickly, but difficult to manage when there are many HTML pages. Internal styles are suitable for small websites, but not efficient when applied across multiple pages. External stylesheets allow for reuse, easy management, and modification, but require creating and linking a CSS file, which takes time and cannot be used when there is no internet connection.
	
Topic: Explanation of CSS text properties.

CSS (Cascading Style Sheets) offers a wide range of text properties that allow web designers to style and format text in various ways. Some of the most commonly used text properties include:

1. `font-family`: This property sets the font family of the text, such as Arial, Times New Roman, or a custom font.

2. `font-size`: This property sets the size of the font, which can be specified in pixels, ems, or percentages.

3. `font-weight`: This property sets the weight of the font, which can be normal, bold, or a number from 100 to 900.

4. `text-align`: This property sets the alignment of the text, such as left, right, center, or justify.

5. `text-decoration`: This property sets the decoration of the text, such as underline, overline, line-through, or none.

6. `text-transform`: This property transforms the text to uppercase, lowercase, or capitalize.

7. `line-height`: This property sets the height of each line of text.

8. `letter-spacing`: This property sets the spacing between each letter in the text.

9. `word-spacing`: This property sets the spacing between each word in the text.

10. `white-space`: This property sets how white space characters are handled in the text, such as nowrap, pre, or normal.

11. `word-break`: This property sets how words should break when they exceed the width of their container, such as break-all, break-word, or keep-all.

12. `word-wrap`: This property sets whether words should be broken at the end of a line or if the text should wrap to the next line.

13. `text-indent`: This property sets the indentation of the first line of text in a paragraph.

14. `vertical-align`: This property sets the vertical alignment of the text within its container.

These text properties can be combined and modified to achieve a wide range of formatting options for text on a web page.
	
###In CSS (Cascading Style Sheets), the `color` property is used to set the color of text and other elements on a web page. The `color` property can be set using a variety of values, including:

1. Color names: There are 147 named colors in CSS, such as "red", "blue", and "green". These can be used to specify a color without using hexadecimal or RGB values.

2. Hexadecimal values: Hexadecimal values use a combination of six letters and numbers to specify a color, such as "#FF0000" for red and "#0000FF" for blue.

3. RGB values: RGB (Red, Green, Blue) values use three numbers between 0 and 255 to specify a color, such as "rgb(255, 0, 0)" for red and "rgb(0, 0, 255)" for blue.

4. RGBA values: RGBA (Red, Green, Blue, Alpha) values are similar to RGB values, but include an additional value for opacity. The opacity value is specified as a number between 0 and 1, such as "rgba(255, 0, 0, 0.5)" for a semi-transparent red color.

5. HSL values: HSL (Hue, Saturation, Lightness) values use three values to specify a color. The Hue value is represented as an angle between 0 and 360 degrees, while Saturation and Lightness are represented as percentages between 0% and 100%. For example, "hsl(0, 100%, 50%)" represents a pure red color.

6. HSLA values: HSLA values are similar to HSL values, but include an additional value for opacity. The opacity value is specified as a number between 0 and 1, such as "hsla(0, 100%, 50%, 0.5)" for a semi-transparent red color.

The `color` property can be applied to any HTML element, such as `p`, `h1`, `span`, or `div`. It can also be used in combination with other CSS properties, such as `background-color` or `border-color`, to create a cohesive design for a web page.

###The size units in CSS

Size units in CSS are used to determine the size, spacing, and height of elements on a webpage. Here are some commonly used size units in CSS:

1. `px` (pixels): a measurement unit based on the pixel. This is the most common unit and is used to determine the size of elements on a webpage.

2. `em`: a measurement unit based on the height of the character. The size of an element is determined by the number of times the height of the character.

3. `rem`: a measurement unit based on the height of the root element. This is a common unit when you want to set the size based on the size of the root element.

4. `%` (percent): a measurement unit based on a percentage of the containing element. For example, if you want to set the width of an element to 50% of the width of the containing element, you can use the value `width: 50%;`.

5. `vw` (viewport width): a measurement unit based on a percentage of the viewport width (excluding the scrollbar). For example, if you want to set the width of an element to 50% of the viewport width, you can use the value `width: 50vw;`.

6. `vh` (viewport height): a measurement unit based on a percentage of the viewport height (excluding the scrollbar). For example, if you want to set the height of an element to 50% of the viewport height, you can use the value `height: 50vh;`.

There are also many other size units such as `pt`, `in`, `cm`, `mm`, but they are not commonly used in CSS.
	
###In CSS (Cascading Style Sheets), the `background-color` property is used to set the background color of an HTML element. This property can be used on any HTML element, and accepts a wide range of color values, including named colors, hexadecimal codes, RGB, and HSL values.

Here's an example of setting the background color of a `div` element to a light blue color:

```
div {
  background-color: #ADD8E6;
}
```

In this example, the hexadecimal color code `#ADD8E6` represents a light blue color.

You can also use named colors, such as `red`, `green`, `blue`, etc.:

```
div {
  background-color: red;
}
```

CSS also provides the ability to set a transparent background color using the `rgba()` or `hsla()` functions. For example, the following rule would set the background color of a `div` element to a semi-transparent black color:

```
div {
  background-color: rgba(0, 0, 0, 0.5);
}
```

In this example, the `rgba()` function sets the color to black (RGB values of 0, 0, 0), with an opacity value of 0.5 (50% transparent).

Overall, the `background-color` property is a useful and powerful tool in CSS for controlling the background color of HTML elements and creating visually appealing web pages.
	
###Background image in CSS, you can use the `background-image` property and specify the URL of the image file. Here's an example:

```css
.my-element {
  background-image: url("path/to/image.jpg");
}
```

In this example, `my-element` is the class name of the HTML element that you want to apply the background image to, and `"path/to/image.jpg"` is the URL or file path to the image file.

You can also add other properties to control the behavior of the background image, such as:

- `background-repeat`: controls how the image should repeat if it doesn't fill the entire element. Values can be `repeat`, `repeat-x`, `repeat-y`, or `no-repeat`.
- `background-position`: controls the starting position of the image. Values can be `left`, `center`, `right`, `top`, `bottom`, or a combination of values like `left top`.
- `background-size`: controls the size of the image. Values can be `cover`, `contain`, a specific length like `300px`, or a percentage like `50%`.

Here's an example that uses some of these properties:

```css
.my-element {
  background-image: url("path/to/image.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
```

This would set the background image to not repeat, be centered in the element, and fill the element while maintaining its aspect ratio.



