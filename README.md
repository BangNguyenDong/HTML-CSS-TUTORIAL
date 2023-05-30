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
<br>
###LESSON3 <br>

## The `<div>` tag in HTML

### Introduction

In HTML, the `<div>` tag is used to create a block-level element to divide and group other elements in a web page. The `<div>` tag doesn't have a specific semantic meaning, but it's a useful tool to manage HTML components.

### Syntax

The syntax of the `<div>` tag is as follows:

```html
<div>
    <!-- Content of the div element -->
</div>
```

### Attributes

You can add attributes to the `<div>` tag to customize this element. Here are some common attributes:

- `class`: Defines a CSS class for the `<div>` element
- `id`: Defines a unique identifier for the `<div>` element
- `style`: Defines inline CSS formatting for the `<div>` element

### Example

Here's an example of using the `<div>` tag in HTML to create two different elements:

```html
<div id="header">
    <h1>This is a title</h1>
    <p>This is a short description</p>
</div>

<div class="container">
    <h2>This is the main title</h2>
    <p>This is the main content</p>
</div>
```

In the example above, we use the `<div>` tag to create two different elements. The first element has an `id` attribute set to "header", and the second element has a `class` attribute set to "container".

## CSS for the `<div>` tag

### Introduction

CSS stands for Cascading Style Sheets. It's a stylesheet language for HTML and XML documents. CSS allows you to control how HTML elements are displayed on your web page.

### CSS Formatting for the `<div>` Element

To format CSS for the `<div>` element, you can use CSS classes or inline CSS formatting through the `style` attribute of the `<div>` tag.

Here's an example of CSS formatting for the `<div>` tag:

```css
#header {
    background-color: blue;
    color: white;
}

.container {
    background-color: white;
    border: 1px solid black;
    padding: 10px;
}
```

In the example above, we use CSS to format the elements created with the `<div>` tag. We set a blue background and white text color for the element with the `id` attribute "header". We set a white background, a black border of 1 pixel thickness, and a 10-pixel padding for the element with the `class` attribute "container".

## Conclusion

In conclusion, the `<div>` tag is a useful tool in HTML to divide and group other elements on a web page. You can use CSS to format the `<div>` element and its content.
<br>


## ID

In HTML, the ID attribute is used to uniquely identify an element on a web page. The ID attribute value should be unique on a web page and cannot be used for multiple elements.

Here is an example of how to use the ID attribute in HTML:

```html
<div id="header">
    <h1>Welcome to my website!</h1>
</div>
```

In the example above, we use the ID attribute to identify the div element with the ID "header". We can use this ID in CSS to apply styles to this element, like changing its background color or font size.

To apply styles to an element with a specific ID in CSS, we use the "#" symbol followed by the ID name. For example, to change the background color of the element with the ID "header" to blue, we would use the following CSS:

```css
#header {
    background-color: blue;
}
```

## Class

In HTML, the class attribute is used to group elements together. The class attribute value can be used for multiple elements on a web page and allows us to apply the same styles to those elements.

Here is an example of how to use the class attribute in HTML:

```html
<div class="container">
    <h2>This is a container</h2>
    <p>This is some text inside the container.</p>
</div>

<div class="container">
    <h2>This is another container</h2>
    <p>This is some text inside the second container.</p>
</div>
```

In the example above, we use the class attribute to group the two div elements together. We can use this class in CSS to apply styles to both elements, like changing their background color or font size.

To apply styles to elements with a specific class in CSS, we use the "." symbol followed by the class name. For example, to change the background color of all elements with the class "container" to gray, we would use the following CSS:

```css
.container {
    background-color: gray;
}
```

## Conclusion

In conclusion, ID and class are two important attributes in HTML and CSS that allow us to define styles for elements on a web page. The ID attribute is used to uniquely identify an element, while the class attribute is used to group elements together. Understanding how to use ID and class is crucial for creating well-structured and easy-to-maintain web pages.
	
<br> 
	
Margin and padding are two important properties in CSS used to create spacing and formatting for elements in HTML.

## Margin

Margin is the space outside of an element and the elements around it. The margin property is used to adjust the space between elements and create empty space around them.

The syntax for the margin property in CSS:

```css
selector {
    margin: top right bottom left;
}
```

- `top`, `right`, `bottom`, `left` are the values that define the spacing. You can use values such as pixels (px), percentages (%), em (em), or other measurement units.

For example, to set the top margin to 10px, right and left margins to 20px, and the bottom margin to 15px, you can use:

```css
div {
    margin: 10px 20px 15px;
}
```

If only one value is specified, the margin will be applied to all edges in the order of top, right, bottom, left.

## Padding

Padding is the space between the content inside an element and its border. The padding property is used to change the spacing between the content and border of an element.

The syntax for the padding property in CSS:

```css
selector {
    padding: top right bottom left;
}
```

- `top`, `right`, `bottom`, `left` are the values that define the spacing, similar to the margin property.

For example, to set the top padding to 10px, right and left padding to 20px, and the bottom padding to 15px, you can use:

```css
div {
    padding: 10px 20px 15px;
}
```

If only one value is specified, the padding will be applied to all edges in the order of top, right, bottom, left.

## The difference between margin and padding

- Margin creates space outside of an element, while padding creates space inside of an element.
- Margin affects the space between elements, while padding affects the space between the content and border of an element.
- Margin is calculated into the total size.
	
Border and box-sizing are two important properties in CSS used to format and adjust the size of elements in HTML.

## Border

Border is the line around an HTML element. The border property in CSS is used to format and set the border for an element.

The syntax for the border property in CSS is:

```css
selector {
    border: width style color;
}
```

- `width`: Sets the thickness of the border, and can use values like pixels (px) or other measurement units.
- `style`: Sets the style of the border, such as solid, dashed, dotted, and many other styles.
- `color`: Sets the color of the border, and can use CSS color values such as color names, hex codes, or RGB.

For example, to set a black border with a thickness of 1px for a div element, you can use:

```css
div {
    border: 1px solid black;
}
```

Alternatively, you can specify each property separately, such as `border-width`, `border-style`, and `border-color`, to customize each border element individually.

## Box-sizing

The box-sizing property determines how the size of an element is calculated, including padding and border.

The syntax for the box-sizing property in CSS is:

```css
selector {
    box-sizing: value;
}
```

- `value`: Sets the value of box-sizing, and can use the value `content-box` (the default value) to calculate the size based on the content inside the element, or `border-box` to calculate the size including padding and border.

For example, to set box-sizing for a div element to calculate the size including padding and border, you can use:

```css
div {
    box-sizing: border-box;
}
```

Using the `border-box` value, the size of the element will include the content, padding, and border, making it easier to manage element sizes.

## Conclusion

In summary, border is a property used to format the line around an element, while box-sizing is a property used to calculate the size of an element including padding and border. Understanding these properties is crucial for building well-formatted and responsive web pages.
<br>
<h1>Lesson4 </h1>
<br>
Below is the document with detailed explanations for the provided code:

```html
<body>
	<!-- ul: unordered list -->
	<!-- ol: ordered list -->
	<!-- li: list item -->
	<!-- list-style-type: none, circle, square, decimal, lower-alpha, upper-alpha, lower-roman, upper-roman -->
	<!-- list-style-position: inside, outside -->
	<!-- list-style-image: url() -->
	<!-- float: left, right, none -->
	<!-- clear: left, right, both, none -->
	<h1>Unordered List</h1>
	<ul>
		<li>Item 1</li>
		<li>Item 2</li>
		<li>Item 3</li>
	</ul>
	<h1>Ordered List</h1>
	<ol>
		<li>Item 1</li>
		<li>Item 2</li>
		<li>Item 3</li>
	</ol>
	<!-- list-style-type: none, circle, square, decimal, lower-alpha, upper-alpha, lower-roman, upper-roman -->
	<h1>List Style Type</h1>
	<ul style="list-style-type: circle;">
		<li>Item 1</li>
		<li>Item 2</li>
		<li>Item 3</li>
	</ul>
	<!-- list-style-position: inside, outside -->
	<h1>List Style Position</h1>
	<ul style="list-style-position: inside;">
		<li>Item 1</li>
		<li>Item 2</li>
		<li>Item 3</li>
	</ul>
	<!-- list-style-image: url() -->
	<h1>List Style Image</h1>
	<ul style="list-style-image: url(circle.png);">
		<li>Item 1</li>
		<li>Item 2</li>
		<li>Item 3</li>
	</ul>
	<h1>Float</h1>
	<div style="background-color: red; width: 100px; height: 100px; float: left;"></div>
	<div style="background-color: blue; width: 100px; height: 100px; float: left;"></div>
	<div style="background-color: green; width: 100px; height: 100px; float: left;"></div>
	<div style="background-color: yellow; width: 100px; height: 100px; float: left;"></div>
	<div style="background-color: orange; width: 100px; height: 100px; float: left;"></div>
	<h1 style="clear:left">Clear</h1>
	<div style="background-color: red; width: 100px; height: 100px; float: right;"></div>
	<div style="background-color: blue; width: 100px; height: 100px; float: right;"></div>
	<div style="background-color: green; width: 100px; height: 100px; float: right;"></div>
	<div style="background-color: yellow; width: 100px; height: 100px; float: right;"></div>
	<div style="background-color: orange; width: 100px; height: 100px; float: right;"></div>
	<h1 style="clear:right">Clear</h1>
</body>
```

Explanation:

- The `<body>` tag represents the content of the HTML document that will be displayed in the browser.

Unordered List:
- The `<ul>` tag is used to create an unordered list.
- Inside

 the `<ul>`, we have three list items represented by the `<li>` tags.
- This section demonstrates a basic unordered list.

Ordered List:
- The `<ol>` tag is used to create an ordered list.
- Inside the `<ol>`, we have three list items represented by the `<li>` tags.
- This section demonstrates a basic ordered list.

List Style Type:
- The `<ul>` tag has a `style` attribute with the `list-style-type` property set to "circle".
- This changes the bullet points of the unordered list to circles.

List Style Position:
- The `<ul>` tag has a `style` attribute with the `list-style-position` property set to "inside".
- This moves the bullet points of the unordered list inside the list items.

List Style Image:
- The `<ul>` tag has a `style` attribute with the `list-style-image` property set to "url(circle.png)".
- This replaces the bullet points of the unordered list with a custom image specified by the URL.

Float:
- Five `<div>` elements are used with different background colors and dimensions.
- Each `<div>` has a `float` property set to "left", causing them to align horizontally.

Clear:
- The `<h1>` heading with the "Clear" text has a `style` attribute with the `clear` property set to "left".
- This clears the left float, allowing the heading to appear below the floated `<div>` elements.

Conclusion:
- The provided code demonstrates various aspects of HTML lists and CSS styling, including different list types, list item styles, list position, list images, floating elements, and clearing floats.
- Experiment with the code and make modifications to understand how the different properties and styles affect the appearance of the elements.
<br>
<h1> LESSON5 - DISPLAY - HOVER </h1>
Here's an example of HTML and CSS code demonstrating block elements, inline elements, and inline-block elements:

html
Copy code
<!DOCTYPE html>
<html>
<head>
  <style>
    /* CSS for block elements */
    .block-element {
      display: block;
      width: 200px;
      height: 100px;
      background-color: red;
      margin-bottom: 10px;
    }

    /* CSS for inline elements */
    .inline-element {
      display: inline;
      padding: 5px;
      background-color: blue;
      color: white;
    }

    /* CSS for inline-block elements */
    .inline-block-element {
      display: inline-block;
      width: 100px;
      height: 50px;
      background-color: green;
      margin-right: 10px;
    }
  </style>
</head>
<body>
  <!-- Block elements -->
  <div class="block-element"></div>
  <div class="block-element"></div>

  <!-- Inline elements -->
  <span class="inline-element">Element 1</span>
  <span class="inline-element">Element 2</span>
  <span class="inline-element">Element 3</span>

  <!-- Inline-block elements -->
  <div class="inline-block-element"></div>
  <div class="inline-block-element"></div>
  <div class="inline-block-element"></div>
</body>
</html>
In the above example, we define three different CSS styles for block elements, inline elements, and inline-block elements. Each style has a different display property.

.block-element uses display: block; to turn the elements into block elements.
.inline-element uses display: inline; to turn the elements into inline elements.
.inline-block-element uses display: inline-block; to turn the elements into inline-block elements.
You can use this example to see the differences in how the elements are displayed in a web browser. We have two block elements displayed vertically, three inline elements displayed side by side, and three inline-block elements displayed side by side.

I hope this example helps you understand the concept of block elements, inline elements, and inline-block elements better.
