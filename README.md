Department of Computer Science
The City College of CUNY
CSc 22100-F: Software Design Laboratory [Fall 2016]
Exercise 4
A printout showing the codes developed and outputs produced for the tests indicated is due during and before the end of the class on Monday, 21 November 2016. The deadline is strictly observed.
1- Amend the a hierarchy of Java classes in Exercise 2 as follows:
Triangle is_a Shape;
Circle is_a Shape;
Rectangle is_a Shape;
class Rectangle:
class Rectangle inherits abstract class Shape. The Rectangle object is defined by its width, width, height, height, and point (x, y) within the object, and may be filled with a color. The class includes appropriate class constructors and methods that perform the following operations:
a. getArea – returns the area of Rectangle object;
b. getPerimeter – returns the perimeter of Rectangle object;
c. getWidth, getHeight – returns the width and height of Rectangle object;
d. setWidth, setHeight – resets the width and height of Rectangle object;
e. toString - returns a string representation of Rectangle object: width and height;
f. draw – draws Rectangle object.
2- Build a class Application that processes polymorphically the subclasses in the hierarchy to draw the geometric objects in Exercises 1 and 3. The drawing panel should use a layout manger and include appropriate GUI components to select between and draw the geometric objects.
Hesham A Auda
14 November 2016