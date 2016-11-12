#Factorial

import java.util.Scanner;

public class Activity {

    public static void main(String[] args) {
        
        Scanner input=new Scanner(System.in);
        int factorial;
        
        System.out.println("introduzca un numero para sacar el vectorial");
                factorial= input.nextInt();
        
        
                
                while(factorial<0){
                
                    System.out.println("ERROR, INTRODUZCA UN NUMERO POSITIVO");
                    System.out.println("Introduce un numero positivo");
                                    factorial= input.nextInt();
                }
        
            int factorial2 = 1;    
        for (int i = 1; i<=factorial; i++) 
        {
            factorial2= factorial2*i;
            
            
        }
        
        System.out.println("factorial de "+factorial+" : "+factorial2);
        
                
    
        
    
    
    
    }
        }
