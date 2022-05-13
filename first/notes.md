# important
- single quotes (`' '`) are NOT interchangeable with double quotes (`" "`) in Java!
- When running a java (jvm-compiled) file named `test`, you CANNOT use `java ./test`; you must use:
```java
java test
```

- Java is case-sensitive

# Comments in Java
- single-line: 
```java
// Here's the comment!
```

- multi-line:
```java
/* This does not run because it's commented out
System.out.println("Hello world!") */
```

- Documentation comment:
```java
/** This is the doc comment.
This section will not be compiled either. */
```

# class names
It is recommended to begin class names with capital letters.

```java
class MyJavaProgram    // valid syntax
class 1Program         // invalid syntax
class My1Program       // valid syntax
class $Program         // valid syntax, but discouraged
class My$Program       // valid syntax, but discouraged (inner class Program inside the class My)
class myJavaProgram    // valid syntax, but discouraged
```

# method names
It is recommended to begin method names with lowercase letters.
```java
public void employeeRecords() // valid syntax
public void EmployeeRecords() // valid syntax, but discouraged
```

# Identifiers in java

Identifiers are the names of local variables, instance and class variables, labels, but also the names for classes, packages, modules and methods. 
All Unicode characters are valid, not just the ASCII subset. 

- All identifiers can begin with a letter, a currency symbol or an underscore (\_). According to the convention, a letter should be lower case for variables.

- The first character of identifiers can be followed by any combination of letters, digits, currency symbols and the underscore. 
- The underscore is not recommended for the names of variables. 
- Constants (static final attributes and enums) should be in all Uppercase letters.

- Most importantly identifiers are case-sensitive.

- A keyword cannot be used as an identifier since it is a reserved word and has some special meaning.


```java
Legal identifiers: MinNumber, total, ak74, hello_world, $amount, _under_value
Illegal identifiers: 74ak, -amount
```

Keywords or Reserved words are the words in a language that are used for some internal process or represent some predefined actions.
These words are therefore not allowed to use as variable names or objects.

| ---       | ---          | ---      | ---        |
| abstract	| assert	     | boolean	| break      |
| byte	    | case	       | catch    |	char       |
| class	    | const	       | continue |	default    |
| do	      | double       | else	    | enum       |
| extends	  | final	       | finally	| float      |
| for	      | goto	       | if	      | implements | 
| import    | instanceof   | int	    | interface  | 
| long	    | native	     | new	    | package    |
| private	  | protected	   | public	  | return     |
| short	    | static	     | strictfp	| super      |
| switch	  | synchronized | this	    | throw      |
| throws	  | transient	   | try	    | void       |
| volatile	| while        |          |            | 

# Data types
In Java, variables must be one of the following types:

+ `String`: stores text, such as "Hello". String values are surrounded by double quotes
+ `int`: stores integers (whole numbers), without decimals, such as 123 or -123
+ `float`: stores floating point numbers, with decimals, such as 19.99 or -19.99
+ `char`: stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
+ `boolean`: stores values with two states: true or false

