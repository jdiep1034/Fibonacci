
/**
 * The purpose of this program is to recursively calculate the n-th Fibonacci number.
 *
 * @author Justin Diep
 * @version 4-18-18
 */
import java.util.Scanner;
public class FibonacciNumbers
{
    //Method to calculate nth Fibonacci Number
    public static int Fibonacci(int n)
    {
        if( n==0 )
        {
            return 0;
        }
        else if( n==1 )
        {
            return 1;
        }
        else if( n>1 )
        {
            return Fibonacci(n-1) + Fibonacci(n-2);
        }
        else
        {
            return 0;
        }
    }
    
    //Main Method
    public static void main(String[]args)
    {
        Scanner in = new Scanner(System.in);
        
        System.out.println("This program produces the (n)th Fibonacci number.");
        System.out.println(); 
        
        for( int i=0; i <1; i += 0)
        {
          System.out.print("Choose an integer value greater than 1 to be n (Type '0' to quit): ");
          int n = in.nextInt();
        
          int f = 0;
            
            if( n>1 )
          {
             f = Fibonacci(n);
             System.out.println("The " + n + "th Fibonacci number is: " + f);
             System.out.println();
          }
          else if( n == 0 )   //terminating input
          {
              i++;
          }
          else                //Error trap
          {
              System.out.println("Input not greater than 1. Try again.");
              System.out.println();
          }
        }
    }
}
