# dairealanhesaplama
 java ile daire alanı hesaplama
```
import java.util.Scanner;
public class main {

    public static void main(String[] args) {
        /*
        Dairenin Alanını ve Çevresini Hesaplayan Program
Java ile yarı çapını kullanıcıdan aldığınız dairenin alanını ve çevresini hesaplayan programı yazın.
Alan Formülü : π * r * r;
Çevre Formülü : 2 * π * r;
Ödev
Yarıçapı r, merkez açısının ölçüsü 𝛼 olan daire diliminin alanı bulan programı yazınız.
𝜋 sayısını = 3.14 alınız.
Formül : (𝜋 * (r*r) * 𝛼) / 360
         */
        double r,a,𝜋= 3.14,alan;
        Scanner daire = new Scanner(System.in);
        System.out.print("Yari Capi Giriniz: ");
        r = daire.nextDouble();
        System.out.print("Daire Alani Giriniz: ");
        a = daire.nextDouble();

        alan = (𝜋 *(r*r)*a)/360;
        System.out.println(alan);



    }
}
```
