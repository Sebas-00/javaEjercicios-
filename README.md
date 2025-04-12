# javaEjercicios-
 // EJERCICIO 1 


import java.util.Scanner;
class Main {
    public static void main(String[] args) {
     
     double numero1;
     double numero2;
     
      
      Scanner sc = new Scanner(System.in);
      
      System.out.print("Ingresa el primer numero:");
      numero1 = sc.nextDouble();
      
      System.out.print("Ingresa el segundo numero:"); 
      numero2 = sc.nextDouble(); 
      
       
       
        System.out.println("La suma es:" + (numero1 + numero2)); 
        System.out.println("La resta es:" + (numero1 - numero2)); 
        System.out.println("La multiplicacion es:" + (numero1 * numero2)); 
        System.out.println("La division es:" + (numero1 / numero2)); 
        System.out.println("El modulo es:" + (numero1 % numero2)); 
            
      }
}



//EJERCICIO 2

import java.util.Scanner;

class Main {
    public static void main(String[] args) {
         

     Scanner sc = new Scanner (System.in);
    String nombre, edad, correo_personal; 
     
     
     System.out.print("Por favor escribe tu nombre:");
     nombre = sc.nextLine();
     System.out.print("Por favor ingresa tu edad:");
     edad = sc.nextLine();
     System.out.print("Por ultimo ingresa tu correo personal: "); 
     correo_personal  = sc.nextLine();
     
       
    System.out.println("su nombre es:" + nombre);
    
    
    System.out.println("su edad es:"+ edad);
    
    
    System.out.println("su correo personal es:"  + correo_personal);
      
      
      
      
      }
      
    } 


//EJERCICIO 3 

   import java.util.Scanner;
public class ejercicioTres {
    public static void main(String[] args) {
   
   
        int numIngresado;
        double numA;
        double numB;
        double radio;
        double base;
        double altura;
        double baseA;
        double alturaB;
        Scanner sc = new Scanner(System.in);

      
        System.out.println("a que deseas encontrarle el area? ");
        System.out.println("1. circulo ");
        System.out.println("2. rectangulo ");
        System.out.println("3. triangulo");
        
        numIngresado = sc.nextInt();
        
        switch (numIngresado) {
            
            case 1:
                System.out.print("ingresa el radio del circulo; ");
                numA = sc.nextDouble();
                radio = numA;
                System.out.print("el area del circulo es: " + (numA * 3.1416));
                break;
                 
                 
                 case 2:
                System.out.print("ingresa la base del rectangulo; ");
                numA = sc.nextDouble();
                base = numA;
                
                System.out.print("ingresa la altura del rectangulo; ");
                numB = sc.nextDouble();
                altura = numB;
                
                System.out.print("el area del rectangulo es: " + (numA * numB));
                break;
                
                
                  case 3:
                System.out.print("ingresa la base del triangulo; ");
                numA = sc.nextDouble();
                baseA = numA;
                
                System.out.print("ingresa la altura del triangulo; ");
                numB = sc.nextDouble();
                alturaB = numB;
                
                System.out.print("el area del triangulo es: " + (numA * numB / 2));
                break;
                
                
       
        }  
    }
}  
     

















