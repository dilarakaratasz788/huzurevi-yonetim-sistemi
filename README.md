Huzurevi İlaç Takip Sistemi
Bu program, huzurevinde konaklayan sakinlerin kişisel bilgilerini tutmak ve günlük ilaç saatlerini takip ederek hatırlatma yapmak amacıyla C dili ile geliştirilmiştir.

📖 Proje Hakkında
Sistem, kullanıcıdan alınan güncel saat bilgisini kullanarak kayıtlı sakinlerin ilaç saatlerini kontrol eder. Eğer o an bir sakinin ilaç saati gelmişse, sistem otomatik olarak bir uyarı mesajı görüntüler.

✨ Özellikler
Kişisel Veri Yönetimi: Sakinlerin adı, soyadı, yaşı, kilosu ve boyu gibi demografik bilgileri saklar.

Dinamik İlaç Takibi: Her sakin için 50 adede kadar farklı ilaç saati tanımlanabilir.

Gerçek Zamanlı Kontrol: Girilen güncel saate göre sistem anlık bildirim yapar.

Sınırlandırılmış Kapasite: Bellek yönetimi ve düzen için maksimum 15 kişilik konaklama kapasitesine sahiptir.

🛠️ Teknik Detaylar
Kod içerisinde aşağıdaki temel yapılar kullanılmıştır:

Yapılar (Structs): struct kisi yapısı ile karmaşık veriler bir arada tutulmuştur.

Sabitler (Macros): MAX_ILAC_SAATI (50) ve kalacakMaksimumkisi (15) gibi değerler ön işlemci komutları ile yönetilmektedir.

Modülerlik: Veri girişi (bilgilerial), ekrana yazdırma (bilgileriYazdir) ve kontrol işlemleri (ilacSaatiBildirim) fonksiyonlara bölünmüştür.

🚀 Kullanım
Programı Başlatın: Sizden ilk olarak 0-23 arası güncel saati girmeniz istenecektir.

Kişi Sayısını Belirleyin: Kayıt edilecek toplam sakin sayısını girin.

Veri Girişi Yapın: Her bir sakin için istenen kişisel bilgileri ve ilaç saatlerini sırasıyla doldurun.

Sonuç: Program tüm sakinlerin listesini dökerek, ilaç saati gelenler için ekranda özel bir uyarı mesajı gösterecektir.

💻 Kurulum
Proje standart C kütüphanelerini (stdio.h) kullanmaktadır. Herhangi bir C derleyicisi ile çalıştırılabilir.
