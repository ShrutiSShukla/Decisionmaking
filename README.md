# Decisionmaking
if-else
import java.util.Scanner;
public class DecisionMaking 
{
    public static void main(String[] args) 
    {
      int input;
      System.out.println("Please Enter Your Age: ");
      Scanner sc= new Scanner(System.in);
      input=sc.nextInt();
      if(input>18)
      System.out.println("You are eligible to vote!!");
      else if (input>20)
      System.out.println("You are major");
      else
      System.out.println("You are Not a major");  
    }
    
}
