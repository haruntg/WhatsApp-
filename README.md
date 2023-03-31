Amaç:
Bu kod, kullanıcının klavyeden girdiği numarayı alır ve WhatsApp web sitesine giderek, belirtilen numaraya mesaj göndermeye hazır hale getirir.

Kullanım:
Kodu bir metin editörüne yapıştırın ve "whatsapp.bat" gibi bir isim vererek kaydedin.

Dosyayı çalıştırmak için, dosyaya çift tıklayın.

"Numara girin:" mesajı gösterildiğinde, istediğiniz numarayı girin ve Enter tuşuna basın.

Kod, otomatik olarak "https://wa.me/" adresine giderek, seçilen numaraya mesaj göndermek için hazır hale getirecektir.

Kod Açıklaması:
@echo off: Bu satır, komut dosyasının çalıştırılması sırasında ekrana yazdırılan tüm komutların gösterilmesini durdurur.

set /p numara="Numara girin: ": Bu satır, kullanıcıdan numarayı girmesini istemek için bir mesaj gösterir ve kullanıcının klavyeden girdiği numarayı "numara" değişkenine atar.

set "numara=+9%numara%": Bu satır, kullanıcının girdiği numaranın başına "+9" ekler ve numara değişkenini günceller.

start https://wa.me/%numara%: Bu satır, "start" komutunu kullanarak, otomatik olarak WhatsApp web sitesine gitmek ve seçilen numaraya mesaj göndermek için bir bağlantı açmak için kullanılır.

Uyarılar:
Bu kod, yalnızca WhatsApp Windows uygulaması yüklü olan bilgisayarlarda çalışır.

Bu kodu kullanmadan önce, hedef kişinin izni olmadan WhatsApp üzerinden mesaj göndermenin yasalara aykırı olabileceğini unutmayın.

Bu kodu yalnızca test amaçlı olarak kullanın veya yasal olmayan aktivitelerde kullanmayın.
