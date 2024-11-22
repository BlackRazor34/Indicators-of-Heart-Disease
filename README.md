# 🫀 Kalp Hastalığı Risk Faktörleri Analizi

<p align="center">
  <img src="A soft representation of heart attack risk.png" alt="Kalp Sağlığı Analizi" width="800">
</p>


## 📊 Proje Açıklaması
Bu proje, 2022 yılına ait kapsamlı bir sağlık veri setini kullanarak kalp hastalığı risk faktörlerini analiz etmektedir. Çalışma, farklı yaş grupları, yaşam tarzı faktörleri ve sağlık durumlarının kalp hastalığı riski üzerindeki etkilerini incelemektedir.

## 🔍 Veri Seti Detayları
- **Kaynak**: Kaggle - Personal Key Indicators of Heart Disease
- **Boyut**: 240,000+ kayıt
- **Değişkenler**: 40 farklı özellik
 - Demografik bilgiler
 - Sağlık göstergeleri
 - Yaşam tarzı faktörleri
 - Kronik hastalıklar

## 📈 Analiz Aşamaları

### 1. Veri Ön İşleme
- Eksik değerlerin tespiti ve temizlenmesi
- Kategorik değişkenlerin düzenlenmesi
- Veri kalitesi kontrolü

### 2. Feature Engineering
#### BMI Risk Kategorileri:
- Severely Underweight (< 16.5)
- Underweight (16.5 - 18.5)
- Normal (18.5 - 24.9)
- Overweight (25 - 29.9)
- Obese Class I-II-III (> 30)

#### Uyku Düzeni Analizi:
- Az Uyku (< 6 saat)
- Normal Uyku (6-9 saat)
- Fazla Uyku (> 9 saat)

#### Sağlık Risk Değerlendirmesi:
- Fiziksel Sağlık Risk Skorları
- Mental Sağlık Risk Skorları
- Kronik Hastalık Sayısı

### 3. Önemli Bulgular

#### 3.1 BMI ve Kalp Hastalığı İlişkisi
- Normal BMI'ya sahip kişilerde risk daha düşük
- Obezite durumunda risk 2 kat artıyor

#### 3.2 Uyku Düzeni Etkisi
- Optimal uyku süresi 6-9 saat
- Düzensiz uyku riski %72 artırıyor

#### 3.3 Kronik Hastalıklar
- Her kronik hastalık riski artırıyor
- Multiple kronik hastalıklarda risk katlanarak artıyor

#### 3.4 Fiziksel Aktivite
- Düzenli aktivite riski azaltıyor
- Hareketsiz yaşam önemli risk faktörü

## 🛠️ Kullanılan Teknolojiler
- Python
- Pandas ve NumPy (Veri işleme)
- Matplotlib ve Seaborn (Görselleştirme)
- Scikit-learn (İstatistiksel analiz)

## 📊 Görselleştirmeler
1. Risk Faktörleri Dağılımı
2. BMI Kategorileri Analizi
3. Yaş ve Risk İlişkisi
4. Kronik Hastalık Etkisi

## 💡 Sonuçlar ve Öneriler

### Temel Risk Faktörleri:
1. Yüksek BMI (> 30)
2. Düzensiz Uyku
3. Kronik Hastalıklar
4. Fiziksel Aktivite Eksikliği

### Öneriler:
1. Düzenli Sağlık Kontrolleri
2. Kilo Yönetimi
3. Uyku Düzeni
4. Fiziksel Aktivite
5. Kronik Hastalık Takibi

## 🔗 Proje Bağlantıları
- [Kaggle Notebook](https://www.kaggle.com/code/emreenginn/indicators-of-heart-disease)
- [GitHub Repository](link)


