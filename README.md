# PatikaDev-Logo-Net-Bootcamp-Homework-1

* Bir adet form oluşturulacak. Form içinde ad soyad email ve password için input olacak.(Login ekranı gibi)
* Api yazılacak ve  HttPost methodunu kullanacak.
* Email validasyonda girilen email uygun olup olmadığı kontrol edilsin.
* Password için uzunluk kontrolü 8 karakter olacak en az 1 büyük harf en az 1 karakter en az bir sayı olacak.
* Dataannotions da RegEx attribute custom attribute yazabilirsiniz validasyonlar için.
* Hata mesajları Türkçe olmalıdır.
* Response tipi için class yazılacak.
* Prop olarak Success error ve data olacak.
* Başarılı postlar success true data giriş işlemi başarılı error null gelecek.
* Hatalı postlar succes false data null error hatalı giriş dönecek
* Tüm alanlar zorunlu olmalıdır.

* Referans : https://stackoverflow.com/questions/16796445/net-regex-specific-to-net-c-sharp-dataannotations

<br>

## Yapılanlar

* Login sayfası için View oluşturuldu
* Controller içine Login sayfası için HTTP GET ve HTTP POST metodları eklendi
* Response, Login ve ResponseViewModel modelleri oluşturuldu
* Fluent Validation kütüphanesi projeye eklendi ve validasyon için LoginValidator sınıfı oluşturuldu
* LoginValidator sınıfı içine Login sınıfı elemanlarının validasyonu kuralları girildi
* Email ve şifre validasyonu için Regex kullanıldı
