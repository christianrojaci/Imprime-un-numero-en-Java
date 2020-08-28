# Imprime-un-numero-en-Java
Ciclo for para imprimir consecutivamente un numero en java
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package primerosnumeros3;

import java.util.Scanner;

/**
 *
 * @author christian
 */
public class Primerosnumeros3 { //Inicio de la clase

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) { // Inicio del metodo
        // TODO code application logic here
        Scanner scanner = new Scanner(System.in); //Objeto que Guarda la variable Scanner
        System.out.print("Canture un Numero:"); //Imprime en consola Capture Numero
        int n = scanner.nextInt(); // funcion para capturar un numero
        for(int i=1; i<=n; i++) // ciclo para imprimir el numero las veces que se capturo
        {
            System.out.println(i); // Imprime la secuencia de los nuemeros
        }
    } // fin del metodo
    
} // fin de la clase
