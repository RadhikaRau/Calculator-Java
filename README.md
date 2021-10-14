# Calculator-Java
import java.util.Scanner;

public class BasicCalculator {

	public static void main(String[] args) {
		
		BasicCalculator B = new BasicCalculator();
		try (Scanner scan = new Scanner(System.in)){
		System.out.println("Input");
		int a =scan.nextInt();
		System.out.println("Input");
		int b =scan.nextInt();
		B.Addition(a, b);
		B.Subtraction(a,b);
		B.Multilpication(a,b);
		B.Division(a,b);
		}
	}
	
		// TODO Auto-generated method stub
		
		void Addition(int a, int b)
		{
			System.out.println(" Addition operation: "+ (a+b));
		}
		void Subtraction(int a, int b)
		{
			System.out.println(" Subtraction operation: "+ (a-b));
		}
		void Multilpication(int a, int b)
		{
			System.out.println(" Multilpication operation: "+ (a*b));
		}
		void Division(int a, int b)
		{
			System.out.println(" Division operation: "+ (a/b));
		
		}

	
		

	}


