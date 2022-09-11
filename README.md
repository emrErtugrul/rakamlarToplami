# rakamlarToplami


import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner inp=new Scanner(System.in);
        int sayi,bolme,a,b,c,d,e,f,g,h;
        System.out.println("Sayı giriniz: ");
        sayi=inp.nextInt();
        h = sayi / 10000000;
        sayi = sayi - (h * 10000000);
        //System.out.println(h);
        //System.out.println(sayi);
        g = sayi / 1000000;
        sayi = sayi - (g * 1000000);
        //System.out.println(g);
        //System.out.println(sayi);
        f = sayi / 100000;
        sayi = sayi - (f * 100000);
        //System.out.println(f);
        //System.out.println(sayi);
        e = sayi / 10000;
        sayi = sayi - (e * 10000);
        //System.out.println(e);
        //System.out.println(sayi);
        d = sayi / 1000;
        sayi = sayi - (d * 1000);
        //System.out.println(d);
        //System.out.println(sayi);
        c = sayi / 100;
        sayi = sayi - (c * 100);
        //System.out.println(c);
        //System.out.println(sayi);
        b = sayi / 10;
        a = sayi - (b* 10);
        //System.out.println(b);
        //System.out.println(a);
        //System.out.println(sayi);
        System.out.println("Rakamlar Toplamı ="+(a+b+c+d+e+f+g+h));
    }
}
