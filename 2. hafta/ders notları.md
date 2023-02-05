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