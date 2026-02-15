# Smart City Traffic Analysis

Bu proje, şehir içi trafik verilerini analiz etmek amacıyla geliştirilmiş modüler bir Python uygulamasıdır.  
Şehirler için trafik yoğunluğu analizi yapar ve farklı analiz stratejileri ile sonuç üretir.

Proje ekip çalışması kapsamında geliştirilmiştir ve yazılım tasarım prensiplerine dikkat edilerek hazırlanmıştır.

 Proje Mimarisi
Kod yapısı katmanlı ve modüler olacak şekilde tasarlanmıştır:

- **models/** → Veri sınıfları
- **services/** → İş mantığı katmanı
- **utils/** → Yardımcı araçlar
- **main.py** → Uygulamanın giriş noktası
- 

Kullanılan Yazılım Tasarım Desenleri
- **Factory Pattern** → Şehir nesnelerinin oluşturulması
- **Strategy Pattern** → Farklı analiz yöntemlerinin uygulanması
- **Service Layer** → İş mantığının ayrıştırılması

 Projenin Özellikleri
- Trafik verilerini okur ve işler
- Şehre özel nesne üretimi yapar
- Farklı analiz stratejileri uygulanabilir
- Modüler ve genişletilebilir yapıdadır
- Temiz kod prensiplerine uygun tasarlanmıştır


Nasıl Çalıştırılır?
1. Proje klasörüne gidin:
```bash
cd trafik_analizi
python main.py
