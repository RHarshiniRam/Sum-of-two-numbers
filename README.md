# Sum-of-two-numbers
Print sum of two numbers
import java.util.Scanner;
public class Sum
{
  public static void main(String [] args)
  {
    int x,y,sum;
    Scanner sc=new Scanner(System.in)
    System.out.println("Enter a number 1:");
    x=sc.nextInt();
    System.out.println("Enter a number 2:");
    y=sc.nextInt();
    sum=x+y;
    System.out.println("Sum of two numbers:"+sum);
    }
 }
