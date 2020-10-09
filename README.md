# main1
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class main {
    public static void main(String[] args) {
        Scanner leer = new Scanner(System.in);
        List Lista = new ArrayList(10);


        for (int i = 0; i <10 ; i++) {
            double valor =1;
            System.out.println("Ingresa los valores a la lista");
            valor = leer.nextDouble();
            Lista.add(valor);
        }



        for (int i = 0; i <3 ; i++) {
            int rango;
            System.out.println("Ingresa la posiciones que quieres sumar");
            rango = leer.nextInt();
            Lista.get(rango);
        }


    }
}
