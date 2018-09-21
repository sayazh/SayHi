# SayHi
String exercise
package stringAssignments;

import java.util.Scanner;

public class stringExercise1 {
	
	   public static void main(String[] args) {
		     Scanner scan =new Scanner(System.in);
		     System.out.println("Enter please your name");
		     String name =scan.next();
		     String str ="Hi ";
		     System.out.println(str+name+"!");
		     
		     scan.close();
		     
	}
	}

