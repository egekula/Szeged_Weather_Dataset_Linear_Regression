# Szeged Hava Durumu Analizi

Bu proje, Szeged hava durumu verilerini kullanarak **Hissedilen Sıcaklık** (Apparent Temperature) değerini tahmin etmeyi amaçlar.

**Yapılan İşlemler:**
- Veri temizliği (eksik 'Precip Type' doldurma, hatalı 0 basınç değerlerini atma).
- Gereksiz sütunların çıkarılması ve özellik ölçeklendirme (StandardScaler).
- Linear Regression ve RidgeCV modellerinin eğitimi.

**Sonuçlar:**
Model, **%99 R2 skoru** ile çok yüksek bir doğruluk oranına ulaşmıştır.

**Kullanılan Dataset**
* https://www.kaggle.com/datasets/budincsevity/szeged-weather