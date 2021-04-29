## Images
There are many reasons why you might
want to add an image to a web page: you
might want to include a logo, photograph,
illustration, diagram, or chart.
## HTML Images SyntaxThe HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

* src - Specifies the path to the image
* alt - Specifies an alternate text for the image
![](https://cdo-curriculum.s3.amazonaws.com/media/uploads/img_tag.png)
If you are building a site from scratch, it is good
practice to create a folder for all of the images
the site uses.
## Three Rules for Creating Images
1. Save images in the right format
2. Save images at the right size
3. Use the correct resolution
--------------------------------------------------------------------------------------------------------
## color
Color can really bring your pages to life.
color in CSS in one of three ways:
1. rgb values
rgb(red, green, blue)

ex : 

<h1 style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0)</h1>
<h1 style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255)</h1>
<h1 style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113)</h1>
<h1 style="background-color:rgb(238, 130, 238);">rgb(238, 130, 238)</h1>
<h1 style="background-color:rgb(255, 165, 0);">rgb(255, 165, 0)</h1>
<h1 style="background-color:rgb(106, 90, 205);">rgb(106, 90, 205)</h1>

------------------------------------------------------------------
2. hex codes
#rrggbb


3. color names
In CSS, a color can be specified by using a predefined color name:


** Understanding Color **
Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.
![](https://99designs-blog.imgix.net/blog/wp-content/uploads/2017/02/RBG-2-column.png?auto=format&q=60&fit=max&w=930)
## Text
Typeface Terminology
1. Serif
2. Sans-Serif
3. Monospace

Type Scales
You may have noticed that programs such as
Word, Photoshop and InDesign offer the same
sizes of text.

![](https://i1.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/03/CSS-Font-Property_tutorialbrain.png?fit=800%2C800&ssl=1)

## Example TEXT
<!DOCTYPE html>
<html>
<head>
		 <title>Text</title>
		 <style type="text/css">
			 body {
				 padding: 20px;}
			 h1, h2, h3, a {
				 font-weight: normal;
				 color: #0088dd;
				 margin: 0px;}
			 h1 {
				 font-family: Georgia, Times, serif;
				 font-size: 250%;
				 text-shadow: 2px 2px 3px #666666;
				 padding-bottom: 10px;}
			 h2 {
				 font-family: "Gill Sans", Arial, sans-serif;
				 font-size: 90%;
				 text-transform: uppercase;
				 letter-spacing: 0.2em;}
			 h3 {
				 font-size: 150%;}
			 p {
				 font-family: Arial, Verdana, sans-serif;
				 line-height: 1.4em;
				 color: #665544;}
			 p.intro:first-line {
				 font-weight: bold;}
			 .credits {
				 font-style: italic;
				 text-align: right;}
			 a {
				 text-decoration: none;}
			 a:hover {
				 text-decoration: underline;}
		 </style>
</head>

![](https://image.slidesharecdn.com/lab6fontcss-html-140916213022-phpapp01/95/lab6-font-css-html-8-638.jpg?cb=1410903066)
## source ##
[W3](https://www.w3schools.com/)
[HTML CSS](file:///home/sanaa/Downloads/HTML%20CSS.pdf)