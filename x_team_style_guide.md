# X-Team NN Style Guide

The style guide seves as a standard for writing consistant, professional quality code.

## Naming conventions

Our naming conventions are fairly standard for java development, and reflect the naming standards used in Java itself. 
Descriptive names should be chosen to improve code clarity

### Examples
* interfaces
    * Should start with uppercase letter and give a sense of the purpose of the interface.
    * Eg. SearchTreeADT, Runnable, Comparable, Sortable, etc. 
* classes
    * Should start with uppercase letter and be a noun.
    * Eg. BinarySearchTree, Car, etc.
* exception types
    * Name should give a understanding of the cause and start with uppercase.  Must end with Exception.
    * Eg. DuplicateKeyException, UnknownTypeException, IntegerSizeException, etc.
* fields
    * Name should be lowercase and relate to the name and purpose of the class.
    * Eg. (In a class named "Student"): name, graduationYear, gradePointAverage, etc.
* methods
    * Method names should begin with a verb and be in camel case. Name should reasonably describe the functionality of the method.
    * Eg. setKey(), addInteger(), buildSnowman(), etc.
* parameters
    * Parameter names should give the caller of the method an idea of what needs to be passed into the method. Camel case.
    * Eg. name, parentNode, etc.
* local variables
    * Local variable names should be descriptive of the purpose of the variable, and in camel case.
    * Eg. parentNode, largestChild, etc.
* instance constants
    * instance constants should be uppercase, and any spaces should be replaced with an underscore. Names should be descriptive.
    * Eg. MAX_VALUE, FILE_NAME, etc.
* class constants
    * Class constants should follow the same standards of instance constants.

## Commenting style for public and private members of a class or interface:

Our comments are aimed at improving the readability and maintainability of code by explaining key points of functionality

### Examples

* classes
    * Class level comments will describe the high level functionality of the class.
* fields
    * Feild comments will describe the purpose of the field.
* constructors
    * Constructor comments will contain at a minimum a summary of the purpose, as well as descriptions of every parameter.
```
/**
 * This constructor initializes the Treenode with the provided key.
 *
 * @param key the key for the treenode
 */
```
* methods
    * Method comments will contain at a minimum a summary of the purpose, as well as descriptions of every parameter and return value.
```
/**
 * The lookup method performs a binary search to find the key provided.
 *
 * @param key the key to be searched for.
 * @return 
 */
```
* inline comments
    * Inline comments will be used as needed to clarify code and explain high level functionality points.
    
## Coding style
* if statements
    * Brackets
        * Opening brackets will be on the line of the if statement, and closing brackets wil be aligned with the begining of if statement
    * Spacing
        * If statements will have a space between if and () as well as between () and {. Contents of if statement will be indented 4 spaces
* switch statement
    * Brackets
        * 
    * Spacing
        * 
* while loops
    * Same as if statement
* for loops
    * Same as if statement
* enhanced for loops
    * same as if statement
