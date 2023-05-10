<a name="top"></a>

---
<h1 align="center">Python</h1>

## Hedef Kitle

Burada anlatılanların hedef kitlesi ....
## Program nedir ?

Bir program, yapılacak bir işin nasıl yapılacağını anlatan bir dizi talimattır. Bu işlem matematiksel de olabilir, mesela denklemler çözmek veya polinomların köklerini bulmak gibi, ama aynı zamanda belgedeki metni aramak ve değiştirmek gibi sembolik işlemler veya resim işlemek ya da video oynatmak gibi görsel işlemler de olabilir.

Farklı programlama dillerinde detaylar farklı olabilir ama hemen hemen her dilde aşağıdaki temel talimatlar bulunur:

* girdi: Klavyeden, dosyadan, ağdan veya başka bir cihazdan veri almak.
* çıktı: Veriyi ekranda göstermek, dosyada kaydetmek, ağ üzerinden göndermek vb.
* matematik: Toplama, çıkarma, çarpma, bölme gibi temel matematiksel işlemleri yapmak.
koşullu işlem: Belli koşulları kontrol etmek ve uygun kodu çalıştırmak.
* tekrarlama: Bazı değişikliklerle tekrarlanan bir işlemi yapmak.

## Python Kuruulumu ve Versiyonları

Python, popüler bir programlama dilidir ve birçok işletim sistemi için kullanılabilir. Python'un en son sürümü
Python 3, Python programlama dilinin en son sürümüdür ve önceki sürüm olan Python 2.x'den bazı önemli değişiklikler içermektedir.
Python'u yüklemek için aşağıdaki adımları takip edebilirsiniz:

- İlk olarak, bilgisayarınızda Python yüklü değilse, resmi web sitesinden indirin ve kurun: https://www.python.org/downloads/

- Yükleyicinin ekranda gösterdiği talimatları takip edin. Önerilen seçenekler varsayılan olarak seçili olacaktır.

- Kurulum tamamlandıktan sonra, Python'u çalıştırmak için bir terminal açın ve python komutunu yazın. Bu, Python yorumlayıcısını başlatmalıdır. 

Ayrıca, Python 2.x artık aktif olarak desteklenmemektedir ve güncellenmeyecektir. Bu nedenle, yeni projelerde Python 3 kullanmak daha iyi bir seçenektir.

## İlk Program

Yeni bir programa diline başlarken gelenektendir ki Hello World! programı yazılır. Bu süre gelen bir gelenektir. Biz de bunu yapacağız. 

Az önceki bölümde terminalden python komutunu yazdığımızda Python yorumlayıcısının başladığını söylemiştik. Şimdi de Python yorumlayıcısını başlatıp Hello World! yazdıralım.

```python
>>>print("Hello World!")
```
Bu, bir yazdırma ifadesi örneğidir, ancak gerçekte kağıda bir şey yazdırmaz. Printer'ınız yoksa endişelenmeyin, bu ifadeyi kullanarak ekrana yazdırabilirsiniz. Doğayı sev ve ağaçları koru.

yukardakini yazdıktan sonra ekranda şöyle bir şey göreceksiniz:

```python
Hello World!
```
Programdaki tırnak işaretleri, görüntülenecek metnin başlangıcını ve sonunu belirtir; sonuçta görünmezler.

Parantezler, "print" fonksiyonun kullanıldığını belirtir. İleride "fonksiyonlar" konusuna değineceğiz.

Evet, ilk olarak ekrana bir şeyler yazdırmayı öğrendik. İlk başlıkta bahsettiğmiz 4 özellikten biri olan çıktıyı artık nasıl kullanmamız gerektiğini biliyoruz. Bundan sonra yaptığımız tüm işlemlerde python bizimle bu çirkin konsol üzerinden konuşacak. Yani biz ne dersek onu konuşacak. Umarız !

## Aritmetik İşlemler

Evet, ilk olarak ekrana bir şeyler yazdırmayı öğrendik. Pek bir şey değil ama başlangıç için yeterli. Şimdi de matematiksel işlemler yapmayı öğrenelim. Matematik bilgiğinizi varsayarak ilerleyeceğiz. Bilmiyorsanız onu da öğreteceğiz. Hayır şaka yapıyoruz. Matematik bilginiz varsa çok iyi. Yoksa da sorun değil. Yani bizim için sorun değil. Siz için sorun olabilir. Neyse, konumuza dönelim.

Python'da matematiksel işlemler yapmak için kullanabileceğimiz birçok operatör vardır. Bunlar:

* Toplama: +
* Çıkarma: -
* Çarpma: *
* Bölme: /
* Tam Bölme: //
* Mod: %
* Üs Alma: **


```python
>>> 5 + 3
8
```

```python
>>> 57-1
56
```


```python
>>> 6 * 9
54
```

```python
>>> 108 / 2
54.0
```
Şimdi neden önce 54 ama sonra 54.0. Sıkı durun bir sonraki bölümde bunu açıklayacağız.

He bir de unutmadan tam sayı bölme işlemi var. Bu işlemde bölüm sonucu tam sayı olarak döner. Örneğin, 10'u 2'ye böldüğümüzde 5.0 değil 5 döner. Bu işlem için "//" operatörünü kullanabiliriz.
```python
>>> 10 // 2
5
```

Üs alma işlemi için "**" operatörünü kullanabiliriz. Örneğin, 2'nin 3. kuvvetini hesaplayalım:
```python
>>> 2 ** 3
8
```
Mod alma işlemi için "%" operatörünü kullanabiliriz. Örneğin, 7'nin 3'e bölümünden kalanı bulalım:

```python
>>> 7 % 3
1
```
Bu işlemler, Python'da aritmetik işlemler yapmanın temel yollarıdır. Bu işlemleri kullanarak, daha karmaşık işlemler yapabiliriz ve yapacağız.

İşlem önceliği kuralları şöyledir:

Parantezler içindeki işlemler
Üs alma işlemi (**)
Çarpma (*) ve Bölme (/) işlemleri (sol'dan sağ'a)
Toplama (+) ve Çıkarma (-) işlemleri (sol'dan sağ'a)

```python
>>> 2 + 3 * 4 - (5 + 2)
7
```

## Değerler ve Tipler

Bir değer, bir programın işlediği temel şeylerden biridir, bir harf veya bir sayı gibi. Şimdiye kadar gördüğümüz bazı değerler 2, 42.0 ve 'Merhaba, Dünya!' gibi şeylerdir.

Bunların her birinin bir türü vardır. 2 bir tam sayıdır, 42.0 bir ondalık sayıdır ve 'Merhaba, Dünya!' bir dizedir. Bu türler, değerlerin nasıl yorumlanacağını ve nasıl işleneceğini belirler. Bunları bir kere öğrenmekte fayda var. Kimse anasının karnından programcı olarak çıkmıyor.
Merhaba anne, benim tipim int.

Her neyse benim gibi unutkan biriyseniz, python bunları sizin için hatırlayacaktır.

Python'da, bir değerin türünü öğrenmek için type() fonksiyonunu kullanabiliriz. Örneğin:

```python
>>> type(2)
<class 'int'>
```

```python
>>> type(42.0)
<class 'float'>
```

```python
>>> type('Merhaba, Dünya!')
<class 'str'>
```

Burada class diye gördüklerinizi kategori gibi düşünebilirsiniz. Yani int tam sayıları, float ondalık sayıları, str ise stringleri temsil ediyor. Bu isimler ingilizcelerinden geliyor.
Genel kültür : 
* int -> integer -> tam sayı
* float -> floating point -> ondalık sayı
* str -> string -> karakter dizisi

 Stringler hakkında daha sonra konuşacağız. Şimdilik sadece bir değer olduğunu ve tırnak işaretleri ile çevrildiğini bilmemiz yeterli.

Yetmez ama evet. Python'da bir değerin türünü öğrenmek için type() fonksiyonunu kullanabiliriz.
```python
>>> type(True)
<class 'bool'>
```

```python
>>> type(False)
<class 'bool'>
```

Kafanız henüz karışmadıysa diye bir kaç örnek daha vereceğiz.

```python
>>> type(None)
<class 'NoneType'>
```

```python
>>> type(type(2))
<class 'type'>
```
    ```python
>>> type('2')
<class 'str'>
```
Hmm bu biraz yanlış gözüküyor ama python hata yapmaz genelde siz hata yaparsınız. Evet bazen kabullenmesi çok zor olacak. Hatta yemin edebilecek kadar emin olacaksınız. Bu hatanın sebebi bilgisayar diyeceksiniz. Sonra yine siz çıkacaksınız. Geri döndük!  Bu bir string değil miydi ? Evet, ama tırnak işaretleri ile çevrilmemiş. Bu yüzden python bunu bir değer olarak algıladı. Bu konuyu daha sonra açıklayacağız.

Gitmden son bir bilgi daha verelim. Çok uzun sayıları yazmanız gerektiğinde aşağıdaki gibi yazabilirsiniz. Bu şekilde yazmak daha kolay olacaktır.

```python
>>> 1_000_000_000
1000000000
```

Python bu alt çizgileri görmezden gelir. Bu şekilde yazmak daha kolay olacaktır. Virgül kullanmak yok. 

## Ödevler

Eğer 40 yaşınıza geldiyseniz ve patronunuz size python öğrenmelisin dedi diye öğreniyorsanız, ödev kavramından oldukça uzaklaşmış olabilirsiniz. 20 yaşında liseden çıktıysanız işler daha kolay. Ödevlerinizi yapın. Yoksa sınıfta kalırsınız.

Yeni bir şeyler öğrenirken pratik yapmak dışında bir programlama yöntemi yoktur. Bol bol hata yapacağız. Hatanız bol olsun. 

Biraz deneysel olacağız. Ödevlerinizi yaparken kendi çözümünüzü bulmaya çalışın. Eğer çözümünüzü bulamazsanız, çözümümüzü inceleyebilirsiniz. Tabi çözüm verdiysek. Muhtemelen vermeyeceğiz.

Şimdi yapmanızı istediğimiz hatalardan bazılarını gözünüze sokalım.


- Bir yazdırma ifadesinde, parantezlerden birini veya her ikisini de çıkardığınızda ne olur?
- Bir dize yazdırmaya çalışırken, tırnak işaretlerinden birini veya her ikisini de çıkardığınızda ne olur?
- Negatif bir sayı yapmak için eksi işareti kullanabilirsiniz, örneğin -2. Artı işareti önünde ne olur? 2++2 ne anlama gelir?
- Matematik notasyonunda, başında sıfır olan sayılar kabul edilir, örneğin 09. Bunu Python'da denerseniz ne olur? 011 ne olacak?
- İki değeri arasında herhangi bir işlem olmadan bırakırsanız ne olur?
- Python yorumlayıcısını kullanarak aşağıdaki soruları cevaplayın:
  - 60 dakika 30 saniye kaç saniyedir?
  -  5 kilometrede kaç mil vardır? İpucu: Bir milde 1,61 kilometre vardır.
  - 10 kilometrelik bir yarışı 42 dakika 42 saniyede koşarsanız, ortalama hızınız saatte kaç mil olur? Ortalama hızınız milde dakika ve saniye cinsinden nedir?

Ödevlerinizi yapın. Yoksa sınıfta kalırsınız. - Civan

## Hazırlayanlar

* [Civan Doğan]



