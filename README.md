//Program 3
//Extension of program 2 that now asks for user input when assigning the length and width of the sides
import java.util.Scanner; //This imports the console scanner that reads user input

//Your code here:
public class Program3 {
    public static void main(String[] args){
        //make a scanner
        Scanner myScanner = new Scanner(System.in); 
        
        //create variables
        int length = 0;
        int width = 0;
        int area = 0;
        int perimeter = 0;
        
        //ask for user input
        System.out.println("Please enter the length: ");
        length = myScanner.nextInt();
        
        
        System.out.println("Please enter the width: ");
        width = myScanner.nextInt(); 
        
        System.out.println("Please enter the perimeter; "); 
        perimeter = myScanner.nextInt();
        System.out.println("Please enter the area; ");
        area = myScanner.nextInt(); 
        
        //get the input 
        
        //calculate
        area = width * length;
        perimeter= length + width + length + width; 
        //output
        System.out.println("The length is:" + length); 
        System.out.println("The width is:" + width);
        System.out.println("The perimeter is:" + perimeter); 
        System.out.println("The area is:" + area);
    }
}



//Paste console output below:
/*
Please enter the length: 
12
Please enter the width: 
42
Please enter the perimeter; 
34
Please enter the area; 
67
The length is:12
The width is:42
The perimeter is:108
The area is:504

*/
