# Fundamentos-De-Programaci-n
Aprender
package Ejercicio1;
import java.util.Scanner;
public class Ejercicio1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

Scanner entrada = new Scanner(System.in);
        
        System.out.print("Ingrese la base del rectángulo: ");
        double base = entrada.nextDouble();
        
        System.out.print("Ingrese la altura del rectángulo: ");
        double altura = entrada.nextDouble();
        
        double area = base * altura;
        
        System.out.println("El área del rectángulo es: " + area);
        entrada.close();
        
	}

}
