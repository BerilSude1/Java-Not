# Java Notlarım
C nin syntaxını, C++ ın nesne yönelimli programlama (OOP) kısmını java almıştır. 
***

## Java'nın Avantajları Nelerdir?
* Basit olması
* Tarafsız mimariye sahip olması (Kendi sanal makinesinden (jvm: java visual machine) dolayı her mimaride çalışabilir):
Java özel makinelere ya da işletim sistemi mimarilerine bağlı değildir. Java donanımdan bağımsızdır. Java'yı platform bağımsız kılan özelliği yazılan kaynak kodlar derlendikten sonra ara bir dil olan byte code'a çevrilmesidir. Ara dile çevrilen bu kod parçaları Java Virtual Machine vasıtasıyla yorumlanır ve çalıştırılır. Buradaki tek sorun hız sorunudur. Çünkü işletim sistemiyle birlikte Virtual Machine’de bilgisayarın kaynaklarını kullandığı için daha yavaş çalışmaktadır.
* Nesne yönelimli olması:
  Java da C++ gibi nesne yönelimlinin özelliklerinden faydalanır. Sınıflar oluşturularak daha az kod yazıp daha fazla iş yaparak kod tekrarı önlenmiş olur. Böylece geliştirme sürecinin verimliliği artar.
* Zengin kütüphane desteği
* Multi-Thread ve Dinamik (Normalde programlama dilleri yukarıdan aşağıya( a, b, c gibi)çalışır fakat java eş zamanlı çalışabiliyor):
  'Multi-Thread' bir programda bir çok işlemin aynı zamanda gerçekleşmesi özelliğidir. Eş zamanlı işlemleri programlayabilmenize imkan tanır. Java bu tür program geliştirmeye destekler.
* En çok tercih edilen dillerden biri olması

## Java ile Geliştirme Yapılabilecek Alanlar

- Mobil Uygulamalar (Android (Java ile yazılmıştır) Studio, Kotlin)
- Masaüstü Uygulamalar (AWT,Swing, JavaFX)
- Web Tabanlı Uygulamalar (Servelts, Struts, JSP)
- Kurumsal Uygulamalar
- Bilimsel Uygulamalar (Matlab)
- Oyun Programlama (jMonkeyEngine(3D motoru), Minecraft)
- Gömülü Sistemler (Java2ME Embedded)


## Java JDK (Java development Kit)
Java Geliştirme Kiti (JDK), JVM (Java Sanal Makinesi) ve JRE (Java Çalışma Zamanı Ortamı) ile birlikte Java programlamada kullanılan üç temel teknoloji
paketinden biridir. JDK, geliştiricilerin JVM ve JRE tarafından çalıştırılabilen Java programları oluşturmalarına izin verir.

## Java Yazım Kuralları
Türkçe karakterler kullanılmaz
Harf Duyarlılığı vardır. Büyük harf küçük harf fark eder.
- **Sınıf Adları:** Java'da sınıf adlarının ilk harfleri büyük olmalıdır. İki kelimeyle birleştirilecekse ikinci kelime büyük harfle başlar (upper camel case)
- **Metot Adları:** Metot adları küçük harfle başlar, birden fazla kelimeyse eklenen her kelime büyük harfle başlar. 
- **camelCaseOrnek**
- **snake_case** : Kelimeler Alt tire ile birbirine bağlanır. Sabit değişkenlerde kullanılır.
- **SCREAMING_SNAKE_CASE**: Genelde sabit isimlendirmede kullanılır.
- **kebap-case**: Tümü küçük harfle oluşturulur, kelimeler arasına - eklenir.

## Java İsimlendirme Kuralları
- Java'da isimlendirilen tüm öğeler sadece A-Z veya a-z gibi harfler, $ karakteri veya _karakteriyle başlayabilir.
- Keywordler (yasaklı kelimeler) isimlendirmede kullanılmaz:
![download](https://github.com/user-attachments/assets/66dc3d6d-07b7-406d-b918-c2cd49dd0395)
- **Sınıflar** için upper camel case kullanılır: **JavaSinifi**
- **Metotlar** için lower camel case kullanılır **helloWorld**
- **Değişkenler** için lower camel case kullanılır. **helloWorld**
Sabitler için screaming snake case kullanılır.**HELLO_WORLD**

## JAVA'DA SINIF NASIL OLUŞTURULUR - MAİN METODU ve KULLANIMI
Java'da çalışacak bir program varsa çalışmaya main metodundan başlar. Main metodu sayesinde derleyici programın buradan başlaması gerektiğini anlar.
Main metodu yazılırken, args yerine başka bir isimlendirme yapılabilir. Ancak genellikle args sözcüğü kullanılır ve bu sözcük arguments sözcüğünün kısaltmasıdır. Arguments ile ifade edilen kısım, sınıf çalıştırılırken JVM tarafından bu sınıfa verilen parametrelerdir

## Proje Başlatmak İçin
* Java dilini seç,
* SDK seç
* Proje Name yaz
* Projeyi oluştur.

* .idea: idenin özelliklerini tanımlar 
* src: Projenin çalıştığı yer. 
* Paketler: Java'da sınıflar paket paket düzenlenebilir, bakımı kolaylaşır, birbirleriyle çalışmaları daha temiz olur.
* Java sınıflar üzerinde çalışan bir programlama dilidir.

# Programlamaya Başlangıç

* Java kodunu çalıştırmak için mutlaka bir sınıfa ihtiyaç vardır.
*  Herhangi bir Java programı derlendikten sonra çalıştırılabiliyorsa, programın belli bir metodundan çalıştırılmaya başlanır. Bu metodun doğru yazımı nedir?
*  public static void main(String[] args)
* Intellij idesi otomatik olarak her işlemi kaydeder tekrar tekrar çalışmayı kaydetmeye gerek kalmaz.

#

 **public class:** Herkese açık sınıftır

#

* **package:** Giriş
* **class:** Başlangıç
* 
```
 package Giris;
 public class Baslangic{
 public static void main (String[] args){
 System.out.print("Merhaba Dünya !");
  }
 }
```

# Programlamaya Başlangıç
## Genel Söz Dizimi
![java-syntax](https://github.com/user-attachments/assets/7bb97f56-d6a6-4ba2-ac0b-0dc6d85b1fb6)

* System.out.print(""); -> Ekrana yazdırma komutu.
* System.out.println("") -> Bir alt satırda ekrana yazdırma komutu.
* "Sistemden. bir çıktı. bas" -> Gibi şifrelenebilir.

# Escape Karakterler
Java'da Escape (Kaçış) karakterleri ile bazı özel durumlar durumlar gerçekleştirilir. Kaçış karakterleri ( / ) ters eğik çizgi ile ifade edilip sonrasında yazılan karakter ile özel işleve sahip olurlar.
![download](https://github.com/user-attachments/assets/8315fa26-fc37-487e-b644-cb4ecd93e7f8)

\b: backspace: Harf harf kendinden bir önceki kelimeyi siler. Ka. tane \b kullanılırsa adedince harf silinir.
\r: Kendinden önceki her şeyi siler

# Yorum Satırları
Kodun kalitesini, okunabilirliğini yükseltmek için yorum satırları kullanılır. Bu yorum satırları çıktıda görünmez. programcılar için açıklama niteliği taşır. Kod ne işe yarıyor, kim yazmış, neler kullanılmış yazılırken gibi açıklamalar barındırır. Derleyici yorum satırını okumaz.
Tavsiye olarak: Kod çok temiz yazılmalı ki yorum satırına da ihtiyaç kalmasın.
* **Tek bir satır için:** // metin
* **Birden fazla satır için:** /* metin */
* **İnfolar için:** /** @etiket metin */ 
  Kod içi belgeleme, bu etiketleri tanıyan ve etiketlerden faydalanarak belge üreten bir aracın yardımı ile belgeye dönüştürülebilmektedir. Bu tarzda yazılan açıklama satırlarına Javadoc adı verilmektedir. Javadoc için kullanılabilecek bazı örnekler ve ne için kullanılabilecekleri aşağıda listelenmiştir:
* ![download](https://github.com/user-attachments/assets/3352643c-d4ae-4126-b7db-bd72e3f87116)
```
/**
 * @author M.Mustafa Çetindağ - 11.Nis.2021
 */
public class AciklamaSatiriOrnegi {
    /**
     * Verilen sayının karekökünü bularak döndürür.
     * Sayının sıfırdan küçük olmadığını varsayar.
     *
     * @param sayi Karekökü alınacak sayı
     * @return Sayının karekökü
     */public double karekok(double sayi) {
        double kkok = 0;
        // burada karekök bulma algoritmasının çalıştığını kabul edelimreturn kkok;
    }
}
```
# Değişkenler ve Veri Tipleri 
**Değişkenler:** Programlamada geçici bilgileri sakladığımız, programcı tarafından belirlenen yapılardır.
Değişkenlerin Özellikleri:
* 1) Değişken veri tipi : Değişkenin türünü belirler (sayı, metin, ondalıklı sayı, tam sayı)
* 2) Değişken ismi
* 3) Değişkene ait değer
* 4) Değişken adresi
 **Değişken Nasıl Tanımlanır?**
1) Değişkenin veri tipi
2) Değişkenin ismi
3) Atama operatörü (=) kullanıyoruz
4) Veri / Değer yazılır.

```
package paket;
public class Main{
public static void main(String[] args){
int number = 11;
int numberTwo;
numberTwo= 13;
int numberThree=3 , numberFour;
numberFour= 4;
String numberOne = "on bir";
System.out.print(number + numberOne); 
  }
}
```
# Java'daki İlkel Veri Tipleri
Java'da değişkenlerin veri tipleri vardır. Bu tipler Java'da varsayılan olarak tanımlı gelen ilkel tipler (primitive) de olabilir yahut yazılımcıların kendi tanımladığı ilkel olmayan tipler (non-primitive) de olabilir. İlkel tipler her zaman bir değere sahiptir. İlkel olmayan tipler ise 'null' (boş) olabilir. İlkel olmayan türlerin tümü aynı boyuta sahipken ilkel veri tiplerin boyutu alacağı veri tipine bağlıdır. (Patika Dev'den alıntıdır)
* **Tam Sayı Veri Tipleri**
Tam sayı veri tiplerinin tek farkı boyutlarıdır. Sondaki parantezli ifade kodlamadaki syntaxıdır.
  1) Byte :8 bit uzunluğundadır, max 127, min -128 değerleri arasındadır. (byte)
  2) Short: 16 bit uzunluğundadır, max 32,767, min -32768 değerleri arasındadır. (short)
  3) Integer: 32 bit uzunluğundadır, max 2,147,483,647 min -2,147,483,648 (optimize uzunluktadır) (int) 
  4) Long: 64 bit uzunluğundadır, Max 9,223,372,036,854,775,807, min Max 9,223,372,036,854,775,808 değerleri arasındadır. (long)

* **Onladık Sayılar**
* Ondalıklı sayılara tam sayı yazılabilir, ondalıklı sayılar (float, double) tam sayıları ondalıklı sayıya çevirir.
  1) Float: 32 bit boyutundadır, max 1.3*10^38, min 1.4 x 10^-45  değerleri arasındadır. (float) (ör: 3.14f -> floatın f si)
  2) Double: 64 bit boyutundadır. max 1.8*10^308, min 4.9*10^-324 değerleri arasındadır. Üst düzey matematiksel işlemlerde kullanılır (double)
      * Double tipi, yüksek duyarlıklı ve hassas matematiksel işlemlerde kullanılır.
      * Float basittir : hız ve bellek.
      * Double daha yavaş ve fazla yer kaplar.(Bu işlemler arasında milisaniye oynar)
      * Java hassas matematiksel işlemler, örneğin sinüs kosinüs fonksiyonları, double tipi değer döndürür.
* **Karakterler**
  1) Char: Tek bir karakterden oluşan veri tipidir. Birleşimi stringi oluşturur.
     ``` char vChar = 'b';
     System.out.print(vChar);
     char v2Char = 98;
     System.out.print(v2Char);
     ```
* **Mantıksal Değerler**
  1) Boolean : true veya false değeri alır.
 ```
  boolean dogru = true;
  boolean yanlis = false;
  System.out.println(dogru);
  System.out.println(yanlis);
```

  # Patika Dev: 
## Char
* Java'da karakter değişkenleri saklamak için Char kullanılır. Char veri tipleri birleşerek String Sınıfından bir yapıya dönüşür.
* Karakterler Char ile saklanır.
* Diğer dillere göre Char Java’da 16 bittir.
* Java Unicode karakter setini kullanır ve tüm dilleri içerir.
* Java evrensel bir dil olarak tasarlandığı için karakter seti de evrensel set olan Unicode ile tanımlanmıştır.
* Anahtar Sözcük : char
## Boolean
* Java, mantıksal değerleri saklamak için boolean adında bir tipe sahiptir.
* Boolean sadece iki değer alabilir : True ve False
* Genellikle koşul ve döngü işlemlerinde, kontrol amaçlı olarak kullanılır.
* Anahtar Sözcük : boolean
## String Sınıfı

String sınıfı java.lang kütüphanelerinde bulunan ve metinlerle ilgili her türlü işlemin yapıldığı sınıftır. Java'da genellikle kelime tutmak için char yerine String sınıfı kullanılır. Basitçe şöyle düşünebiliriz , Char veri tipi tek bir karakter tutabiliyorken, charların birleşmesiyle oluşan sözcükleri String Sınıfı tutmaktadır.

```
public class JavaPatika {
    public static void main(String[] args) {
        String words = "Hello World";
    }
}
```
Temel Operatörler

Java dilinde operatörler birçok işlemi yapabilmenize olanak tanır. Örneğin: matematiksel operatörlerle birlikte aritmetik işlemler yapabilmenizi, ilişkisel operatörlerle verileri kıyaslayabilmeyi, atama operatörleri ile değişkenlerin değerlerini değiştirmeye fırsat verir.

Java'da operatörler aşağıdaki gibi listelenebilir:

Atama Operatörleri
Aritmetiksel Operatörler
İlişkisel ve Eşitlik Operatörler
Koşul Operatörler
Mantıksal Operatörler

Atama Operatörü
![download](https://github.com/user-attachments/assets/b7e9b941-339c-4878-8a25-9a8117c828d7)

Aritmetik Operatörler
Java'da Aritmetik Operatörler adından da anlaşılacağı üzere matematiksel işlemleri programlama dilinde uygulamamızı sağlarlar.

Toplama : a + b
Çıkarma : a – b
Çarpma : a * b
Bölme : a / b
Mod alma : a % b
1 arttırma : a++
1 eksiltme : b--
Karşılaştırma Operatörleri
Java'da Karşılaştırma Operatörleri iki nesnenin birbirleriyle olan durumlarını belirler.

Eşitlik : a == b
Eşit Değil : a != b
Büyüktür : a > b
Küçüktür : a < b
Büyük Eşittir : a >= b
Küçük Eşittir : a <= b
Mantıksal Operatörler
Java'da Mantıksal Operatörler , nesnelerin veya ifadelerin mantıksal değerlerini yansıtır.

Ve : a && b
Veya : a || b
Değil : !(a&&b)
Koşul Operatörü
Java'da Koşul Operatörleri ifadelerin sonucunda oluşacak olayları belirler.

a = 5 ;
b = (a == 1) ? 1 : 0
Çıktısı : 0
Java'ya ait sınıflar vardır bu sınıflar bize ek araç gibi görünür.
# Kullanıcıdan Veri Alma
```
import: 
```









