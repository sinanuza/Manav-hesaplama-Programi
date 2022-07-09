# Manav-hesaplama-Programi
www.patika.dev



**

        import java.util.Scanner;

        public class Manav {
        public static void main(String[] args) {
        double armut= 2.14,elma=3.67,domates=1.11,muz=0.95,patlican=5;
        double a,b,c,d,e;

        System.out.println("armut kac kilo?:");
        Scanner armut2=new Scanner(System.in);
        a=armut2.nextDouble();

        System.out.println("elma kac kilo?:");
        Scanner elma2=new Scanner(System.in);
        b=elma2.nextDouble();

        System.out.println("domates kac kilo?:");
        Scanner domates2=new Scanner(System.in);
        c=domates2.nextDouble();

        System.out.println("muz kac kilo?:");
        Scanner muz2=new Scanner(System.in);
        d=muz2.nextDouble();

        System.out.println("patlican kac kilo?:");
        Scanner patlican2=new Scanner(System.in);
        e=patlican2.nextDouble();

        double tutar=armut*a+elma*b+domates*c+muz*d+patlican*e;

        System.out.println("Toplam tutar:"+tutar);
    }
}
