## Transforms
The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

* Transform Syntax
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.


div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
# 2D Transforms
* 2D Rotate
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.

* HTML

<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>

              
* CSS

.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}

              

![](https://miro.medium.com/max/1440/1*_NVMTnvHTM9teQxrVRlDeg.png)


* 2D Scale
* 2D Skew
## 3D Transforms
![](https://www.found.co.uk/wp-content/uploads/2012/05/css3-3dtransforms-1.jpg)
* 3D Rotate
* 3D Scale
* 3D Translate
* 3D Skew
---------------------------------------------------------------------------------------------
## Transitions & Animations
Transitional Properties
It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. The display property, for example, may not be transitioned as it does not have any midpoint. A handful of the more popular transitional properties include the following.




[more_information](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
-------------------------------------------------------------------------------------------------
### i will read [ان شاءالله]
