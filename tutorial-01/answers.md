# Tutorial 01 — Answers

## Part I

### Question 1: Request two numbers from the user and print the multiplication of the numbers.

import java.util.Scanner;

public class Multiplication{
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);

        System.out.print("Enter the first number:");
        double a = input.nextDouble();

        System.out.print("Enter the second number:");
        double b = input.nextDouble();

        double Product = a*b;

        System.out.print("The product of the two number is:" + Product);
    }
}

### Question 2

import java.util.Random;

public class Random{
    public class void main(String[] args){

        Random num = new Random();

        int a = num.nextInt(100);

        if(a > 50){
            System.out.print("The number " + a + " is greater than 50.")
        }
        else{
            System.out.print("The number " + a + " is not greater than 50.")
        }

    }
}

## Part II

### Question 1

Write your answer here.