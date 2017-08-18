# PrimosNumeros
package sesion1708;

import java.util.Scanner;


public class Primos {

    public static void main(String[] args) 
    {
        System.out.println("\t***NUMEROS PRIMOS***\n");
        int numero, c=0;
        Scanner tec= new Scanner(System.in);
        System.out.println("Ingrese el Numero a Evaluar");
        numero=tec.nextInt();
        
        for(int x=numero;x>0;x--)
        {
            if(numero%x==0)
            {
                c=c+1;                
            }
            
        }   
             if(c==2) {System.out.println("El numero "+ numero +" es Primo");}
             else     {System.out.println("El numero "+ numero +" no es Primo");}
    }
    
}
