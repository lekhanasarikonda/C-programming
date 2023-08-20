# C-programming
![Screenshot_6](https://github.com/lekhanasarikonda/C-programming/assets/134198650/dd7d353d-8c83-46c3-b634-ca4b477bfb10)
HISTORY OF C PROGRAMMING:
>Dennis Ritchie invented C born in 1941

>He was working at Bell organization later renamed as AT&T labs

>He was also invented operating system called as UNIX while working at Bell

>ALGOL->BPCL->B->C Language in 1972

STRUCTURE OF C PROGRAMMING:
> #include<stdio.h>   ------->pre-processor we include particular library called stdio.h it had a specific function for us it allowed us to print something on screen by using printf function

  int main()
  
  {
  
      printf("Lekhana sarikonda");
      
      return 0;
      
  }

  pre-procesiing area:
  #include<stdio.h>   -----> allowed us to print & read something on screen

  #include<math.h>    ----->Has specific mathematical function ex: 2^7  as pow(2,7) and also trignometric function

   #include<string.h> ----->stream of characters enclosed by "  ex: "Iam Lekhana"

   //Macros 

   #define pi 3.14 global value and it never ever change

   //Main function 

   #int main (){  ----> whenever we click upon run the code when its running the first thing that it look for where is my main program and then it will start the execution of the program

   //variables  ----->stores the values like int,float,double,char

   int a=10,b=20,sum;

   //statements and expressions

A program is a collection of statements.

A statement is an instruction given to the computer to perform an action.

There are three different types of statements in C:

Expression Statements

Compound Statements

Control Statements

An expression statement or simple statement consists of an expression followed by a semicolon (;).

Given below are few examples of expression statements:

a = 100;

b = 20;

c = a / b;

A compound statement also called a block, consists of several individual statements enclosed within a pair of braces { }. For example:

{
   a = 3;
   
   b = 10;
   
   c = a + b;
   
}

A single statement or a block of statements can be executed depending upon a condition using control statements like if, if-else, etc. We shall learn more about control statements in later sections.

Given below is an example of if control statement:

a = 10;

if ( a > 5) {

   b = a + 10;
   
}

   
  
