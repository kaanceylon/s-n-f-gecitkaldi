# sinifigecitkaldi
Sınıfı Geçti Kaldı

    import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        int mat,fizik,kimya,turkce,muzik;

        Scanner input = new Scanner(System.in);
        System.out.print("mat notunuzu giriniz : ");
        mat = input.nextInt();

        System.out.print("fizik notunuzu giriniz : ");
        fizik = input.nextInt();

        System.out.print("kimya notunuzu giriniz : ");
        kimya = input.nextInt();

        System.out.print("turkce notunuzu giriniz : ");
        turkce = input.nextInt();

        System.out.print("müzik notunuzu giriniz : ");
        muzik = input.nextInt();

        double avarage = ( mat+fizik+kimya+turkce+muzik ) / 5;
        System.out.print("Ortalama : "+ avarage );
        
        if (mat < 0 || mat > 100) {
            mat = 0;{
            }
            if (fizik < 0 || fizik > 100) {
                fizik = 0;{
                }
                if (kimya < 0 || kimya > 100) {
                    kimya = 0;{
                    }
                    if (turkce < 0 || turkce > 100) {
                        turkce = 0;{
                        }
                        if ( muzik < 0 || muzik > 100) {
                            muzik = 0; {
                        }
                        }
                        if (avarage >= 55 ) {
                            System.out.print("Geçtiniz");
                        } else {
                            System.out.print("kaldınız");
                            
                        }

                    }
                }
            }
        }
    }
                               }




