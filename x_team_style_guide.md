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
    * 
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

<brief statement of your team's commenting style>

### Examples

* classes
* fields
* constructors
* methods
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
  * while loops
  * for loops
  * enhanced for loops
