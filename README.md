# KOU-PL1P1 3 boyutlu görüntü dosyaları projesi
Bu readme.txt dosyası, 3 boyutlu görüntü dosyaları projesi  koduna aittir.
Bu paket, kod ile aynı dizin içerisinde bulunacaktır.


1-PAKETİN İÇERİĞİ:
----------
180202085-180202086.c - Proje  kaynak kodu.
readme.txt - Bu dosya.
Rapor.pdf - Bu projenin raporu.
----------

2-SİSTEM GEREKSİNİMLERİ:
-------------------
Codeblocks'u çalıştırabilecek seviye de bir bilgisayar olması gerekmektedir
-------------------


3-KURULUM:

-------------------
Paket içeriğini yukarıda görebilirsiniz.

Bu kod, iki adet Windows kurulu makinede çalıştırıldı:
- Furkan'nın Windows 10 Education yüklü dizüstü bilgisayarında.
- Berke'nin Windows 10 Home  yüklü dizüstü bilgisayarında.

Bu iki durumda da kod, herhangi bir hata vermeden, daha önceden belirlenen kriterlere
uygun çalıştı.



-------------------


4-KODU DERLEMEK:
------------------
Bilgisayarımızda kurulu olan C derleyici ile kodu kolayca derleyebiliriz.

Derleme bittikten sonra kolayca programı çalıştırabilirsiniz.
------------------


5- PARAMETRELER
---------------------------
Kodun çalışması için başlangıçta herhangi bir parametre gerekmiyor.
------------------



6- PROGRAMIN KULLANIMI
-----------------------------
Program, çalıştırıldığında Klasör içinde verilen “.nkt” uzantılı dosyalar program
tarafından otomatik olarak algılanır eğer bu dosyalar Ascii formatında verilmiş ise
 Ascii olarak eğer Binary formatında verilmiş ise Binary olarak program tarafından 
okutma yapılır. Okuma tamamlandıktan sonra proje tarafından verilen “İsterler ” 
bölüme geçiş yapılır. Bu kısımda kullanıcıdan bir seçim yapması istenilir. Kullanıcı
 1’ bastığında Tüm dosyalar uyumlu ise “Tüm dosyalar uyumludur.” Mesajı bastırılır. 
Eğer dosya da bir uyuşmazlık var ise örnek olarak şu tipte bir mesaj alacaktır :
 “156. Nokta verisi r g b bilgileri olmadan verilmiştir.”, “A.nkt dosyasındaki 
nokta sayısı geçerli değildir.” .Şayet işlem başarılı ise aynı dosya üzerinden 
diğer seçim kısmına geçilir eğer işlem başarılı değil ise program tarafından
 algılanan diğer bir “.nkt” uzantılı dosyaya geçilir.Kullanıcı 2’yebastığında 
birbirine en yakın nokta ve en uzak noktaların bilgileri ve nokta numaraları
 bastırılır. Kullanıcı 3’ebastığında birbirine en yakın nokta ve en uzak noktaların 
bilgileri ve nokta numaraları bastırılır. Kullanıcı 4’e bastığında Merkezinin 3 
boyutlu koordinatı ve yarıçapı bilgileri kullanıcıdan istenilen bir kürenin içinde
 kalan noktaların bilgileri ve nokta numaraları ekrana bastırılır. Kullanıcı 5’e 
bastığında her bir noktanın birbirlerine olan uzaklıklarının ortalaması ekrana 
bastırılır. Kullanıcı 6’ya bastığında ise programdan çıkış yapılır. Yapılan her
 işlem “output.nkt” dosyasına kayıt edilir. Her okutulan “.nkt” dosyasının 
kendisine özgü “output” çıktısı vardır.

***********************************************************************************

7.Değişken İsimleri
int sl : Bu değişken ile dosyanın uyumlu olduğunun mesajı bastırlır
int sl1:Bu değişken eğer bütün rgb değerleri okunmuş ise noktalar karşılaştırmaya yarar.
int sl2: Bu değişken ile dosyanın uyumsuz olduğunun mesajı bastırmaya yarar
int sl3:RGB değerlerinde hata olması durumunda ekranı hatalıdır mesajını bastırmaya yarar.
int cont:Bu değişken nokta sayılarının karşılaştırılmasını sağlar
int cont1: RGB değerlere -1 atanır ve okunmasını sağlar

