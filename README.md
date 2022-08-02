# Introduction to Polygon
Polygon are two-dimensional geometric objects composed of points and straight lines connecting those points.

Sample of Polygon:

![polygon](https://cdn-skill.splashmath.com/panel-uploads/GlossaryTerm/277097a6a870457e90553ed24cf46042/1548051233_Two-dimensional-2-D-shapes-circle-triangle-square-polygons.png
)

## Type of Polygon:
1. Square
2. Rectangle
3. Triangle
4. Circle

## Notation of triangle

![triangle](https://i.stack.imgur.com/1GkR3.png
)

## Methods of Square

1. Is valid
2. Perimeter
3. Area

## Methods of Rectangle

1. Is valid
2. Perimeter
3. Area

## Methods of Triangle

1. Is valid
2. Get Type
3. Perimeter
4. Area

## Methods of Circle
1. Is valid
2. Diameter
3. circumference
4. Area

# Usage examples

## Example of Square

```dart
square = Square(5);
is_valid_square = square.is_valid();
square_perimeter = square.perimeter();
square_area = square.area();
print("Can it be a square?");
print(is_valid_square);
// can it be a square? True
print("The perimeter of the square is:");
print(square_perimeter);
// the perimeter of the square is: 20
print("the area of the square is:");
print(square_area);
// the area of the square is: 25
```

## Example of Rectangle

```dart
rectangle = Rectangle(4, 7);
is_valid_rectangle = rectangle.is_valid();
rectangle_perimeter = rectangle.perimeter();
rectangle_area = rectangle.area();
print("Can it be a square?");
print(is_valid_rectangle);
// can it be a square? True
print("The perimeter of the rectangle is:");
print(rectangle_perimeter);
// the perimeter of the rectangle is: 22
print("the area of the rectangle is:");
print(rectangle_area);
// the area of the rectangle is: 28
```

## Example of Triangle

```dart
triangle = Triangle(4, 7, 5);
is_valid_triangle = triangle.is_valid();
triangle_perimeter = triangle.perimeter();
triangle_area = triangle.area();
print("Can it be a triangle?");
print(is_valid_triangle);
// can it be a triangle? True
print("The perimeter of the triangle is:");
print(triangle_perimeter);
// The perimeter of the triangle is: 16
print("The area of the triangle is:");
print(triangle_area);
// The area of the triangle is: 9.797958971132712
```

## Example of Circle

```dart
circle = Circle(4);
is_valid_circle = circle.is_valid();
circle_diameter = circle.diameter();
circle_circumference = circle.circumference();
circle_area = circle.area();

print("Can it be a circle?");
print(is_valid_circle);
// can it be a circle? True
print("The diameter of the circle is:");
print(circle_diameter);
// The diameter of the circle is: 8
print("The circumference of the circle is:");
print(circle_circumference);
// The circumference of the circle is: 25.132741228718345
print("The area of the circle is:");
print(circle_area);
// The area of the circle is: 50.26548245743669
```
