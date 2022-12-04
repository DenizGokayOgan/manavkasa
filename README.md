# manavkasa

    import java.util.Scanner;
    public class Main {

    public static void main(String[] args) {
        double a ,e ,d ,m ,p;
        double toplam;

        Scanner input = new Scanner(System.in);
        System.out.print("Armut kaç kilo? : ");
        a = input.nextDouble();
        a *= 2.14 ;
        System.out.print("Elma kaç kilo? : ");
        e = input.nextDouble();
        e *= 3.67 ;
        System.out.print("Domates kaç kilo? : ");
        d = input.nextDouble();
        d *= 1.11 ;
        System.out.print("Muz kaç kilo : ");
        m = input.nextDouble();
        m *= 0.95 ;
        System.out.print("Patlıcan kaç kilo: ");
        p = input.nextDouble();
        p *= 5.00 ;

        toplam = a+e+d+m+p;

        System.out.println("Toplam tutar: " +toplam);


    }
}
