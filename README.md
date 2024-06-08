import java.util.Scanner;


public class Main4 {


    public static void main(String[] args) {
    
        String KullaniciAdi,sifre;
        Scanner input= new Scanner(System.in);

        System.out.print("Lütfen bir kullanıcı adı giriniz: ");
        KullaniciAdi= input.nextLine();

        System.out.print("Lütfen bir şifre giriniz: ");
        sifre= input.nextLine();

        if(KullaniciAdi.equals("begnoona") && sifre.equals("furkan123")){
            System.out.print("Giris Yaptiniz");

        }
        else {
            System.out.print("Hatali giris yaptınız tekrar deneyiniz..");

        }
    }

}
