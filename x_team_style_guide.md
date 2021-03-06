 # X-Team 17 Style Guide

We are looking to create discriptive names for all aspects of our programs, following conventions listed below. This style guide is built off of the CS300 Style Guide
## Naming conventions

All names and variables describe what they are used for following convention listed below

### Examples
* interfaces - the variable name should start a UPPER case alphabet and the consequent words should be seperated using an UPPER case alphabet. For instance, BinaryTreeInterface;
* classes - the identifier name should start an UPPER case alphabet and the consequent words should be seperated using an UPPER case alphabet. For example, AVLTree;
* exception types - the variable name should start an UPPER case alphabet and the consequent words should be seperated using an UPPER case alphabet. For instance, ExampleException; 
* fields - the identifier name should start with a LOWER case alphabet and the consequent words should be seperated using an UPPER case alphabet. Like, variableName. One field per line;
* methods - the variable name should start with a LOWER case alphabet and the consequent words should be seperated using an UPPER case alphabet. Like, methodExample();
* parameters - same as fields. 
* local variables - same as fields. 
* instance constants - same as fields.  
* class constants - same as fields but must be either private or protected. 

## Commenting style for public and private members of a class or interface:

All comments follow the following conventions for each example listed below.

### Examples

* classes - Include JavaDoc comments for each class briefly explaining what the purpose of the class is.
* fields - Add inline comments for fields giving a brief explanation of the field and its purpose.
* constructors - Include JavaDoc comments for constructors to explain what is being constructed and its purpose.
* methods - Include JavaDoc comments for each method as well as block tags for things such as parameters, returns, throws, etc.
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements - the operators and the conditions must be seperated by a space.
  For instance, 
  
                if(var == 1 && flag != true)
    If a statement extends to more than 100 character, use the next line and use an operator to start the second line.
    Like, 
    instead of  
                 
                 if(var == 1 && flag != true || randomVar != null && proj != null && obj.val == false)
    go for, 
    
                   if(var == 1 && flag != true || randomVar != null 
                           && proj != null && obj.val == false)
  * switch statement -- > cases must be on seperate lines. 
  * while loops
  * for loops
  * enhanced for loops
  
  Use brackets and vertical spacing for all of these, even if it is not needed. Brackets should be on the same line as the if     statements/method names/for loops etc. and have a space separating them from the character to their left. For example:
      
      if (x == 0) {
         x == 1; 
      }   
 * Spaces:
        Using tabs instead of spaces
        A vertical space --> after the method and before the doc comment
                         --> after the doc comment and before beginning a new method
        
  
