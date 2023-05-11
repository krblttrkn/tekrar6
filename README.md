# Ödev - Vücut Kitle İndeksi Hesaplayan Program
## Vücut Kitle İndeksi Hesaplama
Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın. Aşağıdaki formüle göre kullanıcının "Vücut Kitle İmdeks" değerini hesaplayıp ekrana yazdırın.
### Formül
**Kilo(kg)/Bou(m) * Boy(m)**
### Çıktısı
* Lütfen boyunuzu (metre cinsinden) giriniz : 1,72
* Lütfen kilonuzu giriniz : 105
* Vücut Kitle İndeksiniz : 35,49215792320173
```
import java.util.Scanner;

public class VKIndeks {
    public static void main(String[] args){
        double meter,kg,index;
        Scanner input = new Scanner(System.in);

        System.out.print("Lütfen boyunuzu Giriniz :");
        meter=input.nextDouble();
        System.out.print("Lütfen Kilonuzu Giriniz :");
        kg = input.nextDouble();
        index = kg/(meter*meter);
        System.out.print("Vücut Kitle İndeksiniz :"+index);
    }
}
```
# Patika Profilim
<a href="https://academy.patika.dev/profile">Patika Profilim</a>