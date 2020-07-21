![Image of Java Logo](https://github.com/eemustafasahin/images/blob/master/Java_logo_icon.png)

#  JAVA_COURSE_NOTES
_These notes cover almost every aspects of core Java. At the time you have seen this content, there might be Turkish headers and subheaders. Learner of java programming language, I try to upload new topics and edit some of them. As I repeat the lessons uploaded here, edits will be increasing. When finishing Core Java Course I will complete editing these lessons and start to use as a reference._

### TABLE OF CONTENTS (CORE JAVA)

1.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson001/java001.md)
2.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson002/java002.md)
3.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson003/java003.md)
4.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson004/java004.md)
5.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson005/java005.md)
6.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson006/java006.md)
7.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson007/java007.md)
8.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md)

      - [Method overloading nedir ?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#method-overloading-nedir-)
      - [Bir metodun static olup olmamasının overload işlemine etkisi yoktur](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#bir-metodun-static-olup-olmamas%C4%B1n%C4%B1n-overload-i%C5%9Flemine-etkisi-yoktur)
      - [Bir metodun geri dönüş tür bilgisinin overload işlemine etkisi yoktur.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#bir-metodun-geri-d%C3%B6n%C3%BC%C5%9F-t%C3%BCr-bilgisinin-overload-i%C5%9Flemine-etkisi-yoktur)
      - [Bir metodun parametre değişkenlerinin isimlerinin overload işlemine etkisi yoktur.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#bir-metodun-parametre-de%C4%9Fi%C5%9Fkenlerinin-isimlerinin-overload-i%C5%9Flemine-etkisi-yoktur)
      - [Bir metodun overload edilebilmesi için parametrik yapısı farklı olması gerekir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#bir-metodun-overload-edilebilmesi-i%C3%A7in-parametrik-yap%C4%B1s%C4%B1-farkl%C4%B1-olmas%C4%B1-gerekir)
      - [Bir metodun imzası nedir?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#bir-metodun-imzas%C4%B1-nedir)
      - [Overload Resolution işlemi nasıl gerçekleşir?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#overload-resolution-i%C5%9Flemi-nas%C4%B1l-ger%C3%A7ekle%C5%9Fir)
      - [Bir değişkenin faaliyet alanı ve ömrü nedir?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#bir-de%C4%9Fi%C5%9Fkenin-faaliyet-alan%C4%B1-ve-%C3%B6mr%C3%BC-nedir)
      - [Sınıfın elemanları: metot ve veri elemanı.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f%C4%B1n-elemanlar%C4%B1-metot-ve-veri-eleman%C4%B1)
      - [Sınıfın veri elemanı nedir?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f%C4%B1n-veri-eleman%C4%B1-nedir)
      - [Bir sınıf içerisinde aynı isimde birden fazla veri elemanı bildirimi yapılamaz.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#bir-s%C4%B1n%C4%B1f-i%C3%A7erisinde-ayn%C4%B1-isimde-birden-fazla-veri-eleman%C4%B1-bildirimi-yap%C4%B1lamaz)
      - [Sınıf bildirimi bir tür bildirimidir!](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f-bildirimi-bir-t%C3%BCr-bildirimidir)
      - [Sınıf bildirimi bir tür bildirimi olduğuna göre sınıf türünden de değişkenler bildirilebilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f-bildirimi-bir-t%C3%BCr-bildirimi-oldu%C4%9Funa-g%C3%B6re-s%C4%B1n%C4%B1f-t%C3%BCr%C3%BCnden-de-de%C4%9Fi%C5%9Fkenler-bildirilebilir)
      - [Java' da türler kategori olarak iki gruba ayrılır: değer türleri (value types), referans türleri (reference types).](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#java-da-t%C3%BCrler-kategori-olarak-iki-gruba-ayr%C4%B1l%C4%B1r-de%C4%9Fer-t%C3%BCrleri-value-types-referans-t%C3%BCrleri-reference-types)
      - [Sınıf türünden bir değişkene referans değişken ya da referans denir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f-t%C3%BCr%C3%BCnden-bir-de%C4%9Fi%C5%9Fkene-referans-de%C4%9Fi%C5%9Fken-ya-da-referans-denir)
      - [Java'da nesne yaratılması.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#javada-nesne-yarat%C4%B1lmas%C4%B1)
      - [Sınıfın non-static veri elemanları her nesne için ayrıca yaratılır.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-veri-elemanlar%C4%B1-her-nesne-i%C3%A7in-ayr%C4%B1ca-yarat%C4%B1l%C4%B1r)
      - [Non-static veri elemanlarına nesnenin yaratılması aşamasında default değerler atanır.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#non-static-veri-elemanlar%C4%B1na-nesnenin-yarat%C4%B1lmas%C4%B1-a%C5%9Famas%C4%B1nda-default-de%C4%9Ferler-atan%C4%B1r)
      - [Java'da nesnenin bellekte kapladığı alan en az non-static veri elemanlarının toplam uzunluğu kadardır.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#javada-nesnenin-bellekte-kaplad%C4%B1%C4%9F%C4%B1-alan-en-az-non-static-veri-elemanlar%C4%B1n%C4%B1n-toplam-uzunlu%C4%9Fu-kadard%C4%B1r)
      - [İki aynı türden referansın birbirine atanması iki referansın da aynı nesneyi göstermeleri demektir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#i%CC%87ki-ayn%C4%B1-t%C3%BCrden-referans%C4%B1n-birbirine-atanmas%C4%B1-iki-referans%C4%B1n-da-ayn%C4%B1-nesneyi-g%C3%B6stermeleri-demektir)
      - [Referans parametreli metotlar olabilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#referans-parametreli-metotlar-olabilir)
      - [Referans parametreli metotlar aldıkları referansa ilişkin nesne üzerinde değişiklik yapabilirler .](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#referans-parametreli-metotlar-ald%C4%B1klar%C4%B1-referansa-ili%C5%9Fkin-nesne-%C3%BCzerinde-de%C4%9Fi%C5%9Fiklik-yapabilirler-)
      - [Referans geri dönen metotlar ile bir nesnenin referansı metodun geri dönüş değerinden elde edilebilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#referans-geri-d%C3%B6nen-metotlar-ile-bir-nesnenin-referans%C4%B1-metodun-geri-d%C3%B6n%C3%BC%C5%9F-de%C4%9Ferinden-elde-edilebilir)
      - [Sınıfın static bir veri elemanı bir tanedir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f%C4%B1n-static-bir-veri-eleman%C4%B1-bir-tanedir)
      - [Sınıfın static veri elemanlarının hepsi sınıfın bir elemanı ilk kez kez kullanıldığında yaratılır ve programın sonuna kadar yaşarlar.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f%C4%B1n-static-veri-elemanlar%C4%B1n%C4%B1n-hepsi-s%C4%B1n%C4%B1f%C4%B1n-bir-eleman%C4%B1-ilk-kez-kez-kullan%C4%B1ld%C4%B1%C4%9F%C4%B1nda-yarat%C4%B1l%C4%B1r-ve-program%C4%B1n-sonuna-kadar-ya%C5%9Farlar)
      - [Sınıfın static veri elemanlarına da default değerler atanır.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson008/java008.md#s%C4%B1n%C4%B1f%C4%B1n-static-veri-elemanlar%C4%B1na-da-default-de%C4%9Ferler-atan%C4%B1r)

9.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/java009.md)

      - [Sınıfın non-static bir elemanına sınıf dışından sınıf ismi ile erişilemez. Çünkü non-static veri elemanı her nesne için ayrıca yaratılır.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-eleman%C4%B1na-s%C4%B1n%C4%B1f-d%C4%B1%C5%9F%C4%B1ndan-s%C4%B1n%C4%B1f-ismi-ile-eri%C5%9Filemez-%C3%A7%C3%BCnk%C3%BC-non-static-veri-eleman%C4%B1-her-nesne-i%C3%A7in-ayr%C4%B1ca-yarat%C4%B1l%C4%B1r-nesne-bilinmeden-elemana-eri%C5%9Filemez)
      - [Sınıfın static bir elemanına sınıf dışından referans ile de erişilebilir. Sınıf ismi ile erişmekten okunabilirlik hariç bir farkı yoktur.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-static-bir-eleman%C4%B1na-s%C4%B1n%C4%B1f-d%C4%B1%C5%9F%C4%B1ndan-referans-ile-de-eri%C5%9Filebilir-s%C4%B1n%C4%B1f-ismi-ile-eri%C5%9Fmekten-bir-fark%C4%B1-yoktur-bu-%C5%9Fekilde-kodlar-okunabilirlik-a%C3%A7%C4%B1s%C4%B1ndan-yaz%C4%B1lmamal%C4%B1d%C4%B1r)
      - [Sınıfın non-static bir metodu sınıf dışından referans ve nokta operatörü ile çağrılabilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-s%C4%B1n%C4%B1f-d%C4%B1%C5%9F%C4%B1ndan-referans-ve-nokta-operat%C3%B6r%C3%BC-ile-%C3%A7a%C4%9Fr%C4%B1labilir)
      - [Sınıfın non-static bir metodu sınıf dışından sınıf ismi ve noka operatörü ile çağrılamaz](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-s%C4%B1n%C4%B1f-d%C4%B1%C5%9F%C4%B1ndan-s%C4%B1n%C4%B1f-ismi-ve-noka-operat%C3%B6r%C3%BC-ile-%C3%A7a%C4%9Fr%C4%B1lamaz)
      - [Sınıfın static bir metodu sınıf isme ve nokta operatörü ile çağrılabilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-s%C4%B1n%C4%B1f-isme-ve-nokta-operat%C3%B6r%C3%BC-ile-%C3%A7a%C4%9Fr%C4%B1labilir)
      - [Sınıfın static bir metodu referans ve nokta operatörü ile de çağrılabilir. Fakat okunabilirlik açısından yapılmamalıdır](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-referans-ve-nokta-operat%C3%B6r%C3%BC-ile-de-%C3%A7a%C4%9Fr%C4%B1labilir-static-veri-elemanlar%C4%B1nda-oldu%C4%9Fu-gibi-herhangi-bir-etkisi-yoktur-bu-%C5%9Fekilde-%C3%A7a%C4%9Fr%C4%B1-okunabilirlik-a%C3%A7%C4%B1s%C4%B1ndan-yap%C4%B1lmamal%C4%B1d%C4%B1r)
      - [Sınıfın non-static bir metodu içerisinde aynı sınıfın non-static bir veri elemanına doğrudan erişilebilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-ayn%C4%B1-s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-veri-eleman%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir-do%C4%9Frudan-eri%C5%9Filen-veri-eleman%C4%B1-metodu-%C3%A7a%C4%9F%C4%B1ran-referans%C4%B1n-g%C3%B6sterdi%C4%9Fi-nesnenin-veri-eleman%C4%B1d%C4%B1r)
      - [Sınıfın non-static bir metodu içerisinde aynı sınıfın non-static metodu doğrudan çağrılabilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-ayn%C4%B1-s%C4%B1n%C4%B1f%C4%B1n-non-static-metodu-do%C4%9Frudan-%C3%A7a%C4%9Fr%C4%B1labilir-do%C4%9Frudan-%C3%A7a%C4%9Fr%C4%B1lan-metot-%C3%A7a%C4%9F%C4%B1ran-metodu-%C3%A7a%C4%9F%C4%B1ran-referans-ile-%C3%A7a%C4%9Fr%C4%B1lm%C4%B1%C5%9F-olur)
      - [Yukarıdaki iki maddenin özeti olarak, sınıfın non-static bir metodu içerisinde sınıfın non-static elemanlarına doğrudan erişilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-iki-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-non-static-elemanlar%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Sınıfın non-static bir metodu içerisinde sınıfın static bir veri elemanına doğrudan erişilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-static-bir-veri-eleman%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Sınıfın non-static bir metodu içerisinde sınıfın static bir metodu doğrudan çağrılabilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-do%C4%9Frudan-%C3%A7a%C4%9Fr%C4%B1labilir)
      - [Yukarıdaki iki maddenin özeti olarak, sınıfın non-static bir metodu içerisinde sınıfın static elemanlarına doğrudan erişilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-iki-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-static-elemanlar%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Yukarıdaki dört maddenin özeti olarak, sınıfın non-static bir metodu içerisinde sınıfın tüm elemanlarına (non-static veya static) doğrudan erişilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-d%C3%B6rt-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-t%C3%BCm-elemanlar%C4%B1na-non-static-veya-static-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Sınıfın static bir metodu içerisinde sınıfın non-static bir veri elemanına doğrudan erişilemez.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-d%C3%B6rt-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-t%C3%BCm-elemanlar%C4%B1na-non-static-veya-static-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Sınıfın static bir metodu içerisinde sınıfın non-static bir metodu doğrudan çağrılamaz.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-do%C4%9Frudan-%C3%A7a%C4%9Fr%C4%B1lamaz-%C3%A7%C3%BCnk%C3%BC-%C3%A7a%C4%9Fr%C4%B1lmaya-%C3%A7al%C4%B1%C5%9F%C4%B1lan-non-static-metot-bir-non-veri-eleman%C4%B1na-eri%C5%9Fiyor--olabilir-bu-durumda-veri-eleman%C4%B1n%C4%B1n-hangi-nesneye-oldu%C4%9Fu-bilinemez-dolay%C4%B1s%C4%B1yla-error-olu%C5%9Fur)
      - [Yukarıdaki iki maddenin özeti olarak, sınıfın static bir metodu içerisinde sınıfın non-static elemanlarına doğrudan erişilemez](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-iki-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-non-static-elemanlar%C4%B1na-do%C4%9Frudan-eri%C5%9Filemez)
      - [Sınıfın static bir metodu içerisinde sınıfın static bir elemanına doğrudan erişilebilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-static-bir-eleman%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Sınıfın static bir metodu içerisinde sınıfın static bir metodu doğrudan çağrılabilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-do%C4%9Frudan-%C3%A7a%C4%9Fr%C4%B1labilir)
      - [Yukarıdaki iki maddenin özeti olarak, sınıfın static bir metodu içerisinde sınıfın static elemanlarına doğrudan erişilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-iki-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-static-elemanlar%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Yukarıdaki dört maddenin özeti olarak, sınıfın static bir metodu içerisinde sınıfın yalnızca static elemanlarına doğrudan erişilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-d%C3%B6rt-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-yaln%C4%B1zca-static-elemanlar%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Yukarıdaki sekiz maddenin özeti olarak, sınıfın non-static bir metodu içerisinde sınıfın her elemanına doğrudan erişilebilirken, static bir metodu içerisinde yalnızca static elemanlarına doğrudan erişilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#yukar%C4%B1daki-sekiz-maddenin-%C3%B6zeti-olarak-s%C4%B1n%C4%B1f%C4%B1n-non-static-bir-metodu-i%C3%A7erisinde-s%C4%B1n%C4%B1f%C4%B1n-her-eleman%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilirken-static-bir-metodu-i%C3%A7erisinde-yaln%C4%B1zca-static-elemanlar%C4%B1na-do%C4%9Frudan-eri%C5%9Filebilir)
      - [Point sınıfı ve test kodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#point-s%C4%B1n%C4%B1f%C4%B1-ve-test-kodu)
      - [Point sınıfı](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#point-s%C4%B1n%C4%B1f%C4%B1)
      - [Complex sınıfı ve test kodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#complex-s%C4%B1n%C4%B1f%C4%B1-ve-test-kodu)
      - [Complex sınıfı](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#complex-s%C4%B1n%C4%B1f%C4%B1)
      - [Random sınıfı nextInt metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#random-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-nextint-metodu)
      - [Random sınıfı nextDouble metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#random-s%C4%B1n%C4%B1f%C4%B1-nextdouble-metodu)
      - [Random sınıfı nextLong metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#random-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-nextlong-metodu)
      - [Random sınıfın nextBoolean metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#random-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-nextboolean-metodu)
      - [Sınıf Çalışması: Paranın yazı gelme olasılığının yaklaşık olarak 0.5 olduğunu bulan basit bir simulasyon programını yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-paran%C4%B1n-yaz%C4%B1-gelme-olas%C4%B1l%C4%B1%C4%9F%C4%B1n%C4%B1n-yakla%C5%9F%C4%B1k-olarak-05-oldu%C4%9Funu-bulan-basit-bir-simulasyon-program%C4%B1n%C4%B1-yaz%C4%B1n%C4%B1z)
      - [Sınıf Çalışması: Paranın yazı gelme olasılığının yaklaşık olarak 0.5 olduğunu bulan basit bir simulasyon programını yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-paran%C4%B1n-yaz%C4%B1-gelme-olas%C4%B1l%C4%B1%C4%9F%C4%B1n%C4%B1n-yakla%C5%9F%C4%B1k-olarak-05-oldu%C4%9Funu-bulan-basit-bir-simulasyon-program%C4%B1n%C4%B1-yaz%C4%B1n%C4%B1z-1)
      - [Sınıf Çalışması: İki zar atıldığında zarların çift gelmesi (ikisi de aynı) olasılığını yaklaşık hesaplayan basit simülasyon programını yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-i%CC%87ki-zar-at%C4%B1ld%C4%B1%C4%9F%C4%B1nda-zarlar%C4%B1n-%C3%A7ift-gelmesi-ikisi-de-ayn%C4%B1-olas%C4%B1l%C4%B1%C4%9F%C4%B1n%C4%B1-yakla%C5%9F%C4%B1k-hesaplayan-basit-sim%C3%BClasyon-program%C4%B1n%C4%B1-yaz%C4%B1n%C4%B1z)
      - [Tohum değeri setSeed isimli metot ile değiştirilebilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#tohum-de%C4%9Feri-setseed-isimli-metot-ile-de%C4%9Fi%C5%9Ftirilebilir)
      - [Homework-002-2. sorunun bir çözümü.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#homework-002-2-sorunun-bir-%C3%A7%C3%B6z%C3%BCm%C3%BC)
      - [Java'da nesnenin yaratılma aşamaları](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#javada-nesnenin-yarat%C4%B1lma-a%C5%9Famalar%C4%B1)
      - [constructor (ctor) özellikleri](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#constructor-ctor-%C3%B6zellikleri)
      - [ctor'un çağrılması](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#ctorun-%C3%A7a%C4%9Fr%C4%B1lmas%C4%B1)
      - [ctor non-static bir metottur.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#ctor-non-static-bir-metottur-a%C5%9Fa%C4%9F%C4%B1daki-%C3%B6rnekte-do%C4%9Frudan-eri%C5%9Filen-x-bu-ctor-ile-yarat%C4%B1lan-nesnenin-xi-olur)
      - [ctor öncesinde default değerler atanmış olur.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#ctor-%C3%B6ncesinde-default-de%C4%9Ferler-atanm%C4%B1%C5%9F-olur)
      - [ctor içerisinde return kullanımı](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#ctor-i%C3%A7erisinde-return-kullan%C4%B1m%C4%B1)
      - [Point sınıfı ve test kodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson009/Java009.md#point-s%C4%B1n%C4%B1f%C4%B1-ve-test-kodu-1)
         
10.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md)

      -  [Complex sınıfı ve test kodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#complex-s%C4%B1n%C4%B1f%C4%B1-ve-test-kodu)
      -  [Random sınıfının tohum değeri parametreli ctor elemanı](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#random-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-tohum-de%C4%9Feri-parametreli-ctor-eleman%C4%B1)
      -  [Derleyici String atomu gördüğünde nasıl bir kod üretir ?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#derleyici-string-atomu-g%C3%B6rd%C3%BC%C4%9F%C3%BCnde-nas%C4%B1l-bir-kod-%C3%BCretir-)
      -  [printf metodunda s format karakteri ile bir String referansına ilişkin yazı ekrana basılabilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#printf-metodunda-s-format-karakteri-ile-bir-string-referans%C4%B1na-ili%C5%9Fkin-yaz%C4%B1-ekrana-bas%C4%B1labilir)
      -  [immutable sınıf nedir ?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#immutable-s%C4%B1n%C4%B1f-nedir-)
      -  [String sınıfının toUpperCase metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-touppercase-metodu)
      -  [String sınıfının toLowerCase metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-tolowercase-metodu)
      -  [String sınıfının length isimli metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-length-isimli-metodu)
      -  [String sınıfının charAt isimli metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-charat-isimli-metodu)
      -  [Boş String nedir ?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#bo%C5%9F-string-nedir-)
      -  [Aynı türden iki referansın == ve != operatörleri ile karşılaştırılması](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#ayn%C4%B1-t%C3%BCrden-iki-referans%C4%B1n--ve--operat%C3%B6rleri-ile-kar%C5%9F%C4%B1la%C5%9Ft%C4%B1r%C4%B1lmas%C4%B1)
      -  [Yazıların eşitlik karşılaştırması == ve != operatörleri ile yapılmaz](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#yaz%C4%B1lar%C4%B1n-e%C5%9Fitkik-kar%C5%9F%C4%B1la%C5%9Ft%C4%B1rmas%C4%B1--ve--operat%C3%B6rleri-ile-yap%C4%B1lmaz)
      -  [Yazıların eşitlik karşılaştırması equals metodu ile yapılabilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#yaz%C4%B1lar%C4%B1n-e%C5%9Fitlik-kar%C5%9F%C4%B1la%C5%9Ft%C4%B1rmas%C4%B1-equals-metodu-ile-yap%C4%B1labilir)
      -  [String sınıfının equalsIgnoreCase isimli metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-equalsignorecase-isimli-metodu)
      -  [String sınıfının indexOf metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-indexof-metodu)
      -  [String sınıfının fromIndex parametreli indexOf metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-fromindex-parametreli-indexof-metodu)
      -  [String sınıfının lastIndexOf metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-lastindexof-metodu)
      -  [Sınıf Çalışması: (countString isimli metodun yazılması)](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-countstring-isimli-metodun-yaz%C4%B1lmas%C4%B1)
      -  [Bir string içinde boş string arama testi 1 (kötü yöntem)](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#bir-string-i%C3%A7inde-bo%C5%9F-string-arama-testi-1-k%C3%B6t%C3%BC-y%C3%B6ntem)
      -  [Bir string içinde boş string arama testi 2 (kötü yöntem)](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#bir-string-i%C3%A7inde-bo%C5%9F-string-arama-testi-2-k%C3%B6t%C3%BC-y%C3%B6ntem)
      -  [Bir string içinde boş string arama testi 3 (iyi yöntem)](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#bir-string-i%C3%A7inde-bo%C5%9F-string-arama-testi-3-iyi-y%C3%B6ntem)
      -  [String sınıfının trim metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-trim-metodu)
      -  [String sınıfının concat metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-concat-metodu)
      -  [Yazı birleştirmesi + operatörü ile de yapılabilir](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#yaz%C4%B1-birle%C5%9Ftirmesi--operat%C3%B6r%C3%BC-ile-de-yap%C4%B1labilir)
      -  [+ operatörünün operandlarından bir String türündense diğer operandının String karşlığı elde edilerek birleştirme işlemi yapılır](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#-operat%C3%B6r%C3%BCn%C3%BCn-operandlar%C4%B1ndan-bir-string-t%C3%BCr%C3%BCndense-di%C4%9Fer-operand%C4%B1n%C4%B1n-string-kar%C5%9Fl%C4%B1%C4%9F%C4%B1-elde-edilerek-birle%C5%9Ftirme-i%C5%9Flemi-yap%C4%B1l%C4%B1r)
      -  [Sınıf Çalışması: reverse metodunu yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-reverse-metodunu-yaz%C4%B1n%C4%B1z)
      -  [Sınıf Çalışması: Basit ATM kullanıcı ve parola test uygulamasını yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-basit-atm-kullan%C4%B1c%C4%B1-ve-parola-test-uygulamas%C4%B1n%C4%B1-yaz%C4%B1n%C4%B1z)
      -  [String sınıfının substring metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-substring-metodu)
      -  [String sınıfının substring metoduna index numarası olarak yazının uzunluğu verildiğinde boş string döndürür](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-substring-metoduna-index-numaras%C4%B1-olarak-yaz%C4%B1n%C4%B1n-uzunlu%C4%9Fu-verildi%C4%9Finde-bo%C5%9F-string-d%C3%B6nd%C3%BCr%C3%BCr)
      -  [Sınıf Çalışması: Quit girilene kadar aldığı yazıları - ile birleştiren programı yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-quit-girilene-kadar-ald%C4%B1%C4%9F%C4%B1-yaz%C4%B1lar%C4%B1---ile-birle%C5%9Ftiren-program%C4%B1-yaz%C4%B1n%C4%B1z)
      -  [String sınıfının startsWith metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-startswith-metodu)
      -  [String sınıfının endsWith metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-endswith-metodu)
      -  [Character sınıfının isXXX ( isWhiteSpace, isLetter, isDigit, isUpparCase, isLowerCase ) metotları](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#character-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-isxxx-metotlar%C4%B1)
      -  [Character sınıfının toXXX ( toUpperCase, toLowerCase )metotları](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#character-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-toxxx-metotlar%C4%B1)
      -  [Sınıf Çalışması: Aldığı yazının ilk karakterini büyük harf capitalize isimli metodu yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-ald%C4%B1%C4%9F%C4%B1-yaz%C4%B1n%C4%B1n-ilk-karakterini-b%C3%BCy%C3%BCk-harf-capitalize-isimli-metodu-yaz%C4%B1n%C4%B1z)
      -  [Sınıf Çalışması: Aldığı yazının sağındaki boşlukları silen trimRight ve solundaki boşlukları silen trimLeft metotlarını ayrı ayrı yazınız](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-ald%C4%B1%C4%9F%C4%B1-yaz%C4%B1n%C4%B1n-sa%C4%9F%C4%B1ndaki-bo%C5%9Fluklar%C4%B1-silen-trimright-ve-solundaki-bo%C5%9Fluklar%C4%B1-silen-trimleft-metotlar%C4%B1n%C4%B1-ayr%C4%B1-ayr%C4%B1-yaz%C4%B1n%C4%B1z)
      -  [Sınıf Çalışması: Aşağıda açıklanan metotları (padLeft ve padRight) yazınız ve test ediniz](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-a%C5%9Fa%C4%9F%C4%B1da-a%C3%A7%C4%B1klanan-metotlar%C4%B1-padleft-ve-padright-yaz%C4%B1n%C4%B1z-ve-test-ediniz)
      -  [Homework-002-2. sorunun bir çözümü.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#homework-002-2-sorunun-bir-%C3%A7%C3%B6z%C3%BCm%C3%BC)
      -  [Aldığı yazının içindeki tüm boşlukları silen removeWhiteSpaces metodunu yazınız.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#ald%C4%B1%C4%9F%C4%B1-yaz%C4%B1n%C4%B1n-i%C3%A7indeki-t%C3%BCm-bo%C5%9Fluklar%C4%B1-silen-removewhitespaces-metodunu-yaz%C4%B1n%C4%B1z)
      -  [String sınıfının compareTo metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-compareto-metodu)
      -  [String sınıfının compareToIgnoreCase metodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java010.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-comparetoignorecase-metodu)
      
11.   [Lesson](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson010/java011.md)

      -  [Derleyici özdeş String atomları (string literal) için aynı adresi verir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#derleyici-%C3%B6zde%C5%9F-string-atomlar%C4%B1-string-literal-i%C3%A7in-ayn%C4%B1-adresi-verir)
      -  [Sınıf çalışması: isPangramTR ve isPangramEN isimli metodlarını yazınız (1.1).](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-ispangramtr-ve-ispangramen-isimli-metodlar%C4%B1n%C4%B1-yaz%C4%B1n%C4%B1z-11)
      -  [isPangramEN motedunun unicode-uyumlu yazılması (1.2)](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#ispangramen-motedunun-unicode-uyumlu-yaz%C4%B1lmas%C4%B1-12)
      -  [Sınıf çalışması: isPalindrom isimli motodu yazınız (2).](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-ispalindrom-isimli-motodu-yaz%C4%B1n%C4%B1z-2)
      -  [Sınıf çalışması: isPalindrom isimli motodu yazınız (3).](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-ispalindrom-isimli-motodu-yaz%C4%B1n%C4%B1z-3)
      -  [Sınıf çalışması: isPalindrom isimli motodu yazınız(4).](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-ispalindrom-isimli-motodu-yaz%C4%B1n%C4%B1z4)
      -  [Sınıf çalışması: getLongestPalindrome metodunu yazınız.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-getlongestpalindrome-metodunu-yaz%C4%B1n%C4%B1z)
      -  [Sınıf Çalışması: getRandomTextTR ve getRandomTextEN metodlarını yazınız.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-getrandomtexttr-ve-getrandomtexten-metodlar%C4%B1n%C4%B1-yaz%C4%B1n%C4%B1z)
      -  [Sarmalayan sınıfların parseXXX (parseint, parse double vs.) metodları ile yazılar sayıya çevrilebilir.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#sarmalayan-s%C4%B1n%C4%B1flar%C4%B1n-parsexxx-parseint-parse-double-vs-metodlar%C4%B1-ile-yaz%C4%B1lar-say%C4%B1ya-%C3%A7evrilebilir)
      -  [Neden nextInt, nextLong, nextDouble metotları nextLine metodu ile aynı Scanner nesnesi üzerinde kullanılmamalıdır ?](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#neden-nextint-nextlong-nextdouble-metotlar%C4%B1-nextline-metodu-ile-ayn%C4%B1-scanner-nesnesi-%C3%BCzerinde-kullan%C4%B1lmamal%C4%B1d%C4%B1r-)
      -  [String sınıfının valueOf metodu.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-valueof-metodu)
      -  [String sınıfının contains metodu.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-contains-metodu)
      -  [Sınıf çalışması: isPangramTr ve isPangramEN metodlarını yazınız.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#s%C4%B1n%C4%B1f-%C3%A7al%C4%B1%C5%9Fmas%C4%B1-ispangramtr-ve-ispangramen-metodlar%C4%B1n%C4%B1-yaz%C4%B1n%C4%B1z)
      -  [String sınıfının format metodu.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-format-metodu)
      -  [Complex sınıfı ve test kodu](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#complex-s%C4%B1n%C4%B1f%C4%B1-ve-test-kodu)
      -  [String sınıfının replace metodu.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#string-s%C4%B1n%C4%B1f%C4%B1n%C4%B1n-replace-metodu)
      -  [java 7 ile birlikte switch deyiminde String kullanımı.](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#java-7-ile-birlikte-switch-deyiminde-string-kullan%C4%B1m%C4%B1)
      -  [Paketler](https://github.com/eemustafasahin/Complete_Java_Course_Notes/blob/master/JavaLesson011/java011.md#paketler)
