# fibonacci_java_code
java code for fibonacci series
import java.util.Scanner;
public class Fibonacci {

	public static void main(String[] args) {
		Scanner in = new Scanner(System.in);
		System.out.println("enter the required no of sequence");
		int n = in.nextInt();
		int a = 0 , b = 1 , c ;
		
		System.out.println(a);
		System.out.println(b);
		for (int i = 3 ; i <= n ; i++  ) {
			c = a + b ;
			System.out.println (c);
			a=b;
			b=c;
			
		}	
	}
	}
		



