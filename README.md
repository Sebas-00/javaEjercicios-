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




