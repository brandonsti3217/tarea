nuevo repositorio
import java.util.Scanner;
public class App {
    public static void main(String[] args) throws Exception {
        Scanner sc = new Scanner(System.in);
        String nombre = "";
        System.out.print("Ingrese su nombre");
        nombre= sc.nextLine();
        System.out.println("");
        char letra = nombre.charAt(0);
        char letra1 = nombre.charAt(1);
        char letra2 = nombre.charAt(2);
        char char1= 'a';
        char char2= 'e';
        char char3= 'i';
        char char4= 'o';
        char char5= 'u';
        if ( letra == char1 || letra == char2 ){
            System.out.print(nombre);
        } else if (letra == char3 || letra == char4 ){
            System.out.print("ADSI2020");
        } else if(letra == char5){
            System.out.print( letra1);
            System.out.print( letra2);System.out.preint(nombre:)cambiarelcodigoestamal
        }

    }
}
