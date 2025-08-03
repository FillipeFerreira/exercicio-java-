
import java.util.InputMismatchException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int habilitado = 18;
        Scanner sc = new Scanner(System.in);

        try{
         int idade = sc.nextInt();
            if (idade >= habilitado) {
                System.out.println("voce pode dirigir");
            }else {
                    System.out.println("voce nao pode dirigir ");}
            }catch (InputMismatchException e ) {
            System.out.println("letra errada");
             }finally {
            sc.close();


        }
    }
}
