# Program 3b
(area and width)

## Program Description:  
- Implement a class Rectangle
  - Should contain private class parameters for length, width, area, perimeter
  - Should implement the following methods:
    - A constructor with no parameters
      - Default values to 0
    - A constructor with parameters for length and width
      - Should set each variable logically
      - Should call calcArea and calcPerimeter before finishing
    - get/set methods for each parameter
      - When setting legnth or width:
        - Should round to the nearest 100th before storing
        - Should recalculate area/perimeter after setting
      - Replace setArea with
        - calcArea
          - Takes no parameters
          - Returns the area of the rectangle rounded to the nearest 100th
      - Replace setPerimeter with
        - calcPerimeter
          - Takes no parameters
          - Returns the perimeter of the rectangle rounded to the nearest 100th
    - toString
      - Takes no parameters
      - Returns a string formatted as: This rectangle with sides {Length} and {Width}, has an area of {Area} and a perimeter of {Perimeter}
- Implement a class RectangleTester
  - Implement the following methods
    - addRectangle
      - Takes no parameters
      - Takes user input to set up a new Rectangle
      - Returns a Rectangle object
    - main
      - Set up as a standard main method
      - Should call addRectangle once
      - Should call and print the results of toString for the rectangle
- Choose variable names which are meaningful for this problem, like Area, Width, etc.


### Statements Required: 
- System.out
- Variable Assignment
- Scanner
- Class creation and call

### Sample Output:
>Enter the length: 143
>
>Enter the width: 82
>
>-------------
>
>This rectangle with sides 143 and 82, has an area of 11726 and a perimeter of 450
>
