# 🎮 Video Game Sales Analysis

Bu proje, **Kaggle** üzerinden alınan [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales) veri seti kullanılarak, global çapta video oyunlarının satış performanslarını incelemektedir. Proje kapsamında veri temizleme, görselleştirme ve trend analizi gibi temel veri bilimi adımları uygulanmıştır.

## 🔍 Kullanılan Veri Seti

- **Kaynak:** Kaggle - Video Game Sales
- **Boyut:** 16.598 satır, 11 sütun
- **Öne çıkan sütunlar:**
  - `Name`: Oyun adı
  - `Platform`: Yayınlandığı platform
  - `Year`: Yayın yılı
  - `Genre`: Tür
  - `Publisher`: Yayıncı
  - `Global_Sales`, `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`: Bölgesel satışlar (milyon adet)

## 🛠️ Kullanılan Araçlar ve Kütüphaneler

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly Express

## 📈 Gerçekleştirilen Analizler

- Eksik Verilerin Analizi ve Temizlenmesi
- Oyun Türlerine Göre Satış Analizi
- Platform Bazlı Satış Trendleri
- Yayıncıların Satış Performansı
- Yıllara Göre Satış Eğilimleri
- Bölgesel Satışların Harita ile Gösterimi (Plotly)

## 🎯 Öne Çıkan Bulgular

- `Sports` ve `Action` türündeki oyunlar en çok satış yapan kategoriler arasında yer almaktadır.
- `Nintendo`, açık ara en çok satış yapan yayıncıdır.
- Satışlar 2005-2010 arasında zirve yapmıştır, ardından düşüş göstermiştir.
- En çok satış yapan platformlar arasında `PS2`, `X360`, `Wii`, `DS` ve `PS3` yer alır.
- Japonya'daki satış trendleri diğer bölgelere göre farklılık göstermektedir.

## 📌 Dosya Yapısı

```

├── Untitled.ipynb             # Veri analizi notebook'u
├── README.md                  # Proje açıklaması (bu dosya)

## 📊 Demo Görseller
Notebook içerisinde birçok görsel analiz yer almaktadır. Örneğin:
- Türlere göre satış grafiği
- Platformlara göre satış dağılımı
- Yıllara göre tür bazlı satış çizgileri
- Bölgesel satışların dünya haritası üzerinden görselleştirilmesi
```
