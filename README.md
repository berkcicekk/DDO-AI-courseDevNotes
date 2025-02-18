# DDO-AI-courseDevNotes

## Ön hazırlık

#### pycharm

```http
  https://www.jetbrains.com/pycharm/
```
#### python

```http
  https://www.python.org/
```


# Gün1 Notlar

## Veri
Ham bilgi olup tek başına anlam ifade etmez, işlenerek enformasyon ve bilgiye dönüşebilir.

## Makine Öğrenimi (MÖ)
Bilgisayarların verilerden öğrenmesini sağlayan yapay zeka dalıdır. Kalıpları tanıyıp tahminler yapabilir.

## Derin Öğrenme (DÖ)
Makine öğreniminin bir alt dalıdır. Yapay sinir ağlarını kullanarak büyük veri setlerinden karmaşık desenleri öğrenir.

## Yapay Sinir Ağları (YSA)
İnsan beyninden esinlenen, düğümlerden oluşan ağlardır. Karmaşık problemleri çözmede etkilidir.

## Algoritma
Bir problemi çözmek için adım adım talimatlar dizisi.

## Veri Seti
Makine öğrenimi modellerini eğitmek ve test etmek için kullanılan veri grubudur.

## Model
Makine öğrenimi algoritmalarının öğrendiği kalıpları temsil eder ve tahmin yapmak için kullanılır.

## Eğitim & Test Süreci
- **Eğitim**: Modelin veri setinden öğrenmesi.
- **Test**: Modelin genelleme yeteneğini değerlendirme süreci.

## Performans Ölçütleri
- **Doğruluk**: Modelin doğru tahmin oranı.
- **Hassasiyet (Precision)**: Pozitif tahminlerin doğruluk oranı.
- **Geri Çağırma (Recall)**: Gerçek pozitifleri ne kadar doğru bulduğunu gösterir.
- **F1 Skoru**: Hassasiyet ve geri çağırmanın harmonik ortalaması.

## Aşırı Uyum (Overfitting) & Düzenlileştirme
- **Aşırı Uyum**: Modelin eğitim verisine fazla uyum sağlaması, yeni verilerde başarısız olması.
- **Düzenlileştirme**: Aşırı uyumu önlemek için kullanılan tekniklerdir (L1, L2).

## Çapraz Doğrulama (Cross-Validation)
Veri setinin farklı bölümlerinde modeli test ederek performansını artırma yöntemi.

## Hiperparametre & Optimizasyon
- **Hiperparametre**: Modelin öğrenme sürecini kontrol eden parametrelerdir.
- **Optimizasyon**: Modelin parametrelerini en iyi hale getirme sürecidir.

## Gradyan İnişi (Gradient Descent)
Optimizasyon algoritması olup, model parametrelerini kademeli olarak en iyi değere getirir.

## Yapay Zeka Çeşitleri
1. **Reaktif Makineler**: Geçmişi hatırlamaz, mevcut duruma göre karar alır. (Örn: Deep Blue)
2. **Sınırlı Bellek**: Geçmiş deneyimleri dikkate alabilir. (Örn: Otonom araçlar)
3. **Zihin Teorisi**: İnsanların duygu ve düşüncelerini anlayabilen yapay zeka türüdür.

## Turing Testi
Bir yapay zekanın insan gibi düşünebildiğini test etmek için kullanılır.

## Veri Ön İşleme Süreci
- **Normalizasyon**: Verileri belirli bir aralığa getirme.
- **Standardizasyon**: Verileri ortalama ve standart sapmaya göre dönüştürme.
- **Dengesiz Veri Setleri**:
  - **Aşırı Örnekleme**: Azınlık sınıfını artırma.
  - **SMOTE**: Sentetik veri noktaları üretme yöntemi.

## Makine Öğrenmesi Yöntemleri
### Gözetimli Öğrenme
- Girdi ve çıktı etiketleri verilir.
- **Sınıflandırma** ve **Regresyon** içerir.
- Örn: E-posta spam filtresi.

### Gözetimsiz Öğrenme
- Etiketlenmemiş verilerle çalışır.
- **Kümeleme (Clustering)** kullanılır.
- Örn: Müşteri segmentasyonu.

### Pekiştirmeli Öğrenme
- Ödül-ceza mekanizmasıyla öğrenir.
- Örn: Oyun oynayan yapay zeka.

## Veri Seti Bölme Oranları
- **80/20**: Eğitim %80, Test %20.
- **70/30**: Eğitim %70, Test %30.
- **60/20/20**: Eğitim %60, Doğrulama %20, Test %20.

## Çok Kullanılan Modeller
- **Lojistik Regresyon (Logistic Regression)**: Sınıflandırma problemlerinde kullanılır.
- **Destek Vektör Makineleri (Support Vector Machines)**: Karar sınırlarını belirler.

## Confusion Matrix (Karmaşıklık Matrisi)
- **TP (Doğru Pozitif)**: Gerçek pozitifleri doğru tahmin etme.
- **FN (Yanlış Negatif)**: Pozitifleri yanlışlıkla negatif olarak tahmin etme.
- **FP (Yanlış Pozitif)**: Negatifleri yanlışlıkla pozitif olarak tahmin etme.
- **TN (Doğru Negatif)**: Gerçek negatifleri doğru tahmin etme.


![Logo](https://upload.wikimedia.org/wikipedia/commons/c/c1/CBDDO_logo.svg)



