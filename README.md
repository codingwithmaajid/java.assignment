# Prime Number Checker (Java)

## 📖 Description
This is a simple Java program that checks whether a given number is **prime or not**.  
Currently, the program identifies whether the number is **even** or **odd**.  
You can extend it further to perform a full prime number check.

---

## 🛠 Features
- Prompts the user to enter a number.
- Displays whether the number is **even** or **odd**.
- Can be modified to check for primality.

---

## 📂 Project Structure
```java
//This is a program  to check whether a number is prime or not

import java.util.Scanner;


class Main {
    public static void main(String[] args) {
        
        System.out.println("<<<< This is a program  to check whether a number is prime or not >>>> ");
        // Asking for  the input 
        System.out.println("<Enter the number to check>: ");
         
        //Creating Scanner Object
        Scanner banana = new Scanner(System.in);
        
        int number = banana.nextInt();
        
        if(number%2==0){
         System.out.println("it is an even number ");
       
        } 
         else{
            System.out.println("it is a odd number");
             
        }
    
    
