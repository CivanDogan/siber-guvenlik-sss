<a name="top"></a>  

 
 

 
 

---  

 
 

<h1 align="center">Python Bölüm 2</h1> 

 
 
 

## İçindekiler 

 
 

- Değişkenler 

- İfadeler 

 
 

## Değişkenler 

 
 

Programlamanın gücü değişkenlerden geçer. Bunları bir değere işaret eden isimler gibi düşünebiliriz. Yada şöyle. 

 
<image src="Belgeler/Dokumanlar/Python/resimler/GettyImages-553331677.webp" width="400" height="300">


Partiye gelip geçici olarak kendi bardağınızı almak gibi. Sen gelirsin, bardağın üstüne adını yazar ve içeceklerini oraya koyarsın. Parti boyunca senin içeceğini kimse alamaz çünkü onun senin olduğunu herkes bilir. İşte bu bardak bir değişken gibi. Adını koyarsın (değişken adı), içine bir şeyler koyarsın (değişken değeri) ve sonra onu kullanabilirsin. 

 
 

Fakat, değişkenlerin bazı kuralları vardır, tıpkı partideki bardaklar gibi. Her bardağın benzersiz bir ismi olmalı. Yani, iki kişi aynı isimle bardak alamaz. Bu, programlama dillerinde de böyledir. İki aynı isimli değişken oluşturamazsın, yoksa program karışır ve "SA, hangi bardak senin, hangisi Ahmet'in?" diye sorar. 

 
 

Ayrıca, her değişkenin bir tipi vardır. Yani, bir bardağa ne koyabileceğini belirler. Örneğin, bir bardağa sıcak çorba koymayı düşünürsen, plastik bir bardak yerine seramik bir kase alırsın. Yani öyle yaptığını umuyoruz.  

Parti bitince bardakları yerine bırakmak da lazım ama Python bunu sizin için yapacak. O yüzden siz sadece içeceğinizi koyun ve sonra onu kullanın. 

 
 

### Değişkenlerin Adlandırılması 

 
 

Python'da değişkenler oluşturmak için, değişken adını yazın, sonra eşittir işaretini ve sonra da değerini yazın. Örneğin: 

 
 

```python 

>>> x = 2 

>>> y = 3.0 

>>> z = 'Merhaba, Dünya!' 

``` 

 
 

Bu, değişkenlerin nasıl oluşturulacağına dair bir örnektir. İlk satırda, x adında bir değişken oluşturduk ve ona 2 değerini atadık. İkinci satırda, y adında bir değişken oluşturduk ve ona 3.0 değerini atadık. Son satırda, z adında bir değişken oluşturduk ve ona 'Merhaba, Dünya!' değerini atadık. 

 
 

### Değişkenlerin Kullanılması 

 
 

Değişkenler oluşturduktan sonra, onları kullanabilirsiniz. Örneğin: 

 
 

```python 

>>> print(x + y) 

5.0 

>>> print(z) 

Buraya ne geleceğine dair bir tahmininiz var mı ? 

``` 

 
 

İlk satırda, x ve y değişkenlerini topladık ve sonucu yazdırdık. İkinci satırda, z değişkenini yazdırdık. 

 
 

### Değişkenlerin Değerlerini Değiştirmek 

 
 

İşte şimdi eğlenceli kısım. Değişkenlerin değerlerini değiştirebilirsiniz. Örneğin: 

 
 

```python 

>>> x = 2 

>>> print(x) 

2 

>>> x = 3 

>>> print(x) 

3 

``` 

 
 

İlk satırda, x adında bir değişken oluşturduk ve ona 2 değerini atadık. İkinci satırda, x değişkenini yazdırdık. Üçüncü satırda, x değişkeninin değerini 3 olarak değiştirdik. Son satırda, x değişkenini yazdırdık. 

 
 

Peki başka şimdi şöyle yaparsak ne olur ?  

 
 

```python 

>>> x = 2 

>>> x+29 

31 

>>> print(x) 

``` 

 
 

Burada x'in değeri ne olur ? 

 
 

Python shell'inde deneyin. (Yeni bilgi Shell nedir ? Zaten biliyorsunuz. Ufak bir araştırma ile eski dostunuzu bulabilirsiniz. Bulduktan sonra vedalaşmayı unutmayın. Lakin yakında ondan ayrılacağız. ) 

 
 

## Değişkenlerin Kullanımı ve İlişkileri 

 
 

```python 

>>> x = 2 

>>> y = 3 

>>> x = x * y 

>>> print(x) 

``` 

 
 

Burada x'in değeri ne olur ? 

İlk satırda, x adında bir değişken oluşturduk ve ona 2 değerini atadık. İkinci satırda, y adında bir başka değişken oluşturduk ve ona 3 değerini atadık. Üçüncü satırda, x değişkeninin değerini, x ve y değişkenlerinin toplamı olan 5 olarak değiştirdik. Son satırda, x değişkenini yazdırdık ve sonucun 5 olduğunu gördük. 

 
 

Peki ya bu kodu denerseniz ne olur? 

 
 

```python 

>>> x = 2 

>>> y = 3 

>>> z = x + y 

>>> print(z) 

``` 

 
 

Bu kodda x ve y'nin toplamını z adında bir değişkene atıyoruz ve sonra z'yi yazdırıyoruz. Z'nin değeri ne olacaktır?  

 
 

## Ödevler  

 
 

Evet evet evet ! Ödevlerimiz var.  

 
 

Alıştırma 2.1. Önceki bölümden tavsiyemi tekrarlıyorum, yeni bir özellik öğrendiğinizde, hatalar yapmak için interaktif modda denemeniz gerekir. 

 
 

- Gördük ki n = 42 legal bir ifade. Peki ya 42 = n denerseniz ne olur? 

- Peki ya x = y = 2? 

- Bazı dillerde her ifade noktalı virgül (;) ile biter. Python'da bir ifadenin sonuna noktalı virgül koyarsanız ne olur? 

- Peki bir ifadenin sonuna nokta koyarsanız ne olur? 

- Matematik gösteriminde x ve y'yi şu şekilde çarpabilirsiniz: xy. Bunu Python'da denerseniz ne olur? 

 
 

#### Geçen üniteden toplayarak gelmek isteyenler için ekler 

 
 

- Diyelim ki bir kitabın kapak fiyatı 130 TL, ancak kitapevleri %35 indirim alıyor. Kargo ilk kopya için 5 TL, her ek kopya için ise 2 TL. 75 kopya için toplam toptan maliyet nedir? 
 

"Ödev yapmak, evin içinde kaybolan çoraplar gibi, her zaman ertelenebilecek bir şeydir." - CivanGPT 

Sonraki : [Bölüm 3](/Belgeler/Dokumanlar/Python/Python3.md) 

 
 

## Hazırlayanlar  

 
 

 
 

* [Civan Doğan]  

 
 

 