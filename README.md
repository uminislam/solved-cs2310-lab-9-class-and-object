Download Link: https://assignmentchef.com/product/solved-cs2310-lab-9-class-and-object
<br>



<strong>Q-1.</strong> Design and implement a class named “Employee” to compute the net salary of an employee using the basic salary, medical allowance, and house rent (45% of basic salary).

The design of Employee class should include:

<ul>

 <li>Three private members basic_sal, med_allow, and h_rent, which present basic salary, medical allowance and house rent of an employee.</li>

 <li>One private member net_sal to preserve the computed net salary of an employee.</li>

 <li>A default constructor (i.e., Employee()) to initialize the basic_sal, med_allow, and h_rent as 3000, 500, and 1350 (as 45% of 3000).</li>

 <li>A parameter constructor (i.e., Employee(int, int)) to initialize the values of basic_sal and med_allow of an employee.</li>

 <li>A set method (i.e., set(int, int)) to enter the new basic salary and medical allowance of an employee.</li>

 <li>A method (i.e., computeNetSalary()) to compute the net salary of an employee. The net salary of an employee should be computed through the following formula: net salary = basic salary + medical allowance + house rent, where house rent = 45% of basic salary.</li>

 <li>A get method (i.e., get()) to display the net salary of an employee.</li>

</ul>




According to the requirements above, write a program to compute the net salary of two employees:

<ul>

 <li>Create first Employee object (i.e., <em>Emp1</em>) with default constructor.</li>

 <li>Enter the value of basic salary and medical allowance of second employee (i.e., <em>Emp2</em>) and create it with parameter constructor.</li>

 <li>Compute the net salary of both employees (<em>Emp1</em> and <em>Emp2</em>) by calling computeNetSalary()</li>

 <li>Display the net salary of both employees (<em>Emp1</em> and <em>Emp2</em>) by calling get()</li>

 <li>Enter new basic salary and medical allowance of <em>Emp1</em> by calling set() method.</li>

 <li>Compute and display the net salary of <em>Emp1</em>.</li>

</ul>

<strong> </strong>

<strong><u>Expected Outputs:</u> </strong>




Enter basic salary for Emp2: <strong><u>4000</u> </strong>

Enter medical allowance for Emp2: <strong><u>600</u> </strong>

The net salary for Emp1 is 4850

The net salary for Emp2 is 6400 Enter basic salary for Emp1:

<strong><u>5000</u></strong>

Enter medical allowance for Emp1:

<h1>1000</h1>

The net salary for Emp1 is 8250

<strong>Q-2.</strong> Design and implement a class to compute the area of a triangle using the values of their sides. The design of class (named Triangle) should include:

<ul>

 <li>Three private members side1, side2, and side3, which present sides of a triangle.</li>

 <li>One private member area to preserve the computed area of triangle.</li>

 <li>A default constructor (i.e., Traingle()) to initialize sides of triangle and area of triangle as zero.</li>

 <li>A parameter constructor (i.e., Traingle(double, double, double)) to initialize the values of sides for corresponding triangle and initialize area of triangle as zero.</li>

 <li>A set method (i.e. setSides(double, double, double)) to enter the new values for the sides.</li>

 <li>A method (i.e. computeArea()) to compute the area of triangle.</li>

 <li>A get method (i.e. getArea()) to display the area.</li>

</ul>







<em>Hint-1. Area of Tringle can be computed through the following Heron’s Formula: </em>

<em>Area = sqrt(s*(s-a)*(s-b)*(s-c)), where s=(a+b+c)/2. </em>

<em> </em>

<em>Hint-2. You need to include &lt;</em><em>cmath&gt; library to use the </em><em>sqrt() function and include &lt;iomanip&gt; library to use </em><em>setprecision and </em><em>fixed manipulators to change the precision value and printing format. </em>




According to the requirements above, write a program which defines an array of triangles




Triangle arr[10].




The program should let the user input the sides of n triangles (where n is an integer input by the user and 1≤n≤10) and store them in the array. The program should print the area of all triangles and also print the name of the triangle with the largest area (if there are two or more triangles with the same maximum area, only print the first one in the original order that they are defined).




Assume that all inputs are valid, i.e., n is within the range specified, and those three sides can form a triangle.





































<strong><u>Expected Outputs:</u> </strong>

<strong> </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="603"><strong>Example 1.</strong></td>

  </tr>

  <tr>

   <td width="603">Enter a number between 1 and 10:  <strong><u>4</u> </strong>Enter the sides of triangle 1:<strong><u>3 3 3</u></strong>Enter the sides of triangle 2:<strong><u>3 4 5</u></strong>Enter the sides of triangle 3:<strong><u>3 4 5</u></strong>Enter the sides of triangle 4:<strong><u>3 2 3</u></strong>Area of triangle 1: 3.90Area of triangle 2: 6.00Area of triangle 3: 6.00Area of triangle 4: 2.83Triangle 2 has the largest area: 6.00</td>

  </tr>

  <tr>

   <td width="603"><strong>Example 2.</strong></td>

  </tr>

  <tr>

   <td width="603">Enter a number between 1 and 10:  <strong><u>5</u> </strong>Enter the sides of triangle 1:<strong>6  </strong><strong><u>6 6</u></strong>Enter the sides of triangle 2: <strong><u>4 5 6</u> </strong>Enter the sides of triangle 3:<strong>7  </strong><strong><u>8 9</u></strong>Enter the sides of triangle 4:<strong><u>3 4 5</u></strong>Enter the sides of triangle 5:<strong><u>5 7 5</u></strong>Area of triangle 1: 15.59Area of triangle 2: 9.92Area of triangle 3: 26.83Area of triangle 4: 6.00Area of triangle 5: 12.50Triangle 3 has the largest area: 26.83</td>

  </tr>

 </tbody>

</table>


