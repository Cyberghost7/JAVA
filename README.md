# JAVA
public class Main {

public static void main(String[] args) {
System.out.println("\t\"I love pizza\"\n");
System.out.println("I also love beans!\n");
System.out.println("\"Duuuuuuude\"\n");
System.out.println("Tips");

/*
Comment part 1
*/

int a=12;

}
}

---------------------

public class Main {

public static void main(String[] args) {

int a=12; //Setting up the variable via initialization

/* Printing the variable, NOT a string so don't use quotes
For the above */

System.out.println("My number is: "+ a);
System.out.print("I am " + a + " years old now \n");

long b=1290309213209213213L;
long c=23822380243L;

System.out.println(b);
System.out.println(c);

}
}

—-----------------------------



public class Main{
    
    
public static void main(String[] args){
    
    int a=12;
    double b=3.14;
    float c=3.32f;
    long d=92042033209L;
    
    
    System.out.print("Today, I am " + a + " years old \n");
    System.out.println("Tomorrow, I will figure out the mystery of " + b + " which is Pi");
    System.out.print("Tomorrow I will program " + c + " which is a fractional number\n");
    System.out.println("Today I will finish " + d + " which finizales math operations");
    
    
    boolean z=true;
    boolean x=false;
    
    System.out.println(z);
    System.out.println(x);
    
}
    
    
    
    
}
—----------------------------------

public class Main{
    
    
public static void main(String[] args){
    
    int a=12;
    double b=3.14;
    float c=3.32f;
    long d=92042033209L;
    
    
    System.out.print("Today, I am " + a + " years old \n");
    System.out.println("Tomorrow, I will figure out the mystery of " + b + " which is Pi");
    System.out.print("Tomorrow I will program " + c + " which is a fractional number\n");
    System.out.println("Today I will finish " + d + " which finizales math operations");
    
    
  char symbol='!';
  String var="Today, I am ";
  String var2=" years old";
  
  String var3="Tomorrow, I will figure out the mystery of ";
  String var4=" which is Pi";

  
  System.out.println(var + a + var2 + symbol);
  System.out.println(var3 + b + var4 + symbol);

 String var7="bro";
  
  System.out.println("Hello my " + var7);
}

}
    
    
    
    
}
—-------------------------------------------------


public class Main{
    
    
public static void main(String[] args){
    
    String x="Water";
    String y="Kool-aid";
    
    System.out.println("x: " + x);
    System.out.println("y: " + y);
    
    
 String temp;
 
 temp=x;
 x=y;
 y=temp;
    
    
    System.out.println(x);
    System.out.println(y);
    System.out.println(temp);
}
    
    
}
—---------------------------------------

import java.util.Scanner;
 
public class Main{
 
public static void main(String[] args){
 
 
String var="Today I am ";
int age=23;
String var2=" years old";
char symbol='!';
 
System.out.println(var + age + var2 + symbol);
Scanner scanner= new Scanner(System.in);
 
System.out.println("What is your name?");
String input_name=scanner.nextLine();
 
System.out.println("hello, " + input_name);
 
 
}
}
—------------------

import java.util.Scanner;
 
public class Main{
 
    public static void main(String[] Args){
 
Scanner scanner = new Scanner(System.in);
 
 
 
System.out.println("Hello sir! What is your name?");
 
String input_name=scanner.nextLine();
 
System.out.println("And, what is your age?");
 
int input_age=scanner.nextInt();
 
System.out.println("Good, your name is " + input_name + ". And your age is " + input_age + ". Have a great day at our resort!");
 
    }
 
 
 
}
 
 
—---------------import java.util.Scanner;
 
 
public class Main{
 
    public static void main(String[] Args){
 
 
       int num=10;
 
       double num2=20;
 
       num2++;
       num2=num2/2;
 
       System.out.println(num2);
 
       double dec=10;
 
       dec=dec/2;
 
       System.out.println(dec);
 
       num++;
 
       num--;
 
       num=num*2;
 
       num=num/2;
 
       System.out.println(num);
       
 
    }
 
 
 
}
 

—--
import java.util.Scanner;
public class Main{
    public static void main(String[] args){

        Scanner scanner= new Scanner(System.in);

        System.out.println("Hello, what is your name?");

        String name=scanner.nextLine();

        System.out.println("And, what is your age?");

        int age=scanner.nextInt();

        System.out.println("Hello " + name + ": you are " + age + " years old!");



int num=2;

double num2=232.3;

long numb3=23323920329L;

System.out.println(num);

num++;

System.out.println(num);

num++;
System.out.println(num);

num--;
System.out.println(num);
num=num*1220;
System.out.println(num);


num=num/20;
System.out.println(num);
num++;
System.out.println(num);
num--;
System.out.println(num);

num++;
System.out.println(num);

num=num*10;
System.out.println(num);
num=num/20;
System.out.println(num);
num++;
System.out.println(num);

num--;
System.out.println(num);

    }
}

—----------------------------------------------------
import java.util.Scanner;
 
import java.util.Random;
 
 
public class Main{
 
public static void main(String[] args){
 
    Scanner scanner =new Scanner(System.in);
 
    String input=scanner.nextLine();
 
    System.out.println("Hello, your name is " + input);
 
Random random=new Random();
 
int rnum2=random.nextInt(100)+1;
 
double rnum3=random.nextDouble();
 
//int num=random.nextInt(100)+1;
 
//double num=random.nextDouble();
 
System.out.println(rnum2);
 
boolean ran=random.nextBoolean();
 
System.out.println(ran);
 
boolean rnum=random.nextBoolean();
 
System.out.println(rnum);
 
 
}
 
}
—---------------------------------

import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
 
 
        Random random=new Random();
 
        int num=random.nextInt(100);
 
        System.out.println(num);
    }
}
—---------------------------
public class Main{
 
    public static void main(String[] args){
 
    int age=80;
 
    if(age==80){
        System.out.println("You are super old boomer!");
    }
    else if(age>=18){
        System.out.println("You are an adult");
    }
 
    else if(age<=17){
        System.out.println("You are a teen or a child!");
    }
 
    else if(age>=75){
        System.out.println("You are  old AF!");
    }
 
    else{
        System.out.println("You don't exist!" + " Or youre old AF!");
    }
 
 
 
    }
}
—-----------

import java.util.Random;

public class Main{
    public static void main(String[] args){

        Random random=new Random();

        int num=random.nextInt(100);

        System.out.println(num);

        double num2=random.nextDouble();

        System.out.println(num2);

        boolean num3=random.nextBoolean();

        if (num==10){
            System.out.println("You have the correct answer!");
        }

        else if(num>10){

            System.out.println("You have an answer higher than the expected value");
        }

        else if(num2<=20){
            System.out.println("Your answer is not correct yet again!");
        }

        else{
            System.out.println("Your answer is wrong!");
        }
    }
}

—--------------
import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
        Random random=new Random();
 
int num=random.nextInt(100);
        System.out.println(num);
 
        if (num==10){
            System.out.println("You are out of value paramters!");
 
        }
 
        else if(num<=1){
 
            System.out.println("You are in range!");
 
        }
 
        else{
 
            System.out.println("You are out of range!");
        }
    }
}
—-----------------------
import jdk.nashorn.internal.ir.BreakableNode;
 
public class Main{
 
    public static void main(String[] args){
 
        String city="Hanoi";
 
        switch(city){
case "Saigon" : System.out.println("You are in Saigon!");
break;
 
case "BinhDuong": System.out.println("You are in Binh Duong!");
break;
 
case "PhanRanh": System.out.println("You are in Phan Ranh!");
break;
 
case "Hanoi": System.out.println("You are in Hanoi!");
break;
 
default: System.out.println("You are not in Viet Nam!");
 
 
        }
    }
}
—-------------
import java.util.Scanner;
import java.util.Random;
 
 
public class Main {
 
    public static void main(String[] args){
 
        Random random=new Random();
        Scanner scanner=new Scanner(System.in);
 
System.out.println("Enter the number now");
 
 
int num2=random.nextInt(100);
 
double num3=random.nextDouble();
 
int num=scanner.nextInt();
 
System.out.println("You have entered the number " + num);
 
if(num>num2){
System.out.println("You have entered " + num);
 
}
 
else if(num2>num){
System.out.println("the random number " + num2 + " is greater");
 
}
 
else if(num3>num){
 
   System.out.println("The random double " + num3 + " is greatest!"); 
}
 
else {
 
   System.out.println("Nothing to say!"); 
}
 
    }
    
}
 
—-----------------------------
public class Main{
 
    public static void main(String[] args){
 
String team="Bulls";
 
switch(team){
case "NBA":System.out.println("That is the correct String");
break;
 
case "Soccer": System.out.println("That is also the correct sport");
break;
 
case "Football": System.out.println("That is the correct team sport");
break;
 
case "Bulls": System.out.println("This is the correct NBA team!");
break;
 
default:System.out.println();
 
 
 
}
 
    }
}
—-----------


import java.util.Scanner;
import java.util.Random;

public class Main{

    public static void main(String[] args){

    

String name="Thomas";

switch(name){

case "Thomash" : System.out.println("This is not the correct name");
break;

case "Thomas": System.out.println("You have the correct answer! This is correct!");
break;

case "Julius": System.out.println("This is the first name!");
break;

default: System.out.println("None of the above names are correct");

}

Random random=new Random();

System.out.println("The system will generate a random integer now!");

int rnum=random.nextInt(100);

boolean r=random.nextBoolean();

System.out.println(rnum);
System.out.println(r);

Scanner scanner =new Scanner(System.in);

System.out.println("Enter the number now!");

int num2=scanner.nextInt();


int age=30;
double num=10.2;


if (age==num){
System.out.println("The age variable int is equal to the num variable int");
}
 else if(age>=num2){

System.out.println("The age varialbe is greater than or equal to num2");

 }
 else if(age<=num2){
System.out.println("The age variable is less than or equal to num2");

 }

 else {
     System.out.println("Error not within the given parameters!");
 }

    }

}
—---
import java.util.Scanner;
import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
    
 
String name="Thomas";
 
switch(name){
 
case "Thomash" : System.out.println("This is not the correct name");
break;
 
case "Thomas": System.out.println("You have the correct answer! This is correct!");
break;
 
case "Julius": System.out.println("This is the first name!");
break;
 
default: System.out.println("None of the above names are correct");
 
}
 
Random random=new Random();
 
System.out.println("The system will generate a random integer now!");
 
int rnum=random.nextInt(100);
 
boolean r=random.nextBoolean();
 
System.out.println(rnum);
System.out.println(r);
 
Scanner scanner =new Scanner(System.in);
 
System.out.println("Enter the number now!");
 
int num2=scanner.nextInt();
 
 
int age=30;
double num=10.2;
 
 
if (age==num){
System.out.println("The age variable int is equal to the num variable int");
}
 else if(age>=num2){
 
System.out.println("The age varialbe is greater than or equal to num2");
 
 }
 else if(age<=num2){
System.out.println("The age variable is less than or equal to num2");
 
 }
 
 else {
     System.out.println("Error not within the given parameters!");
 }
 
    }
 
}
—----------------------
import java.util.Scanner;
import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
Scanner scanner=new Scanner(System.in);
Random random=new Random();
 
System.out.println("Please enter your name!");
 
String name=scanner.nextLine();
 
System.out.println("Your name is " + name);
 
System.out.println("Please enter your age!");
 
int input_age=scanner.nextInt();
 
System.out.println("Your age is "+ input_age);
 
int age=34;
double num=3.14;
 
double num2=random.nextDouble();
int rnum=random.nextInt(100);
 
System.out.println(rnum);
 
System.out.println(num2);
 
if (num<=num2){
System.out.println("You are correct as num is larger than num2");
 
}
 
else if(age<input_age){
 
System.out.println("Age " + age +" is less than " + input_age);
 
}
 
else{
System.out.println("Nothing!");
 
}
 
String last="Thomas";
 
switch(last){
case "Thomsa" : System.out.println("Incorrect spelling");
break;
 
case "Julius" : System.out.println("First name");
break;
 
default : System.out.println("You haven't entered the correct last name");
 
 
 
}
 
    }
}
—----------------------
import java.util.Scanner; 
public class Main{
 
  public static void main(String[] args){
 
System.out.println("You are attempting to end the game!");
 
 
Scanner scanner=new Scanner(System.in);
 
 
System.out.println("What would you like to do? Enter 'q' or 'Q' to quit!");
 
String input=scanner.nextLine();
 
System.out.println("You have entered: " + input);
 
if(input.equals("Q") || input.equals("q")){
System.out.println("You have entered this input - " + input + " - and have thus quit the game!");
}
 
else if(!input.equals("Q") && !input.equals("Q")){
System.out.println("You have entered " + input + " and thus will continue the game!");
 
}
 
else{
System.out.println("Error, please try again");
 
}
 
 
 
  }
}


—----------------------------------------
import java.util.Scanner;
import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
        String name="Thomas";
 
        int age=34;
 
        Long age2=349403943L;
 
        double age3=3.14;
 
        Random random=new Random();
 
        double age4=random.nextDouble();
 
        System.out.println(age4);
 
String lname="Thomas";
 
if (lname.equals("Thomas") && !lname.equals("Tom")){
System.out.println("This if the first and correct if case");
 
}
 
else if(!lname.equals("Thomas")){
System.out.println("Wrong statement");
 
}
 
else{
System.out.println("Error");
 
 
}
 
        System.out.println(name);
 
        switch(lname){
case "Thomas": System.out.println("This is the switch first statement");
break;
 
default: System.out.println("This is an error");
 
 
        }
    }
}
—------------------
import java.util.Scanner; 
import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
        Scanner scanner=new Scanner(System.in);
 
        Random random=new Random();
 
        System.out.println("What is your name?");
 
        String name="";
 
        name="";
 
        name=scanner.nextLine();
 
        while(!name.equals("Thomas") || name.isBlank()){
System.out.println("Please try again!");
 
name=scanner.nextLine();
 
        }
 
int age=34;
 
age=age++;
 
age=age*10;
 
int num=random.nextInt(100);
 
System.out.println(num);
 
    // for loop is for a limited amonut of times
 
    // 3 parts to a for loop
 
    for(int i=0; i<10; i++){
System.out.println("The number " + i + " is still not 10 yet!");
 
    }
    
    /* as long as the middle statement is true, the loop will continue
    until it is no longer true */
 
    for(int i=34; i>=2; i--){
System.out.println("The number " + i + " is still not 2!");
 
    }
 
 
    }
}
—-------------------

import java.util.Scanner; 
import java.util.Random; 
 
public class Main{
 
    public static void main(String[] args){
 
String name="";
 
Scanner scanner=new Scanner(System.in);
Random random=new Random();
 
System.out.println("Please enter the correct number of columns and then rows now");
 
int row;
int column;
 
 
row=scanner.nextInt();
System.out.println("You have entered " + row + " number of rows");
column=scanner.nextInt();
System.out.println("You have entered " + column + " number of columns");
 
 
int limit=100;
 
if(row<=limit){
 
System.out.println("Please continue to fill the table!");
    
for(int i=0; i<row; i++){
row=row-1;
 for(int j=0; j<column; j++){
column=column-1;
 }
 
 System.out.println(column);
 System.out.println(row);
 
    } 
 
}
 
    else{
        System.out.println("Error - table is not complete");
    }
 
    System.out.println("Please enter the correct table name!");
 
    name=scanner.next();
 
    System.out.println("You entered " + name + " as the table name");
 
    
 
}
 
 
 
    }
 

—---------------


import java.util.Scanner; 
import java.util.Random; 
import java.util.ArrayList; 
 
public class Main{
 
    public static void main(String[] args){
 
// Array is a basic data structure to store multiple values
 
String[] cars={"BMW", "Merceds", "Camero", "Audii", "Viper Dodge", "Tesla"};
 
cars[4]="Dodge Viper";
 
System.out.println(cars[4]);
 
 
String[] games={"Werewolf", "Poker", "Rummy", "Canasta"};
 
System.out.println(games[3]);
 
 
String[] days= new String[4];
String[] time=new String[4];
 
time[0]="noon";
 
days[0]="Monday";
days[1]="Tuesday";
days[2]="Wedensday";
days[3]="Thursday";
 
 
System.out.println(days[3]);
System.out.println(time[0]);
 
for(int i=0; i<days.length; i++){
System.out.println(days[i]);
 
 
 
}
 
Boolean a=false;
Integer b=45;
Double c=3.14;
Boolean ab=true;
Character d='!';
 
// Wrapper classes/reference data types allow for access of powerful methods
 
//Array List allows for resizable arrays - only store reference data types
 
ArrayList<String> food= new ArrayList<String>();
 
food.add("pizza");
food.add("rice");
food.add("hotdog");
 
/* 
food.set(0, "sushi");
food.remove(2);
food.clear();
*/
 
for(int i=0; i<food.size(); i++){
System.out.println(food.get(i));
}
 
 
}
 
 
    }
 
—------

import java.util.Scanner; 
 
import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
       Scanner scanner=new Scanner(System.in);
       Random random=new Random();
 
       String name;
int age;
int num;
 
int num2=random.nextInt(100);
System.out.println(num2);
 
 
System.out.println("Please enter the name now!");
       name=scanner.nextLine();
       System.out.println("You have entered: " + name + " - as the name!");
 
 
age=random.nextInt(100);
System.out.println("The System has chosen the random number - " + age);
 
 
       while(!name.equals("Thomas") || name.equals("thomas") || name.isBlank()){
           System.out.println("The name is " + name + ". Please try again!");
           name=scanner.nextLine();
 
       }
System.out.println("Enter the value for num now!");
       num=scanner.nextInt();
 
 
       for(int i=0; i<age; i++){
        if (num<10){
age=age-1;
System.out.println("The value equals " + age);
        }
 
        else{
            System.out.println("The value entered - " + num + " is too large! Enter a new value now!");
            num=scanner.nextInt();
            System.out.println(num + " is the new value!");
 
        }
 
System.out.println("The number " + num2 + " is increasing in value!");
num2++;
num2=num2-9;
num2--;
num2=num2*100;
 
System.out.println(num2 + " is the final value!");
 
 
       }
 
       if(age<100){
System.out.println("The value for age - " + age + " - is finally less than 100");
    }
 
    else if(age==100){
System.out.println("The value for age is equal to 100");
 
    }
 
    else{
System.out.println("Error in the age value");
 
    }
 
    switch(name){
case "Thomash": System.out.println("Wrong name: " + name);
break;
 
case "Tom": System.out.println("Wrong name again: " + name);
break;
 
default: System.out.println("What name did you enter? You entered " + name);
 
    }
}
}
—-----------------------

import java.util.Scanner;
import java.util.Random;
 
public class Main{
 
    public static void main(String[] args){
 
Scanner scanner=new Scanner(System.in);
Random random=new Random();
 
System.out.println("Generate the total number of rows and column limits via the system");
 
int limit=random.nextInt(100);
 
System.out.println("The sys has entered " + limit + " as the value limit!");
 
int rows;
int columns;
String symbol;
 
System.out.println("Enter the # of rows!");
rows=scanner.nextInt();
System.out.println("You entered " + rows + " as the number of rows");
 
System.out.println("Enter the # of columns!");
columns=scanner.nextInt();
System.out.println("You have entered " + columns + " as the number of columns");
 
System.out.println("Enter the symbol now!");
symbol=scanner.next();
System.out.println("The symbol is " + symbol + "!");
 
System.out.println("Enter 'Q' to quit or 'C' to continue!");
String decision=scanner.next();
 
if(decision.equals("Q") || decision.equals("q")){
System.out.println("Understood, program is quitting!");
}
 
else if(decision.equals("C") || decision.equals("c")){
    System.out.println("Continuing program!");
 
if(limit>=30){
System.out.println("Error, limit is too large - try again!");
limit=scanner.nextInt();
System.out.println(limit + " is the value limit!");
 
for(int i=0; i<=rows; i++){
System.out.println();
   for(int j=0; j<=columns; j++){
    System.out.println(symbol);
   }
 
}
 
}
 
else{
 
System.out.println("Continuing program!");
 
for(int i=0; i<=rows; i++){
    System.out.println();
       for(int j=0; j<=columns; j++){
        System.out.println(symbol);
       }
    
    }
 
}
}
 
 
 
else{
 
    while(!decision.equals("C") || !decision.equals("c") || !decision.equals("q") || !decision.equals("Q") || decision.isBlank()){
        System.out.println("Error, try again!");
        decision=scanner.nextLine();
         System.out.println("You entered " + decision);
}
 
}
 
 
 
 
    }
}

