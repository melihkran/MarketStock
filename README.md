# SuperMarketStorage - Market Stok Takip Sistemi

Bu proje, bir market için geliştirilmiş, Java ve Spring Boot tabanlı bir konsol uygulamasıdır.

## Özellikler

- Ürün ekleme
- Ürün listeleme
- Stok güncelleme
- Ürün arama
- Satış Geçmişini Sıfırlama
- SQLite veritabanı desteği

## Teknik Detaylar

- Java 8
- Spring Boot 2.7.0
- SQLite veritabanı
- Maven

## Kurulum ve Çalıştırma

### 1. Projeyi Derleme

Projeyi derlemek ve çalıştırılabilir `.jar` dosyasını oluşturmak için terminalde aşağıdaki komutu çalıştırın:

```bash
mvn clean package
```

Bu komut, `target` klasörü altında `market-stok-takip-1.0-SNAPSHOT.jar` adında bir `.jar` dosyası oluşturacaktır.

### 2. Uygulamayı Çalıştırma

Oluşturulan `.jar` dosyasını çalıştırmak için aşağıdaki yöntemlerden birini kullanabilirsiniz:

#### Windows için (.bat dosyası)

Projeyi kolayca çalıştırmak için `run.bat` dosyasına çift tıklamanız yeterlidir. Bu dosya, uygulamayı bir komut istemcisi penceresinde başlatır ve uygulama kapandıktan sonra pencerenin açık kalmasını sağlar.

#### PowerShell için (.ps1 script)

PowerShell üzerinden çalıştırmak isterseniz, `run.ps1` scriptine çift tıklayabilirsiniz. Bu script de uygulamayı bir PowerShell penceresinde başlatır ve uygulamanın çıktısını görmenizi sağlar.

### Not:

Spring Boot'un başlangıç logları ve banner'ı gizlenmiştir. Bu sayede uygulama daha sade bir konsol çıktısıyla başlayacaktır.

## Veritabanı

Uygulama SQLite veritabanı kullanmaktadır. Veritabanı dosyası `data/market.db` konumunda bulunmaktadır.

## Kullanım

Uygulama başlatıldığında konsol üzerinden aşağıdaki işlemleri yapabilirsiniz:

1. Ürün Ekle
2. Ürün Listele
3. Stok Güncelle
4. Ürün Ara
5. Satış Geçmişini Sıfırla
6. Çıkış

## Geliştirici

Bu proje marketlerin deposundaki ürünlerin takibi için geliştirilmiştir.

## Neden Deploy Edilmedi?

Bu bir terminal uygulamasıdır, tarayıcıdan değil terminalden yaşar. Web’e taşınabilir bir arayüzü olmadığı için deploy edilmemiştir, ama çalıştırmak oldukça kolaydır. 😊
