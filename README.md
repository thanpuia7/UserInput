# UserInput
Simple program go get data from user in Java
import java.util.Scanner; class GetUser{   public static void main (String args[]) 
{      int a;     
float b;    
String s;    
Scanner in = new Scanner(System.in);      
System.out.println("Enter an integer");    
a = in.nextInt();  
System.out.println("You entered integer "+a);  
System.out.println("Enter a float");   
b = in.nextFloat();   
System.out.println("You entered float "+b);  
Scanner gt = new Scanner(System.in);    
System.out.println("Enter a string"); 
s = gt.nextLine();     
System.out.println("You entered string "+s);   
}
}
