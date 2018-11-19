# Week2_CST105_ProgrammingExercise2Integer_Erica_Walters
/* Use a srandomly selected 5-digit Integer from the User
 * Based on Input received the program will perform a calulation of the 5 digits
 * The result will be the division of the first 2 digits, the percentage of the third gigit and the division of the last 2 digits
 * The resultant number of the entir calculatio will be random
 */

/** Program: Five Digit Integer
 * File: FiveDigitInteger.java
 * Summary: This program sums up 5 digit integers to a total number. For example 19091 equals 20.
 * Author: Erica Walters
 * Date: November 18, 2018
 */
import java.util.Scanner;

public class FiveDigitInteger {
    //create a scanner
    private static Scanner in = new Scanner(System.in);
    public static void main(String [] args) {
        
        // enter 5 digit integet number
        System.out.print("Enter 5 random numbers ");
        
        //Compute the sum of the 5 numbers
        int input = in.nextInt();
        int sum = 0;
        while (input>0) {
            int add = input % 10;
            sum = sum + add;
            input = input / 10;}
        System.out.println(sum);
 
        }
    
}
