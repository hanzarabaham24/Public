//GONZALES, HANZ ABRAHAM F.
//BSCS - 1ST YEAR
//PROGRAMMING FINALS REQUIREMENT
import java.math.BigInteger; // Importing only the necessary class from java.math to keep the code clean and efficient.
import java.util.Scanner; // Importing Scanner for user input.

public class GonzalesHanzMidtermReq {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in); // Proper use of Scanner for input, ensuring easy input handling.
        
        System.out.println("Enter the first number:"); // Clear prompt for the user.
        BigInteger num1 = scanner.nextBigInteger(); // Use of BigInteger for handling large integers, ensuring accuracy and efficiency.
        
        System.out.println("Enter the second number:"); // Clear prompt for the user.
        BigInteger num2 = scanner.nextBigInteger(); // Consistent use of BigInteger for the same reason as above.
        
        BigInteger gcd = num1.gcd(num2); // Use of BigInteger's built-in gcd method for efficiency and reliability.
        
        System.out.println("The GCD of " + num1 + " and " + num2 + " is " + gcd); // Clear output for the user.
    }
}
