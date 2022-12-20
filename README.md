import java.util.Scanner;

public class DaireninAlani {

    public static void main(String[] args){

        Scanner input = new Scanner(System.in);

        int r;
        int aci;
        float pi = 3.14f;
        double alan;
        double cevre;
        double DilimAlan ;
        System.out.println("Dairenin Yarıçapını Giriniz");
        r = input.nextInt();
        System.out.println("Dairenin Yarıçapını Giriniz");
        aci = input.nextInt();
        alan = pi*r*r;
        cevre = 2*pi*r;
        DilimAlan = (pi*(r*r)*aci)/360;

        System.out.println("Dairenin alanı : "+alan);
        System.out.println("Dairenin Çevresi : " + cevre);
        System.out.println("Açı ölçüsü "+aci+"Derece olan daire diliminin alanı : " + DilimAlan);
    }
}
