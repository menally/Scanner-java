import java.util.Scanner;
public class Main{
    public static void main (String[] args){
        Scanner scanner = new Scanner(System.in);
        System.out.println("Ingresa un numero entero:");
        int numero = scanner.nextInt();
        if (numero >= 100){
            System.out.println("---------------------");
        System.out.println("Ingresa tu calificacion del examen (0-100):");
        int calificacion = scanner.nextInt();
        if (calificacion >=60){
            System.out.println("Felicidades aprobaste");
            System.out.println("------------------------");

            System.out.println("Ingresa  un numero entero:");
            numero = scanner.nextInt();
            if (numero % 2 == 0){
                System.out.println("El numero es par");
            } else {
                System.out.println("El numeero es impar");
            }
            System.out.println("-----------------------------");

            System.out.println("Ingresa tu edad");
            int edad = scanner.nextInt();
            if (edad >= 18) {
                System.out.println("Puedes votar");
            } else {
                System.out.println("Aun no puedes votar");
            }

        }

          scanner.close();
        }
    }
    }