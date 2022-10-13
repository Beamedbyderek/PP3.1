
package pp.pkg3.pkg1;

/* 

10/2/2022

 Derek Durand

name and number

*/ 
import java.util.Scanner;
import java.util.Random;
public class PP31 {

   
    String lastName2;
    
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.print("First Name: ");
        String firstName = in.next();
        System.out.print("Last Name: ");
        String lastName = in.next();
        
        char firstLetter = firstName.charAt(0);
        String lastName2 = lastName.substring(0,5);
        
        System.out.println(firstLetter + " " + lastName2 + " ");
        Random rand = new Random();
        int randomNum = rand.nextInt(100)+10;
        System.out.println(randomNum);
    }
    
    
}
