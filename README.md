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

### 🎮 Türlerdeki Oyun Sayıları
![Türlerdeki Oyun Sayıları](01.png)

### 💰 En Çok Satış Yapan Türler
![En Çok Satış Yapan Türler](02.png)

### 🕹️ En Çok Satış Yapan Platformlar
![Platform Satışları](03.png)

### 🏢 En Çok Satış Yapan Yayıncılar
![Yayıncılar](04.png)

### 📊 Yıllara Göre Global Satışlar
![Yıllık Satış Trendleri](05.png)

### 🌍 Bölgelere Göre Toplam Satışlar
![Bölgesel Satışlar](06.png)

### 🌐 Türlere Göre Bölgesel Dağılım
![Tür-Bölge Dağılımı](07.png)

### 📉 Yıllara Göre Tür Bazlı Satış Trendleri
![Yıllık Tür Trendleri](08.png)

### 🧩 Platforma Göre Tür Dağılımı
![Platform-Tür Dağılımı](09.png)

## 📌 Dosya Yapısı
```
├── vgsales.csv                 # Ham veri
├── Untitled.ipynb             # Veri analizi notebook'u
├── README.md                  # Proje açıklaması (bu dosya)
├── 01.png ~ 09.png            # Görseller
```

## 📚 Nasıl Çalıştırılır?
```bash
# Ortamı oluştur
pip install -r requirements.txt

# Jupyter Notebook aç
jupyter notebook Untitled.ipynb
```

## 📊 Sonuçlar
- `Action` ve `Sports` türleri, oyun sayısı ve satış açısından öne çıkıyor.
- `PS2`, `X360` ve `Wii` gibi platformlar en yüksek satışlara sahip.
- Japonya'da RPG türü öne çıkarken, Kuzey Amerika'da Shooter türü daha popüler.
- 2005–2010 yılları arasında satışlar zirve yaptı.