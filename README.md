# shoppingCart
# My Shopping Cart Projesi

Bu proje, bir alışveriş sepeti uygulamasının basit bir HTML, CSS ve JavaScript versiyonunu içermektedir.

## Nasıl Çalıştırılır

1. Bu projeyi bilgisayarınıza klonlayın veya ZIP dosyası olarak indirin.

2. İndirdiğiniz klasörü bir metin düzenleyici ile açın.

3. `index.html` dosyasını web tarayıcınızda açarak projeyi görüntüleyebilirsiniz.

![Proje Ekran Görüntüsü](ekranGifi.gif)

## Canlı Görüntü

Web sitesini canlı olarak görüntülemek için [buraya tıklayın](https://shoppingcart38.netlify.app/).




## Proje Açıklaması

Bu proje, bir alışveriş sepeti web uygulamasını temsil eder. Aşağıdaki özelliklere sahiptir:

- Ürünlerin listesi ve fiyatları.
- Sepete ürün eklemek ve çıkarmak.
- Toplam alışveriş tutarını gösterme.
- Sepeti temizleme seçeneği.

## Sepet Verilerini Saklama (localStorage)

Bu projede, kullanıcının sepetini ve ürünleri yerel depolama (localStorage) kullanarak saklıyoruz. Bu, kullanıcıların sayfayı yeniden ziyaret ettiğinde sepetlerinin korunmasını sağlar. İşte `localStorage` kullanımına dair daha fazla bilgi:

- **Ürünlerin Saklanması**: Projeyi ilk başlattığınızda, ürünler `localStorage` kullanılarak tarayıcıda saklanır. Bu, kullanıcıların farklı sekmeler veya tarayıcı oturumları arasında ürünlerin korunmasını sağlar.

- **Sepetin Saklanması**: Kullanıcılar ürünleri sepete eklediğinde, sepet verileri `localStorage`'a kaydedilir. Bu sayede kullanıcılar sayfayı yeniden ziyaret ettiğinde sepet içeriği hala mevcuttur.

- **Verilere Erişim**: Sepet ve ürün verilerine erişim için `Storage` sınıfını kullanıyoruz. Bu sınıf, `localStorage`'a veri eklemek, veri almak ve veriyi güncellemek için işlevler içerir.


## Kullanılan Teknolojiler

Bu proje aşağıdaki teknolojileri kullanmaktadır:

- HTML
- CSS
- JavaScript
- Bootstrap
- Font Awesome


