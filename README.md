Smart City Traffic Analysis

Bu proje, şehir içi trafik verilerini analiz etmek amacıyla geliştirilmiş modüler bir Python uygulamasıdır.
Amaç; farklı şehirler için trafik yoğunluğu, analiz stratejileri ve servis katmanı üzerinden veri işleyerek sonuç üretmektir.

Proje ekip çalışması kapsamında geliştirilmiştir ve yazılım tasarım prensiplerine dikkat edilerek yapılandırılmıştır.

Proje Mimarisi

Kod yapısı katmanlı ve modüler olacak şekilde tasarlanmıştır:

models/ → Veri sınıfları

services/ → İş mantığı

utils/ → Yardımcı araçlar

main.py → Uygulamanın giriş noktası

Projede yazılım tasarım desenleri kullanılmıştır:

Factory Pattern → Şehir nesnelerinin oluşturulması

Strategy Pattern → Farklı analiz yöntemlerinin uygulanması

Service Layer → İş mantığının ayrıştırılması

Projenin Özellikleri

Trafik verilerini okur ve işler

Şehre özel nesne üretimi yapar

Farklı analiz stratejileri uygulanabilir

Modüler ve genişletilebilir yapı

Loglama desteği

Nasıl Çalıştırılır?

Proje klasörüne gidilir.

Terminal üzerinden:

python main.py
