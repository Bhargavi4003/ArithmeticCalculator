# ArithmeticCalculator
package Mypackage;
import java.util.Scanner;

public class ArithmeticOperations {

	public static void main(String[] args) 
	{
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the Two Numbers :");
		int firstnum = sc.nextInt();
		int secondnum = sc.nextInt();
		System.out.println("Enter the Operator : ");
		char op = sc.next().charAt(0);
		double Ans = 0;

		switch (op) 
		{
		case '+':
			Ans = firstnum + secondnum;
			break;
		case '-':
			Ans = firstnum - secondnum;
			break;
		case '*':
			Ans = firstnum * secondnum;
			break;
		case '/':
			Ans = firstnum / secondnum;
			break;
		}
		System.out.println("Solution : " + Ans);
	}

}
