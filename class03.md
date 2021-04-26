# LIST
three types of list in HTML :
* Ordered lists         <ol></ol>
![](https://1.bp.blogspot.com/-rpOY4wFXI2U/XMM1vrUNRBI/AAAAAAAAC0c/kqPiH0lOJ_g6FfxvGu0GJ5mUic90wBOJQCLcBGAs/s640/Ordered-List-using-html.png)
each item in list is numbere
* Unordered lists      <ul></ul>
  ![](https://1.bp.blogspot.com/-UarALmUBD8A/XMMyAsHDnSI/AAAAAAAACzs/R4kurkGI6E0X2SWSRxCQrQ1c7Fl2DBYwACLcBGAs/s640/Unordered-List-using-HTML.png)
  ex :                           
  <ul>
    <li>Coffee</li>     
    <li>Tea</li>
    <li>Milk</li>
  </ul>  

  output : 
    * Coffee
    * Tea
    * Milk

* Definition lists
A description list is a list of terms, with a description of each term.

The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each
------------------------------------------------------------------------------------------------------
# Boxes
** Border, Margin & Padding **
![](https://media.geeksforgeeks.org/wp-content/uploads/cssmarginandpadding.png)
* Content - The content of the box, where text and images appear
* Padding - Clears an area around the content. The padding is transparent
* Border - A border that goes around the padding and content
* Margin - Clears an area outside the border. The margin is transparent

# Border Images
 * Syntax
    border-image: source slice width outset repeat|initial|inherit;
    ![](https://doc.qt.io/archives/qt-4.8/images/qml-borderimage-example.png)
# Box Shadows
   The box-shadow property allows you to add a drop shadow around a box.
   ![](https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2014/12/text-shadow-syntax-img1.png)
   ![](https://i.pinimg.com/600x315/99/13/96/99139605fa9f983eed9fbc73d8997d14.jpg)


# Elliptical Article Shapes
border-radius
   The border-bottom-right-radius property defines the radius of the bottom-right corner.

 Tip: This property allows you to add rounded borders to elements!
![](https://i.ytimg.com/vi/vn41-lpnjNM/maxresdefault.jpg)

## source ##
[W3](https://www.w3schools.com/)
[HTML CSS](file:///home/sanaa/Downloads/HTML%20CSS.pdf)
------------------------------------------------------------------------------------------------------
# ARRAYS 
   array is a special variable, which can hold more than one value at a time.
If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

var car1 = "Saab";
var car2 = "Volvo";
var car3 = "BMW";
However, what if you want to loop through the cars and find a specific one? And what if you had not 3 cars, but 300?

The solution is an array!

An array can hold many values under a single name, and you can access the values by referring to an index number.

## Creating an Array

Syntax:

var array_name = [item1, item2, ...]; 
## ACCESSING & CHANG ING VALUES IN AN ARRAY
![](https://www.tutorialsteacher.com/Content/images/csharp/array.png)

* Popping
  The pop() method removes the last element from an array:
  ex: 
  var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.pop();              // Removes the last element ("Mango") from fruits
---------------------------------------------------------------------------------------------------
## Comparison operators 
(===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands

## IF ... ELSE STATEMENTS
In JavaScript we have the following conditional statements:

* Use if to specify a block of code to be executed, if a specified condition is true
* Use else to specify a block of code to be executed, if the same condition is false
* Use else if to specify a new condition to test, if the first condition is false
* Use switch to specify many alternative blocks of code to be executed

## Syntax ## 
if (condition) {
  //  block of code to be executed if the condition is true
} else {
  //  block of code to be executed if the condition is false
}

## SWITCH STATEMENTS
SWITCH STATEMENTS 
A switch statement starts with a
variable called the switch value.
Each case indicates a possible
value for this variable and the
code that should run if the
variable matches that value.
* Syntax
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
## ex 
switch (new Date().getDay()) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
     day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
}
------------------------------------------------------------------
## TRUTHY & FALSY VALUES
Due to type coercion, every value in JavaScript
can be treated as if it were true or false; and
this has some interesting side effects

## JavaScript For Loop
![](https://www.sitesbay.com/javascript/images/for-loop-steps.png)


* Different Kinds of Loops
JavaScript supports different kinds of loops:

1. for - loops through a block of code a number of times
2. for/in - loops through the properties of an object
3. for/of - loops through the values of an iterable object
4. while - loops through a block of code while a specified condition is true
5. do/while - also loops through a block of code while a specified condition is true
ex: 
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
outbut:
The number is 0
The number is 1
The number is 2
The number is 3
The number is 4

* WHILE LOOPS

Syntax
while (condition) {
  // code block to be executed
}
* DO WHILE LOOPS

Syntax
do {
  // code block to be executed
}
while (condition);