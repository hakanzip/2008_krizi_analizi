# 2008 Finansal Krizi Analizi

Bu proje, 2008 küresel finansal krizinin etkilerini finansal piyasalar ve makroekonomik göstergeler üzerinden incelemek için hazırlanmıştır. Çalışmanın amacı, kriz sürecinde S&P 500, Nasdaq gibi borsa endekslerinin, altın gibi güvenli liman varlıklarının ve çeşitli makroekonomik göstergelerin (ör. inşaat ruhsatları, makine siparişleri) nasıl bir seyir izlediğini görselleştirerek kriz dinamiklerini daha iyi anlamaktır. Ayrıca bu analizler, kriz dönemlerinin gelecekteki sinyallerini tespit edebilmek için bir temel oluşturmayı hedeflemektedir.

## Proje Yapısı
- `data/` : Tüm veri dosyaları (CSV formatında)
- `images/` : Üretilen grafikler ve görseller (PNG formatında)
- `notebook/` : Jupyter Notebook dosyası
- `requirements.txt` : Gerekli Python kütüphaneleri listesi
- `.gitignore` : Git'e eklenmeyecek dosyalar

## Kullanılan Veriler
`data/` klasöründe:
- GOLD.csv – Altın fiyatları
- IXIC.csv – Nasdaq endeksi
- GSPC (1).csv – S&P 500 endeksi
- macrodata.csv – Makroekonomik göstergeler
- Recession_Periods.csv – Resesyon tarihleri (NBER verisi)
- snpdiv.csv – S&P 500 temettü verileri
- sp-500-pe-r...ings-chart.csv – S&P 500 fiyat/kazanç oranları

## Kullanılan Kütüphaneler
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## Çalıştırma Adımları
1️⃣ Gerekli kütüphaneleri kur: