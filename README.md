# Triangle-and parameter program 
import java.util.*;

class traingle

{ public static void main(String[] args) { Scanner sc= new Scanner(System.in); double h,b,area; int a,bl,c,p; System.out.println("Enter the h and b value"); h=sc.nextDouble(); b=sc.nextDouble(); System.out.println("Enter the value of a,b,c");

    a=sc.nextInt();
    
    bl=sc.nextInt();
    
    c=sc.nextInt();
    
    p=a+bl+c;
    
    area=h*b/2;
    
    System.out.println("Area "+area+"Perimeter "+p);
    
}
}
