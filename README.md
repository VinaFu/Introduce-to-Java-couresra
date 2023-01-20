# Introduce-to-Java-couresra

[Benefits]

    WORA = Write Once Run Anywhere
  
[Process]

    JVM = Java Vitual Machine
    JRE = Java Runtime Environment

    Java Source File -> JVM - compiler -> intermediate format -> JRE -> native code
  
[Packages]

    . to separate
    primitives/ built-in types: non-object types 
      // int, float, double
    JCP = Java Community Process
      // API
    JDBC = Java Database Connectivity
      // java.sql
    comment:
        //
        /* ... */
        /**
        *
        */
    
[Editions]
 
    Java created by Sun; similar to C/C++

    Java Standard Edition(SE)
      JRE + JVM; code library
    Java Enterprise Edition(EE)
      specific server, i.e. web server
    Java Micro Edition(ME)
      Blue-Ray; Android; seldom
  
[Syntax & Datatypes]

    1 public class
    naming: camelCase; NOT start with num.
    primatives: byte, short, int, long, float, double, boolean, char
        // double: is a double-precision 64-bit IEEE 754 floating point. ????
    
    String[] car;
    String[] pets = {"dog", "cat", "bird"};
    int[0] = new int[12]
    
    Wrapper class:
    
        |Primitive type	|   Wrapper class|
            boolean	    |   Boolean
            byte	    |   Byte
            char	    |   Character
            float	    |   Float
            int	        |   Integer
            long	    |   Long
            short	    |   Short
            double	    |   Double
    
    Autoboxing: automatic conversion the Java compiler makes between primitive types and corresponding object wrapped classes
        // encapsulation
    Array: a grouping of primitives or objects with the same name. like "pets" above.
    Java 8 Javadocs: (https://docs.oracle.com/javase/8/docs/api/)
    
[Operators]

        1. Assignment:     =
        2. Mathematical:   +, -, *, /, %
            // %: modulus - 10 % 4 = 2; reminder; %10 as the last digit
        3. Unary 一元的:    ++, --  
            // ++i: prefix increment - 先+i， 再用
               i++: postfix increment - 先用i，再+
               --i:
               i--:
        4. Relational:     >, <, ==, >=, <=, !=
        5. Logical:        &&, ||, !
        6. Logical & Bitwise 按位:   <<, >>, >>>, |, &
            // ｜ = or; & = satisfy at the same time; 
        
    
