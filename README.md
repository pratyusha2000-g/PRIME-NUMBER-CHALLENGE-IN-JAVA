# PRIME-NUMBER-CHALLENGE-IN-JAVA
import java.util.Scanner;
public class Main
{
	public static void main(String[] args)
	{
	    Scanner sc=new Scanner(System.in);
	    int n,i,c=0;
		
		System.out.println("Enter a Number");
	    n=sc.nextInt();
	    for(i=2;i<=n/2;i++)
	    {
	        if(n%i==0)
	          c++;
	    }
	    if(c==0)
	    System.out.println(n+" is a prime number");
	    else
	    System.out.println(n+" is not a prime number");
	    
	}
}
