# sicaklik

import java.util.Scanner;

public class havasicakligi {
    public static void main(String[] args) {
        int heat;

        Scanner input=new Scanner(System.in);
        System.out.println("Sıcaklık gırın :");
        heat=input.nextInt();

        if(heat<5){
            System.out.println("Kayak Yapabılırsınız");
        }
        else if(heat>=5 && heat<=25){
            if (heat<=15 ){
                System.out.println("Sınemaya Gıdebılırsınız");
            }
            if(heat>10 ){
                System.out.println("Pikniğe Gıdebılırsınız");
            }

        }
        else{
            System.out.println("Yüzmeye Gıdebılırsınız");
        }






    }
}
