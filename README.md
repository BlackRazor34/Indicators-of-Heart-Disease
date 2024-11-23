# 🫀 Kalp Hastalığı Risk Faktörleri Analizi




## 📊 Proje Açıklaması
CDC'ye göre, kalp hastalığı ABD'deki çoğu ırktan insan için (Afrikalı Amerikalılar, Amerikan Yerlileri ve Alaska Yerlileri ve beyazlar) önde gelen bir ölüm nedenidir. Tüm Amerikalıların yaklaşık yarısı (%47) kalp hastalığı için 3 ana risk faktöründen en az 1'ine sahiptir: yüksek tansiyon, yüksek kolesterol ve sigara. Diğer önemli göstergeler arasında diyabet durumu, obezite (yüksek BMI), yeterli fiziksel aktivite yapmama veya çok fazla alkol alma yer almaktadır. Kalp hastalığı üzerinde en büyük etkiye sahip olan faktörlerin belirlenmesi ve önlenmesi sağlık hizmetlerinde çok önemlidir. Buna karşılık, bilgi işlem alanındaki gelişmeler, bir hastanın durumunu tahmin edebilecek verilerdeki "kalıpları" tespit etmek için makine öğrenimi ve sınıflandırma yöntemlerinin uygulanmasına izin vermektedir.

Bu projede örnek iş tanım ve hedeflerinin belirlenmesi yanında, kalp krizi riskinin değişkenlere göre araştırılması ve analiz edilmesi üzerine çalıştım.

##  Örnek Problem Tanımı ve İş Hedefi

Sağlık sektöründe faaliyet gösteren şirketimiz için, Kalp hastalığı riskini erken aşamada tespit edip, önleyici sağlık hizmetlerini optimize etmek.

Bu model şu amaçlarla kullanılabilir:

Hastaneler ve kliniklerde risk değerlendirmesi
Sigorta şirketleri için risk skorlaması
Preventif tıp uygulamaları için erken uyarı sistemi
Telesağlık uygulamalarında ön değerlendirme aracı

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
- Veri setinin hazırlanması
- NaN değerler oluşturulması
- Eksik değerlerin tespiti ve temizlenmesi
- Kategorik değişkenlerin berlilenmesi ve düzenlenmesi
- İstatistiksel analizler

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
- Pandas
- NumPy 
- Matplotlib
- Seaborn 

## 📊 Görselleştirmeler
1. Risk Faktörleri Dağılımı
2. BMI Kategorileri Analizi
3. Yaş ve Risk İlişkisi
4. Kronik Hastalık Etkisi
5. Sigara Kullanımına Bağlı Risk Analizi

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


