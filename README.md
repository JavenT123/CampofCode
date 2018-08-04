# CampofCode
Javen Turner
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package firstcodeproject;
import java.util.Scanner;
/**
 *
 * @author dapcep
 */
public class Firstcodeproject {

    public static void main(String args[]) {

        System.out.println("Enter a string: ");
        Scanner input = new Scanner(System.in);;
        String variableString;
        variableString = input.nextLine();
        System.out.println("You have entered: ");
        System.out.println(variableString);
        
        
        isPositive();

    }        
    
    public static void isPositive() {
        int number = 10;
        if(number > 0)
        {
            System.out.println("number is postive");
        }
        else if (number < 0) {
            System.out.println("number is Negative");
        }
    }
    

}

