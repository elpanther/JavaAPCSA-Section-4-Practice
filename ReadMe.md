# JavaAPCSA Section 4 Practice

* Part A - Writing methods
* Part B - Process a name


## Part A

### Problem 1: Writing methods

#### Overview

In this practice, you will write methods that return values for the following scenarios:

#### Step 01

* Converts given temperature in Fahrenheit to Celsius:
    * Formula: C=5/9*(F-32)

#### Step 02

* Computes the hypotenuse length of a triangle given its side lengths.
  Formula: c = √(b²+a²)

#### Step 03

* Simulate the rolling of two 6-sided dice and display their sum.

### Tasks

You must implement the following:

### Task 1
In the ComputeMethods.java, define the following three methods:

   public double fToC(double degreesF)
   public double hypotenuse(int a, int b)
   public int roll()

### Task 2

In the TestClass.java, perform the following:

Add a main method, in the main method:
Create an instance of ComputeMethods and invoke the methods defined in ComputeMethods.java on this instance
and display their results.

### Expected Output Examples

Temp in celsius is 38.00000000000001
Hypotenuse is 10.816653826391969
The sum of the dice values is 9

## Part B

### Problem 2: Process a name

#### Overview

In this practice, you will develop a java program that processes a name entered by the user. The program does the following:
It reads the user's first and last name (read an entire line as a single string), then prints the last name followed by a comma and the first
initial. (Assume that the user types a valid name.)

### Task

You must implement the following in the ProcessName.java file:
1. Have the user enter a name
2. Extract the first and last name from the name entered by the user
3. Use methods of String class to manipulate name as specified:
4. Display the name to the console
   
 
### Expected Output Example:

   Type your name: Jenny Weaver
   Your name is: Weaver, J.