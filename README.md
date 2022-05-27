# YildizlarlaElmasYapma

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print("Bir Sayi Giriniz: ");
        int number = input.nextInt();

        for (int i=1;i<=6;i++){
            for (int k=1;k<=(number-i);k++){
                System.out.print(" ");
            }
           for (int j=1; j<=(2*i)-1;j++){
               System.out.print("*");
           }
            System.out.println();
        }
        for (int i=6; i>0;i--){
            for (int k=1;k<=(number-i);k++){
                System.out.print(" ");
            }
            for (int j=1; j<=(2*i)-1;j++){
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
