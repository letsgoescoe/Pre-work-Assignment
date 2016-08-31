# Pre-work-Assignment
import java.util.Scanner;

public class prework {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
				
			Scanner scanner = new Scanner(System.in);
				
		System.out.println("Please enter a number to reverse : ");		

		int original = scanner.nextInt();
		int reverse = 0;
		int remainder;

		// original 542
		while(original !=0){
			
			remainder = original % 10; //2 //4 // 5
			reverse = reverse * 10 + remainder; //2 // 4 // 24 // 245
			original = original / 10; // 54 // 5 // 0
		}
		System.out.println("Your reverse of number is:" + reverse);
			}
			
		

	}
