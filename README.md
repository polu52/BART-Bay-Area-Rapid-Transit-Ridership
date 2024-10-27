# BART (Bay Area Rapid Transit) Ridership

### Proje Açıklaması

BART, "Bay Area Rapid Transit" anlamına gelen ve San Francisco Bay Area bölgesine hizmet veren bir toplu taşıma sistemidir. BART, haftanın beş günü ortalama 423.000 yolcu taşımakta olup ABD'nin en yoğun beşinci hızlı transit sistemidir. Bu proje, San Francisco BART metro istasyonlarının yoğunluk analizini yaparak istatistiksel ve tahmine dayalı modelleme yöntemleri ile çeşitli soruları yanıtlamayı amaçlamaktadır.

### Veri Kümesi

Bu proje, [BART Ridership veri kümesini](https://www.kaggle.com/datasets/saulfuh/bart-ridership) kullanmaktadır. Veri, 2016 ve 2017 yıllarını kapsayan günlük BART istasyonu hareket bilgilerini içermektedir.

![San Francisco BART Haritası](https://metroeasy.com/wp-content/uploads/2023/05/San-Francisco-BART-Map.gif)

### Proje Soruları

#### Veri Analitiği Soruları:
- Hangi BART istasyonu en yoğun?
- En az popüler olan BART hattı hangisi?
- Berkeley'den SF'ye oturarak gitmek için en iyi saat ne zaman?
- Haftanın en yoğun günü hangisi?
- Gece geç saatte BART'ı kaç kişi kullanıyor?

#### Veri Bilimi Soruları:
- **Soru A**: Her istasyon arasındaki düz çizgi mesafesini hesapla.
- **Soru B**: İki istasyon arasındaki yolcu sayısını tahmin edebilen bir model oluştur.

### Kullanılan Kütüphaneler

- **pandas**: Veri işleme ve analiz
- **numpy**: Sayısal hesaplamalar
- **matplotlib** ve **seaborn**: Veri görselleştirme
- **plotly**: Etkileşimli grafikler oluşturma
- **geopy**: Coğrafi hesaplamalar
- **prophet**: Zaman serisi tahminleme

### Kurulum

Projeyi çalıştırmak için aşağıdaki adımları takip edin:

1. Gerekli kütüphaneleri yükleyin:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly geopy prophet
   ```

2. Notebook'u çalıştırarak veri analitiği ve tahmine dayalı analizleri yapın.

### Proje Yapısı

- **BART(Bay Area Rapid Transit) Ridership.ipynb**: Proje ile ilgili tüm analiz ve modelleme adımlarının bulunduğu Jupyter Notebook dosyası.
