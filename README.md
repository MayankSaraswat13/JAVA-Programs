
Practice Questions

TOPIC ARRAY

Q1. write a Java program to find if the given number is palindrome or not

Example1)
C:\>java Sample 110011
O/P: 110011 is a palindrome

Example2)
C:\>java Sample 1234
O/P: 1234 is not a palindrome


Q2. Write a program to initialize an integer array with values and check if a given number is present in the array or not.

If the number is not found, it will print -1 else it will print the index value of the given  number in the array.

Example 1) If the Array elements are  {1,4,34,56,7} and the search element is 90, then the output expected is -1.

Example 2)If the Array elements are  {1,4,34,56,7} and the search element is 56, then the output expected is 3.

Q3. Initialize an integer array with ascii values and print the corresponding character values in a single row.


Q4. Write a program to print the sum of the elements of an array following the given below condition.

If the array has 6 and 7 in succeeding orders, ignore the numbers between 6 and 7
and consider the other numbers for calculation of sum.

Eg1) Array Elements - 10,3,6,1,2,7,9
O/P: 22
[i.e 10+3+9]

Eg2) Array Elements - 7,1,2,3,6
O/P:19

Eg3) Array Elements - 1,6,4,7,9
O/P:10


Q5. Given an array of type int, print true if every element is 1 or 4.

only14([1, 4, 1, 4]) → true
only14([1, 4, 2, 4]) → false
only14([1, 1]) → true

Q6. Write a program to reverse the elements of a given 2*2 array.
Four integer numbers needs to be passed as Command Line arguments.

Example1)
C:\>java Sample 1 2 3
O/P: Please enter 4 integer numbers

Example2)
C:\>java Sample 1 2 3 4
O/P:
 The given array is :
  1 2
  3 4
 The reverse of the array is :
  4 3
  2 1

Two dimensional Array




TOPIC PRACTISE QUES 3 

Questions for practice



Q1) Write a program that would print the information (name, year of joining, address) of three employees
by creating a class named 'Employee'. The output should be as follows:


Name     Year of joining     Address
Aman     2021                Chandigarh
Sunil    2000                Mathura
Rohan    2010                Agra



Q2) Write a program to print the area of two rectangles having sides (4,5) and (5,8) respectively
by creating a class named 'Rectangle' with two instance variables, length and breadth and
a  method named 'Area' which returns the area.
 the object attributes by taking the input from the user in the constructor


Q3) Write a program by creating an 'Employee' class having the following methods and print the final salary.

1 - 'getInfo()' which takes the salary, number of hours of work per day of the employee as parameter
2 - 'AddSal()' which adds $10 to the salary of the employee if it is less than $500.
3 - 'AddWork()' which adds $5 to the salary of the employee if the number of hours of work per day is more than 6 hours.


Try to solve these questions


TOPIC PRACTISE QUES 6
Create an abstract class Compartment to represent a rail coach. Provide an abstract function notice in this class.

public abstract String notice();

Derive FirstClass, Ladies, General, Luggage classes from the compartment class.
Override the notice function in each of them to print notice message that is suitable to the specific type of  compartment.

Create a class TestCompartment. Write main function to do the following:
Declare an array of Compartment of size 10.
Create a compartment of a type as decided by a randomly generated integer in the range 1 to 4.
Check the polymorphic behavior of the notice method.
[i.e based on the random  number genererated, the first compartment can be Luggage, the second one could be Ladies and so on..]



TOPIC CMD LINE ARGUMENTS
Which includes- ArgsCheck,Patient,Sum,TensDigit,University,interset,shape .java

Q1) Write a program to create a class named shape. It should contain 2 methods, draw()
and erase() that prints “Drawing Shape” and “Erasing Shape” respectively.



Q2) Design a class that can be used by a health care professional to keep track of a patient’s vital statistics.
The following are the details.
Name of the class - Patient
Member Variables - patientName(String),height(double),width(double)
Member Function - double computeBMI()
The above method should compute the BMI and return the result.
The formula for computation of BMI  is weight (in kg) ÷ height*height(in metres).
Create an object of the Patient class and check the results.


Q3) Write a program to accept gender ("Male" or "Female") and age from command line arguments
and print the percentage of interest based on the given conditions.

If the gender is 'Female' and age is between 1 and 58, the percentage of interest is 8.2%.

If the gender is 'Female' and age is between 59 and 100, the percentage of interest is 9.2%.

If the gender is 'Male' and age is between 1 and 58, the percentage of interest is 8.4%.

If the gender is 'Male' and age is between 59 and 100, the percentage of interest is 10.5%.



Q4) Write a Program that accepts two Strings as command line arguments and generate the output in the required format.

Example1)
If the two command line arguments are GLA and Mathura then the output generated should be GLA University Mathura.

Example2)
If the command line arguments are AAA and Delhi then the output generated should be AAA Technologies Delhi

[Note: It is mandatory to pass two arguments in command line]
Q6) Write a Program to accept two integers as command line arguments and print the sum of the two numbers

Example1)
C:\>java filename 10 20
O/P Expected : The sum of 10 and 20 is 30


Q7) Write a program to check if the program has received command line arguments or not.

If the program has not received arguments then print "No Values",
else print all the values in a single line separated by ,(comma)

Example1) java Example
O/P: No values

Example2) java Example Mumbai Bangalore
O/P: Mumbai,Bangalore

[Hint: You can use length property of an array to check its length]




Q8) Write a program that finds the tens digit in a non-negative integer N (0 ≤ N ≤ 1000000).
Take a look at the examples:
If N is 264, the tens digit is 6.

If N is 4136, the tens digit is 3.

If N is 101, the tens digit is 0.
Report a typo
Sample Input 1:
173
Sample Output 1:
7




