Hello , Thanks for the lookup in my page, calculating a cgpa is one of the thing , we need to correctly enter one by one credits,grades in calculator sometime
we mistakenly enterd wrong value and results wrong cgpa, some of the still dont know how to calculate cgpa, so i designed a java console level project to
calculate cgpa . the main motive of doing this project is help student to calculate cgpa easily, it also calculate sgpa too.
the concepts i used in java code are listed below:

1. Class and Main Method

class Main → Defining a class named Main.

public static void main(String[] args) → Entry point of every Java program.

2. Static Method

static int cal(int a,int b) → A static method for modularity and reusability.

It performs multiplication of grade and credit.

Shows method definition, parameters, return type.

3. Scanner Class (User Input)

Scanner sc = new Scanner(System.in);

Used to take runtime input from the user.

Belongs to java.util package.

4. Variables and Data Types

int sem, sub, a, b, res, gra → Integer variables.

float sum → Floating-point variable for handling division result precisely.

5. Loops (Iteration)

for (int j=0; j<sem; j++) → Outer loop for semesters.

for (int i=0; i<sub; i++) → Inner loop for subjects.

Shows nested loops.

6. Arithmetic Operators

gra += b; → Incremental addition (compound assignment).

res = cal(a,b); → Multiplication via method.

sum += res; → Accumulation.

7. Input/Output

System.out.print() & System.out.printf()

Output formatting (like "%.2f" for 2 decimal places).

8. Type Conversion / Casting

sum/gra → Implicit type conversion happens (int denominator + float numerator = float result).

9. Algorithmic Concept

This code calculates CGPA/weighted average:

Formula → Σ(grade × credit) ÷ Σ(credits)

Summary of Concepts Used:

Class & main method

Static method (function)

Scanner class (input handling)

Variables & data types

Loops (for, nested loops)

Arithmetic operators

Input/output (print, printf)

Type conversion (int → float in division)

Algorithm for weighted average (CGPA calculation)
