# Market Stok Takip Sistemi

Bu proje, bir market için stok takip sistemi uygulamasıdır. Java ve Spring Boot kullanılarak geliştirilmiştir.

## Özellikler

- Ürün ekleme
- Ürün listeleme
- Stok güncelleme
- Ürün arama
- SQLite veritabanı desteği

## Teknik Detaylar

- Java 8
- Spring Boot 2.7.0
- SQLite veritabanı
- Maven

## Kurulum

1. Projeyi klonlayın
2. Maven bağımlılıklarını yükleyin:
   ```bash
   mvn install
   ```
3. Uygulamayı çalıştırın:
   ```bash
   mvn spring-boot:run
   ```

## Veritabanı

Uygulama SQLite veritabanı kullanmaktadır. Veritabanı dosyası `data/market.db` konumunda bulunmaktadır.

## Kullanım

Uygulama başlatıldığında konsol üzerinden aşağıdaki işlemleri yapabilirsiniz:

1. Ürün Ekle
2. Ürün Listele
3. Stok Güncelle
4. Ürün Ara
5. Çıkış

## Geliştirici

Bu proje marketlerin deposundaki ürünlerin takibi için geliştirilmiştir.
