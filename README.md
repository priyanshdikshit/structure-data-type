# Structure datatype
## Introduction : 
In C programming, a struct (or structure) is a collection of variables (can be of different types) under a single name.
Structures (also called structs) are a way to group several related variables into one place. Each variable in the structure is known as a member of the structure. Unlike an array, a structure can contain many different data types (int, float, char, etc.).

## Why is it needed? 
Lets understand this with an example , there is a student variable that may have its name, class, section, etc. So if we want to store all of its information, We can create different variables for every variable like a character array to store name, integer variable to store the class, and a character variable to store the section. But this solution is a little messy, C provides us with a better neat and clean solution, i.e., Structure. Storing data for a single student is easy, but imagine creating that many variables for 50 students or even 500 or more. So to handle this type of problem, we need to create a user-defined data type that can store or bind different types of data types together, this can be done with the help of structure in C.

## How to create a structure? 
To create a structure in C, the struct keyword is used followed by the tag name of the structure. Then the body of the structure is defined, in which the required data members (primitive or user-defined data types) are added.

 **EXAMPLE**
      
      struct data 
      {
          
      };


## How to Declare Structure Variables?

**EXAMPLE**
      
      struct data
      {
          char name[50];
          char address[50];int age;
      };


## How to Initialize Structure Members?
Using Dot '.' operator
Using the dot (.) operator, we can access any structure member and then initialize or assign its value according to its data type.

Syntax:

     struct structure_name variable_name;
     variable_name.member = value;

## Accessing Structure elements: 
We can directly access the structure member using the dot(.) operator. The dot operator is used between the structure variable name and the structure member name we want to access. Let’s see the syntax to understand it in a better way.

     structure_variable.structure_member;


**Reference website:**
https://www.scaler.com/topics/c/structures-c/
 
