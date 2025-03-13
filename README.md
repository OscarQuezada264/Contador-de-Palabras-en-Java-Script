# Contador-de-Palabras-en-Java-Script
Este programa en Java cuenta el número de palabras en un texto ingresado por el usuario. Es un buen ejercicio para practicar el uso de arreglos y la manipulación de cadenas.
import java.util.Scanner;

public class ContadorDePalabras {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Introduce un texto:");
        String texto = scanner.nextLine();
        String[] palabras = texto.split("\\s+");
        System.out.println("Número de palabras: " + palabras.length);
        scanner.close();
    }
}
