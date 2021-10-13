import java.util.Scanner;

public class LabProgram {

	public static void main(String[] args) {

		/* Create Scanner */
		
		Scanner login = new Scanner(System.in);      // Create scanner object login


      // Define variables needed for scanner
      
      String firstName;                            // Variable to hold the first name
      String lastName;                             // Variable to hold the last name
      int fourDigitPin;                            // Four digit pin
      
      // Define variables to hold formatted text
      
      String loginName;                // Will be up to the first 5 letters of last name
      char initial;                  // Will be the first letter of first name
      int pin;                         // Will be a pin created by the user
      String userName;                 // Final username to be used by the user
      
      // Get the user input
      
      firstName = login.next();           // Get the users first name
      lastName = login.next();            // Get the users last name
      fourDigitPin = login.nextInt();     // Get the users pin 4 Digits
      
      // ====================    Lets format the text into the required format
      
      /* Check the length of the user's last name and if the name is
      *  less than 5 characters then use all of the name. 
      *  If the name is more than 5 characters than grab the first five
      * and assign it to the loginName variable
      */
      
      // loginName formatting
      if (lastName.length() < 5) {
         loginName = lastName;
      }
      else {
         loginName = lastName.substring(0,5);
      }
      
      // Grab the inital of the first name
      initial = firstName.charAt(0);
      
      // Grab the last two digits of the integer provided by the user
      pin = fourDigitPin % 100;
      
      // ==========================  Put it all together
      
      userName = loginName + initial + pin;
      
      System.out.println("Your login name: " + userName);
      
      
      
	}
}
