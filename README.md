# systemLN JAR file
 
 Simply import this JAR file to your project's external libraries to see the magic. 
 
## Functionality 
 It replaces System.out.print() to the following format (See the API). 

## API
    import systemln.*;
    
     //in main method
    
    o.l(Object obj); // prints obj without a line break
    o.n(Object obj); // prints obj with a line break
 
## Example
 
     package com.example;
 
     import systemln.*;
 
     public static void main(String[] arg){
 
         o.n("statement with line break");
         o.l("statement without line break");
         o.n("another line break with line break");
 
     }
 
 

