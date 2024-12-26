# Kütüphane Yönetim Sistemi

Bu proje, Kütüphane Yönetim Sistemi geliştirmek için Java programlama dili kullanılarak oluşturulmuştur. Proje, tasarım desenlerini kullanarak modüler ve genişletilebilir bir yapı sunar. Amaç, kütüphane işlemlerini kolaylaştırmak ve kullanıcılar için daha işlevsel bir sistem sağlamaktır.

## Genel Yapı

### Kullanıcı Yönetimi

- Sisteme giriş yapma veya yeni kullanıcı kaydı oluşturma.
- İki farklı kullanıcı rolü desteklenir:
  - **Öğrenciler**: Kitap ödünç alma, iade etme, kitapları listeleme.
  - **Personel**: Kitap ekleme, güncelleme ve silme işlemleri.

### Kitap Yönetimi

- Kitapların durumu (rafta, ödünç alınmış, kayıp) takip edilebilir.
- Kitaplar adına, yazara veya kategoriye göre aranabilir.
- Kullanıcılar kitaplara yorum yapabilir ve puan verebilir.

### Projede Kullanılan Tasarım Desenleri

- **Singleton**: Veritabanı bağlantısı için tek bir örnek oluşturulmasını sağlar.
- **Factory**: Kullanıcı nesnelerinin (öğrenci veya personel) oluşturulmasını yönetir.
- **Strategy**: Farklı arama stratejileri (yazara, ada, kategoriye göre) sağlar.
- **State**: Kitapların durumlarını (rafta, ödünç alınmış, kayıp) yönetir.
- **Observer**: Kitap durum değişikliklerinde bildirimler gönderir.
- **Decorator**: Kitaplara yorum ve puan ekleme işlevlerini genişletir.

### Arayüz

- Kullanıcı dostu bir grafik arayüz sunulmuştur.
- **Swing** kütüphanesi kullanılarak geliştirilmiştir.
- Giriş ekranı, kayıt ekranı ve kitap yönetimi ekranları gibi farklı modüller içerir.


### Proje Arkadaşları:
- YÜKSEL UYGUN , GitHub Linki: https://github.com/YukselUygun/KutuphaneSistemii
- ZEYNEP UĞUZ , GitHub Linki: https://github.com/zeynepuguz/KutuphaneSistemi


