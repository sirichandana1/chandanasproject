# chandanasproject
import java.io.*;
import java.lang.*;
import java.util.Scanner;


public class MERCURY {

	public static void main(String[] args) throws InterruptedException {
		int n1=0,n2=1,n3,i,a;
		Scanner sc=new Scanner(System.in);
		a=sc.nextInt();
		System.out.print(n1+" "+n2);
		for(i=2;i<a;i++)
		{
				n3=n1+n2;
				System.out.print(" "+n3);
				n1=n2;
				n2=n3;
			
		}
	return;
	}
	

