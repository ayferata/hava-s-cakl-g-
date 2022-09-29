# hava-s-cakl-g-
import java.util.Scanner;
public class Main {
    public static void main (String []args) {
       int heat;

       Scanner input= new Scanner(System.in);
        System.out.println("sıcaklık giriniz: ");
        heat= input.nextInt();

        if (heat<5){
            System.out.println("kayak yapabilirsiniz");
        } else if (heat<=25) {
            if (heat <= 15) {
                System.out.println("sinemaya gidebilirsiniz");
            }
            if (heat >= 10) {
                System.out.println("pikniğe gidebilirsiniz");
            }
        }else {
            System.out.println("yüzmeye gidebilirsiniz");
            

        }

    }
    }
