# Hisse Senetlerinin Sektörel Benzerlik Analizi ve Sınıflandırma Modeli Geliştirilmesi

## Proje Açıklaması
Bu proje, hisse senetlerini sektörlerine göre analiz ederek benzerliklerini incelemek ve bir sınıflandırma modeli geliştirmek amacıyla oluşturulmuştur. Python ve çeşitli makine öğrenmesi kütüphaneleri kullanılarak finansal veriler işlenmiş, özellik mühendisliği uygulanmış ve farklı modeller test edilerek en iyi sonuç alınmaya çalışılmıştır.
Bu proje, Milli Teknoloji Akademisi Yapay Zeka Uzmanlık Programı Veri Yoğun Uygulamalar dersleri kapsamında yapılması istenmiştir.

## Veri Seti
Veriler `yfinance` API'si ve web scraping yöntemleri ile `stockanalysis.com` üzerinden çekilmektedir. Sektör ve endüstri bazında hisse senetlerinin finansal verileri toplanarak analiz edilmiştir.

## Kullanılan Modeller ve Yöntemler
Projede aşağıdaki yöntemler kullanılmıştır:
- **Özellik Seçimi:** Korelasyon tabanlı özellik eleme, `DropCorrelatedFeatures` ve `SmartCorrelatedSelection`
- **Makine Öğrenmesi Modelleri:**
  - Random Forest
- **Özellik Mühendisliği:** `tsfresh` ile zaman serisi özellik çıkarımı

## Sonuçlar
Modelin performansı `accuracy_score`,`classification_report` gibi metrikler ile değerlendirilmiştir. Sonuçlar, hangi modelin daha iyi sınıflandırma yaptığına dair analizler içermektedir.
