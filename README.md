import  java.util.Scanner;
//swapping of two number without using third verable

public class BankMainclass {

	public static void main(String[] args) {
		
	Scanner s=new Scanner(System.in);
	System.out.println("Eneter the value x and y");
	int x=s.nextInt();
	int y=s.nextInt();
	
	System.out.println("before swapping \nx="+x +"\ny= "+y);
	x=x+y;//x=2,y=1....
	y=x-y;//y=2,x=3
	
	x=x-y;//x=1
	System.out.println("after swapping \nx="+x+"\ny="+y);
	 int a=5;
	 int b=6;
	 int c;
	 System.out.println("=====using third verbal ========");
	 
	 System.out.println("before swapping \n"+"a:"+a +"\n"+"B:"+b);
	 c=a;
	 a=b;
	 b=c;
	 System.out.println("after swapping \n"+"a:"+a+"\n"+"b:"+b);
	}
 
}


