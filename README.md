### Prototype Design Pattern ###

![prototypedesignpattern](https://github.com/ahmetvatansever/PrototypeDesignPattern/assets/24367205/b61f175e-0dc3-4a11-99de-9ff8aa6af941)


Prototype Design Pattern, Varoluşsal(Creatinoal) tasarım desenlerinden biridir.
Aynı sınıftan üretilecek olan ve pek çok ortak özelliği bulunan benzer nesnelerin üretimi sırasında
gerçekleşebilecek karışıklıkları engellemek ve üretim maliyetini azaltmak amacı ile kullanılır.

Karmaşık nesneleri sıfırdan oluşturmak yerine, hali hazırda elde var olan nesnelerden kopyalanarak
elde etme yonuna gidilebilir. Durumu kopyalanarak çoğaltılan nesne prototip ya da örnek nesnedir.

Prototip-örnek olarak oluşturulan nesne, aynı sınıftan diğer nesneler için bir başlangıç noktası olur.
Kopyalama ile elde edilen nesnenin durumu prototip nesne ile aynıdır.
Yeni nesne üzerinde yapılmak istenen değişiklikler nesne üzerindeki set metotları ile yapılır.
