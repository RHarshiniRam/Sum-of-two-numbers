# Sum-of-two-numbers
Print sum of two numbers
import java.util.Scanner;
public class Sumofnumbers
{
  public static void main(String [] args)
  {
    int num1,num2,sum;
    Scanner sc=new Scanner(System.in)
    System.out.println("Enter a number 1:");
    num1=sc.nextInt();
    System.out.println("Enter a number 2:");
    num2=sc.nextInt();
    sum=num1+num2;
    System.out.println("Sum of two numbers:"+sum);
    }
 }
