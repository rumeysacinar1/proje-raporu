 SEMAYS - E-Ticaret Üzerinden Satın Alma Tahmini

Bu projede bir e-ticaret sitesinde kullanıcıların satın alma alışkanlıklarını tahmin etmek için clickstream verilerine dayalı bir makine öğrenmesi modeli geliştirilmiştir.

 Proje Bileşenleri (Big Picture)
- **Frontend:** HTML/CSS/JS ile kategori ve ürün sayfaları
- **Backend:** PHP ile admin paneli ve veri kaydı (logs.txt, stats.json)
- **ML Pipeline:** Google Colab üzerinde Python/Scikit-learn ile Logistic Regression
- **API:** Flask tabanlı REST API ile tahmin sonuçları

 Kullanım
- `index.php` → Admin paneli
- `mlpipeline.py` → Model eğitimi
- `app.py` → REST API
- `logs.txt` → Ham kullanıcı hareketleri
- `stats.json` → İstatistik verisi

Rapor
Tüm proje detayları için `Rapor.pdf` dosyasını inceleyiniz.
