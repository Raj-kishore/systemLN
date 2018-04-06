# systemLN JAR file
 
 Simply import [this JAR file](https://github.com/Raj-kishore/systemLN/blob/master/systemln-raj-v2.jar?raw=true) to your project's external libraries to see the magic. 
 
## Functionality 
 It replaces System.out.print() to a minimized form i.e. o.l() and System.out.println() to o.n().

## API

    import systemln.*;
    
     //in main method
    o.l("prints string literal without a line break");
    o.n("prints string literal with a line break");
 
## Example
 
     package com.example;
 
     import systemln.*;
 
     public static void main(String[] arg){
 
         o.n("statement with a line break");
         o.l("statement without a line break");
         o.n("another statement a with line break");
 
     }
 
 
##### Developed by Raj Kishor Maharana
##### Date created - 5 Apr 2018
