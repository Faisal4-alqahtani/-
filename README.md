package jjava1;
import java.util.Scanner;
public class Jjava1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		int A = input.nextInt();
			String s = input.next();
		int B = input.nextInt();
	
		int T;
		
		if(s.equals("+")) {
			T = A + B;
		}
		
		else if(s.equals("-")) {			
			T = A - B;	
		}
		else if(s.equals("*")) {
			T= A * B;
		}
		else 
		T= A / B;
		
	System.out.println(T);
	}

}
