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
- **Sınıf Adları:** Java'da sınıf adlarının ilk harfleri büyük olmalıdır. İki kelimeyle birleştirilecek
- **Metot Adları:** Metot adları küçük harfle başlar, birden fazla kelimeyse eklenen her kelime büyük harfle başlar. 
- **camelCaseOrnek**
- **snake_case** : Kelimeler Alt tire ile birbirine bağlanır. Sabit değişkenlerde kullanılır.
- **SCREAMING_SNAKE_CASE**: Genelde sabit isimlendirmede kullanılır.
- **kebap-case**: Tümü küçük harfle oluşturulur, kelimeler arasına - eklenir.

## Java İsimlendirme Kuralları
- Java'da isimlendirilen tüm öğeler sadece A-Z veya a-z gibi harfler, $ karakteri veya _karakteriyle başlayabilir.
- Keywordler (yasaklı kelimeler) isimlendirmede kullanılmaz.
- **Sınıflar** için upper camel case kullanılır: **JavaSinifi**
- **Metotlar** için lower camel case kullanılır **helloWorld**
- **Değişkenler** için lower camel case kullanılır. **helloWorld**
Sabitler için screaming snake case kullanılır.**HELLO_WORLD**




