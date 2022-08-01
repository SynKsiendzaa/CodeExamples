# Code Examples:

This file will include most popular coding languages example code.

## Included languages:
**[C++](#C++)**
**[C#](#CSharp)**
**[Python](#Python)**
**[Java](#Java)**
**[PHP](#PHP)**
**[JavaScript](#JavaScript)**
**[Batch](#Batch)**
**[Lua](#Lua)**
**[Arduino](#Arduino)**
**[JSON](#JSON)**
**[XML](#XML)**
**[Shell/Bash](#Shell/Bash)**

## C++

//Hello world code **<-- Comment**
/* **Multi line**
**Comment** */
#include <iostream>

using namespaces std;

int main()
{
    std::cout << "Hello World!";
    return 0;
}

## CSharp

namespace MyApp
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("123");
            public int number = Convert.ToInt32( Console.ReadLine() );


            // Wait before closing
            Console.ReadKey();
        }
    }
}

## Python

#Program to check if a number is prime or not **<-- Comment**

num = 29

#To take input from the user
#num = int(input("Enter a number: "))

#define a flag variable
flag = False

#prime numbers are greater than 1
if num > 1:
    # check for factors
    for i in range(2, num):
        if (num % i) == 0:
            # if factor is found, set flag to True
            flag = True
            # break out of loop
            break

#check if flag is True
if flag:
    print(num, "is not a prime number")
else:
    print(num, "is a prime number")

## Java

// Fibonacci series displayer **<-- Comment**
class Main {
  public static void main(String[] args) {

    int n = 10, firstTerm = 0, secondTerm = 1;
    System.out.println("Fibonacci Series till " + n + " terms:");

    for (int i = 1; i <= n; ++i) {
      System.out.print(firstTerm + ", ");

      // compute the next term
      int nextTerm = firstTerm + secondTerm;
      firstTerm = secondTerm;
      secondTerm = nextTerm;
    }
  }
}

## JavaScript

// program to check if the number is even or odd **<-- Comment**
// take input from the user
const number = prompt("Enter a number: ");

//check if the number is even
if(number % 2 == 0) {
    console.log("The number is even.");
}

// if the number is odd
else {
    console.log("The number is odd.");
}

## Batch

::::::::::::::::::::::::::::::::::::::::::::::::

@if (true == false) @end /*!
@echo off
mshta "about:

" %*
goto :EOF */

alert("Hello, world!");

:::::::::::::::::::::::::::::::::::::::::::::::::::

you can call it in a file like this

@echo off

cls

echo enter a password

set /p pass=

call msg

## Lua

io.write
(
"Hello world, from ",_VERSION,"!\n"
)

## Arduino

/*
  Blink

  Turns an LED on for one second, then off for one second, repeatedly.

  Most Arduinos have an on-board LED you can control. On the UNO, MEGA and ZERO
  it is attached to digital pin 13, on MKR1000 on pin 6. LED_BUILTIN is set to
  the correct LED pin independent of which board is used.
  If you want to know what pin the on-board LED is connected to on your Arduino
  model, check the Technical Specs of your board at:
  https://www.arduino.cc/en/Main/Products

  modified 8 May 2014
  by Scott Fitzgerald
  modified 2 Sep 2016
  by Arturo Guadalupi
  modified 8 Sep 2016
  by Colby Newman

  This example code is in the public domain.

  https://www.arduino.cc/en/Tutorial/BuiltInExamples/Blink
*/

// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}

## JSON

{
    "name":"John", 
    "age":30, 
    "car":null
}

## XML

<?xml version="1.0" encoding="UTF-8"?>
- <note>
  <to>Tove</to>
  <from>Jani</from>
  <heading>Reminder</heading>
  <body>Don't forget me this weekend!</body>
</note>

## Shell/Bash

#!/bin/bash

#example of using arguments to a script
echo "My first name is $1"
echo "My surname is $2"
echo "Total number of arguments is $#" 