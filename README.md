XOX OYUNU

Bu proje, C++ dili kullanılarak Nesne Yönelimli Programlama (OOP) prensiplerine uygun şekilde geliştirilmiş klasik bir Tic Tac Toe (XOX) oyunudur. Oyuncular sırayla X ve O sembollerini 3x3'lük bir tahtaya yerleştirerek oyunu kazanmaya çalışıyor. Oyun, İnsan vs İnsan ve İnsan vs Bilgisayar modlarını içerir. Bilgisayar rastgele hamleler yapar.

Kullanılan Teknolojiler

C++
Nesne Yönelimli Programlama (OOP)
Konsol (Terminal) Uygulaması
Proje Özellikleri

OOP temelli sınıf yapısı
3x3 oyun tahtası
Oyuncu adı girişi
Bilgisayara karşı oynama modu (rastgele hamle yapar)
Kazanma kontrolü (yatay, dikey, çapraz)
Beraberlik raporu
Geçersiz hamle kontrolü
Skorların oyuncu_skorları.txtkayıtlarına kaydedilmesi
Sınıf Yapısı

OyunNesnesi : Tüm görsel oyun öğeleri için soyut sınıflar ( draw(), erase()yöntemleri).
Oyuncu : İnsan oyuncunun adını ve köylerini yönetir.
BilgisayarOyuncu : Rastgele hamlesini yapan oyuncu.
Tahta : Oyun tahtasını ve kurallarını yönetir.
Oyun : Oyunun çeşitliliği, oyuncu sırasını ve skorları kontrol eder.
Oyun Kuralları

Oyuncular sırayla hamle yapar (X ve O).
Aynı satır, sütun veya çaprazda 3 sembol olan oyuncu oyunu kazanır.
Tüm bunları yapanlar kazananlar yoksa oyun berabere biter.
Bilgisayar oyuncusu rastgele hamle yapar.
Geçersiz girişler reddedilir ve tekrar dağıtılır.
