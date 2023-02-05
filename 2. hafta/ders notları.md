# print() fonkisyonu
print fonksiyonunun görevi ekrana çıktı vermeyi sağlar
metinsel ifadeler '' veya "" içerisinde yazılır
# parametreler
## sep parametresi
sep ifadesi seperatorün kısaltmasıdır ve ayraç feya ayırıcı anlamı gelir ve ekrana basılacak ögeler arasına hangi karakterin yerleştirileceğini göterir. print fonkisyonun içine direk göülü olarak bulunur. yani kulanmanın veya kulnanmamanın bir önemi yoktur.
## end parametresi
sep parametesi gibi print() fonkisyonunun içinde gömülü olarak hep bulunur. 'end' parametresi ise bu parametrelerin sonuna neyin geleceğini belirler.

### not1
üstteki her iki parametrede printin içinde direk tanımldıır yani vardır ama "" içindeki değer hep boştur. yani yazılmaığı zaman şu sekilde var olurlar:
- **print(" hello world" , sep="", end="")**
### not2
eğer print içersinde ' ile ayrılması gereken bir şey varsa print " ile yazılmalıdır. bu yüzden genellikle "" kullanman daha sağlıklı olacaktır.
- ex: *yanlış* print('ahmet'in telefonu') , *doğru* print(" ahmet'in telefonu")
### not3
syntaxerror = yazım hatası
- ex: print "hello world" burada parantez kullanmadığım için syntaxerror alacağım.
### not4
.py uzantılı dosyalarda çoklu yorum satırı içim ''' kullanılır
- ex: ''' bla bla bla  ''' 

# değişkenler
değişkenler bir verinin deieğerini saklamayı sağlar.
verilerin sonradan değiştirilmesine olanak sağlar. 
kodlar sırasıyla çalışır.

## değişken tanımlama kuralları
- 1orkun = hatalı adlanrıma + bu bir syntaxerror hatasıdır.
- orkun1 = doğru adlandırma
- _orkun = doğru adlandırma

### not1 
Değişken adlandırırken türkçe karakter kullanmamaya dikkat et.
değişkenler büyük küçük harfe duyarlıdır.
değişken adlandırırken boşluk yerine _(snake_case) kullanabilirsin.
- ex: orkun_aktai = "bekar"
camelCase adlandrıma da (1. kelimenin ilk harfi küçük 2. ise büyük yazma) kullanabilirsin.
- ex: orkunAktas = "bekar"

# type() fonksiyonu
bir değişkenin integor, float, string ya da boolean olup olmadığını verir. yani veri tipini verir.

## sayı veri türleri
- int 
tam sayıları temsil eder.
mesela 5 10 20 -50
- float
ondalık sayıları temsil eder.
mesela 21.0 3.7 9.5 -7.4

# string
metinsel ifadelerdir ve '' / "" / '''''' şeklinde yazılmaları gerekir.
kaç tırnak ile başlandıysa o sayıda bitirilmelidir.
- ex: degisken = "altı" [ doğru kullanım]
- ex: degisken = "altı' [ yanlış kullanım]
**yazılımda index 0'dan başlar sola doğru ise -1'den başlar.**
- ex: degisken = "orkun", 0. index = o / 1. index = r / -1. index = n

# input() fonskiyonu
kullanıcıdan veri girişi almamızı sağlar.
input ile veri alırken string gibi davranır bu yüzden sayı alcaksan int ya da float kullan.


