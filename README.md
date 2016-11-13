# input-Birthday
package qu4;


  import java.util.Scanner;
 
public class QU4 {

   
    public static void main(String[] args) {
      
        Scanner console1 =new Scanner(System.in);
    System.out.print("On what day of the month were you born? ");
    int day = console1.nextInt();
        Scanner console2 =new Scanner(System.in);
    String month;
    System.out.print("What is the name of the month in which you were born? ");
    month = console2.nextLine();
        Scanner console3 =new Scanner(System.in);
    System.out.print("During what year were you born? ");
    int year = console3.nextInt();
     
    System.out.println("You were born on " + month + " " + day + ", " + year + ". You're mighty old!");
    }
}
