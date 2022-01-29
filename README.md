# Prime-or-not
import java.util.Scanner;
public class Prime {
	public static void main(String[] args) {
		int flag=0,i;
		System.out.println("Enter a value:");
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		if(n==1)
		{
			System.out.println(n+" is a neither prime nor composite number");	
		}
        for(i=2;i<n;i++)
        { if(n%i==0)
          { flag=1;
          }  
	    }
        if(flag==1)
        { System.out.println(n+" is a not prime number");
        }
        else
        { System.out.println(n+" is a prime number");
        }
  }

