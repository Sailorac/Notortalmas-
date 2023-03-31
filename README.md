



import java.util.Scanner ;
public class Main {
    public static void main(String[] args) {
        int mat, fizik, kimya, turkce, muzik;

        Scanner input = new Scanner(System.in) ;

System.out.print("Matematik Notunuz:");
mat = input.nextInt() ;


System.out.print("Fizik Notunuz :");
fizik = input.nextInt();


System.out.print("Kimya Notunu Giriniz :");
kimya = input.nextInt();


System.out.print("Türkçe Notunu Giriniz :");
turkce = input.nextInt();


System.out.print("Muzik Notunu Giriniz :");
muzik = input.nextInt();

  int toplam = (mat + fizik + kimya + turkce + muzik) ;
  double ortalama = toplam / 5 ;
        System.out.println("ortalamanız: "+ ortalama);
        boolean durum = ortalama>=60;
        String sonuc = durum ? "Sınıfı Geçtiniz" : "Sınıfta Kaldınız";
        System.out.println(sonuc);
