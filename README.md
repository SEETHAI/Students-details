# Students-details
Java program to print Students details and calculate the marks
//program to get student details
import java.util.Scanner;
 
public class GetStudentDetails
{
      public static void main(String args[])
      {
          String name;
          int roll, python, java, html;
           
          Scanner SC=new Scanner(System.in);
           
          System.out.print("Enter Name: ");
          name=SC.nextLine();
          System.out.print("Enter Roll Number: ");
          roll=SC.nextInt();
          System.out.print("Enter marks in Python, Java and Html: ");
          python=SC.nextInt();
          java=SC.nextInt();
          html=SC.nextInt();
           
          int total=python+java+html;
          float perc=(float)total/300*100;
           
          System.out.println("Roll Number:" + roll +"\tName: "+name);
          System.out.println("Marks (Python, Java, Html): " +python+","+java+","+html);
          System.out.println("Total: "+total +"\tPercentage: "+perc);
            
      }
          
}
