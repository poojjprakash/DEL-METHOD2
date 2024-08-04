import java.util.Arrays;
import java.util.Scanner;
public class Main
{
    
	public static void main(String[] args) {
	    int i;
	     Scanner s = new Scanner(System.in);
	    int a3[]=new int[5];
	    int b[]= new int[a3.length-1];
	    System.out.println("enter the nos: ");
	    for(i=0;i<a3.length;i++){
	    a3[i]=s.nextInt();
	    }
	    
	    System.out.println("Enter the index u want to del???");
	    int index=s.nextInt();
	    
	    if(index<=a3.length-1){
	    for(i=0;i<a3.length-1;i++)
	    {
	        if(i>=index)
	        {
	           b[i]=a3[i+1];
	        }
	        else
	        {
	             b[i]=a3[i];
	        }
	           }
	    }
	    else
	    System.out.println("invalid index");
 	 
 	System.out.println("after deleted............");
 	for( i=0;i<b.length;i++)
 	System.out.println(b[i]);
 	
 	
			
	}
}
