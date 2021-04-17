- Class A is a subclass of class B. Class A also implements interface C. Represent this in java code. What java keywords can be used to implement this relationship? (3 marks)
- An Employee class implements the Comparable interface in the java lang package. The Comparable interface has a compareTo method with the following signature and description. [12 marks]
    - ```java 
        public int compareTo(Object o)
        ```
        Method description - Compares this object with the specified object for order. Returns a negative integer, zero, or a positive integer as this object is less than, equal to, or greater than the specified object.
      - The Employee class has attributes employee ID and employee name, both of which are String variables.
    - Write java code for the Employee class. You should have a constructor to set the employee ID and employee name and methods to get and set the attributes. Implement the compareTo method which will compare two Employee objects based on the employee ID.
    - Write a single java method sortArray with the following signature,
      - ```java 
        public void sortArray( Employee[] emp )
        ```
        that takes a reference to an Employee array as the input argument and sorts the array in ascending order of employee IDs, using the bubble sort algorithm described below.
        - Bubble Sort Algorithm: Scan through the complete array, left to right, comparing adjacent elements and swapping them if they are out of order. Repeat this process until no elements are swapped during a particular scan. \
        Note:
          1. sortArray is NOT a method in Employee class.
          2. You can write any additional methods that are required for sorting the array.
          3. You DO NOT have to write a program (main method) to test sortArray method.
- What is the output of the following program? [0.5 Marks]
  - ```java
        public class LoopTestB {
            public static void main(String [] args) {
                String [] sa = {"hello ", "world "};
                for(int x = 0; x < 3; x++) {
                    for(String s: sa) {
                        if( x == 1)
                            continue;
                        System.out.print(x + " " + s);
                    }
                }
            }
        }
    ```
- What is the output of the following program? [0.5 Marks]
  - ```java
        class A {
            private int a = 2;
            public A(int x) {a = x*2;}
            public A() {this (5);}
            public int test () {return a;}
            public static void main(String argv []) {
                A a1 = new A();
                A a2 = new A(9);
                System.out.println(a1.test ()*a2.test ());
            }
        }
    ```
- One of the lines in this program results in a compilation error. In the space provided write the corrected version of this line (include the line number of the corrected line in your answer). [0.5 Marks]
  - ```
    1
    2 public class LoopTestE {
    3
    4   public static void main(String [] args) {
    5
    6       int i = 0;
    7       char [] A = {’A’, ’B’, ’C’, ’D’};
    8
    9       for (int i = 0; i < A.length; i++)
    10          System.out.println("A(" + i + ") = " + A[i]);
    11  }
    12
    13 }
    ```
- Consider a GraphicCircle class which extends (inherits from) a Circle class; the printDetails() method in the Circle class is overridden in the GraphicCircle class and the Circle class has a constructor which has three integer parameters. Consider the following Java application. [0.5 Marks]
  - ```
    1
    2 public class TestCircle {
    3   public static void main(String [] args){
    4       Circle c = new Circle (10, 10, 0);
    5       GraphicCircle gc = (GraphicCircle)c;
    6       gc.printDetails();
    7   }
    8 }
    ```
  - Which of the following is true?
    1. In line 6, the printDetails() method of the Circle class will get executed.
    2. In line 6, the printDetails() method of the GraphicCircle class will get executed.
    3. The program will produce a runtime error.
    4. The program will produce a compile time error.
    5. The printDetails() method of both the Circle and GraphicCircle classes will get executed.
- Name the type of visibility modifier that would not be valid for an abstract method? [0.5 Marks]

