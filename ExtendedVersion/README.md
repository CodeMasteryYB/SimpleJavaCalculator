# Extended Version

This folder contains the extended version of the calculator.

<img src="/ExtendedVersion/Images/Result.jpg" width="60%">

Check the src folder for the solution

Changes from the previous version:
1) Added the *CE* button:
   - Clear the curent value inside the text field

2) Added the *del* button:
   - Delete the last character inside the text field
   - Use the *substring* and *length* functions:
```java
public String substring (int beginIndex, int endIndex);

//Example:
String s1 = "String";
int sLen = s1.length();  // <- 6
String s2 = s1.substring(0, 2); // <- Str
String s3 = s1.substring(1, 3); // <- tri
```
3) Added the *sqrt* and *x^2* buttons:
   - Use *Math.sqrt* to compute the square root
```java
public static double sqrt(double a)
        
//Example:
double d1 = Math.sqrt(4) // <- 2
double d2 = Math.sqrt(2) // <- 1.4142135623...
```