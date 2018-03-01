# X-Team 62 Style Guide

We prefer style guides which is not too cumbersome for writing code efficiently.
This also allows our code to be more clear and read easily. 

## Naming conventions

We use camel casing when naming methods and variables, while using minimal abbreviation.
The name must be generally descriptive of the action it performs.

### Examples
* interfaces - SearchTreeADT, Comparable etc.
* classes - BalancedSearchTree, Random etc.
* exception types - DuplicateKeyException, IndexOutOfBoundsException etc.
* fields - leftChild, rightChild, size, list, tree etc.
* methods - insert(), remove(), getRightChild(), etc.
* parameters - value, key, node, etc. 
* local variables - temp, node, x, value, i, etc.
* instance constants - TABLE_SIZE, MAX_VALUE, etc.
* class constants - TABLE_SIZE, MAX_VALUE, etc. 

## Commenting style for public and private members of a class or interface:

<brief statement of your team's commenting style>
We use javadocs indicating the method's function (any parameters and return type) and 
comment complex algorithms.

### Examples

* classes - indicate author, description

//@author - NAME
public class Fish {}

* fields - no comment necessary

private int size;

* constructors - javadoc

/**
 * @param length - the length of the fish object to be constructed
**/
public Fish(int length) {}

* methods - javadoc (function, parameter, return type)

/**
 * @return the length of the fish
**/
public int getLength() {}

* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  
  if (A == B) {}
  
  * switch statement
  
   int month = 8;
   String monthString;
   switch (month) {
      case 1:  monthString = "January";
               break;
      case 2:  monthString = "February";
               break;
   }
  
  * while loops
  
  while (true) {}
  
  * for loops
  
  for (int i = 0; i < TABLE_SIZE; i++) {}
  
  * enhanced for loops
  
  for (int i : list) {}
