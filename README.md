/*
Object oriented programming Lab 3 question 4

Complete the Rectangle class by
1.	Declaring the double width instance variable
2.	Declaring the double length instance variable
3.	Writing the constructor method with input parameters for width and length
4.	Writing the method double area() to compute the Rectangle area
Complete the main method by
1.	Using new to create a  Rectangle instance with constructor input 50.5 and 25.7 for width and length
2.	Printing its instance variables using the standard output formatting (See example output)
3.	Printing the return value of the area() method on the Rectangle instance



For example:
Test	Result
Rectangle r = new Rectangle(1.2,1.4);
System.out.println(r.width);	1.2

Rectangle r = new Rectangle(1.2,1.4);
System.out.println(r.length);	1.4

Rectangle r = new Rectangle(1.2,1.4);
System.out.println(r.area());	1.68

Rectangle.main(new String[]{});	width = 50.5
length = 25.7
area = 1297.85







public class Rectangle 
{
 
 //declare instance vars here
     
  //write constructor here
  
  //write the area method here
    
    public static void main(String[] args) 
    {
        
      //instantiate Rectangle object
      
      //print instance variables
      
      //print area
  
    }
}
*/
public class Rectangle {
    // Declare instance variables
    double width;
    double length;

    // Constructor method with input parameters for width and length
    public Rectangle(double width, double length) {
        this.width = width;
        this.length = length;
    }

    // Method to compute the area of the rectangle
    public double area() {
        return width * length;
    }

    public static void main(String[] args) {
        // Instantiate a Rectangle object
        Rectangle myRectangle = new Rectangle(50.5, 25.7);

        // Print instance variables
        System.out.println("width = " + myRectangle.width);
        System.out.println("length = " + myRectangle.length);

        // Print area
        System.out.println("area = " + myRectangle.area());
    }
}
