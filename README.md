# Tiktok-project

### 📘 tiktok1.ipynb
Amacı:
TikTok'ta doğrulanmış (verified) ve doğrulanmamış (unverified) kullanıcıların videoları arasındaki izlenme sayılarında anlamlı bir fark olup olmadığını test etmek.

İçerik Özeti:
Veri yükleme ve ilk inceleme (info(), describe()),
Aykırı değer analizi,
Eksik verilerin temizlenmesi,
verified_status değişkenine göre gruplama

Hipotez testi:
H₀: Doğrulanmış ve doğrulanmamış videolar arasında fark yok,
H₁: Arada anlamlı bir fark var


### 📗 tiktok2.ipynb
Amacı:
TikTok verisini temizleyip analiz ettikten sonra, videoların "doğrulanmış hesap" (verified) olup olmamasını tahmin etmek için lojistik regresyon modeli geliştirmek.

İçerik Özeti:
Veri temizliği (eksik veriler, tekrar eden kayıtlar),
Aykırı değer tespiti (boxplot ile görselleştirme),
Özellik mühendisliği (OneHotEncoder, TF-IDF gibi yöntemlerle),
Veri dengesizliğinin giderilmesi (resample),
Lojistik regresyon modeli kurulması,
Eğitim-test ayırımı, modelin eğitilmesi,
Doğruluk, sınıflandırma raporu ve karmaşıklık matrisi ile değerlendirme

### 📕 tiktok3.ipynb - README Açıklaması
Bu notebook, TikTok platformunda yanıltıcı bilgi yayılımını azaltmaya yönelik bir makine öğrenmesi modeli geliştirme çalışmasını içermektedir.

🎯 Projenin Amacı:
TikTok videolarında yer alan içeriklerin "claim" (iddia) mi yoksa "opinion" (görüş) mü olduğunu ikili sınıflandırma (binary classification) ile tahmin etmeye çalışmak.

İçerik Özeti:
Etik Değerlendirme (Part 1):
Modelin hedefinin sosyal medya üzerindeki bilgi akışı üzerindeki etkileri sorgulanır. Yanlış bilgilendirme ile mücadelede yapay zekanın rolü düşünülür.

Özellik Mühendisliği (Part 2):
Eksik verilerin ve tekrar eden kayıtların temizlenmesi
Yeni özellikler oluşturulması (örneğin: metin uzunluğu)
Veri dönüşümleri (örnek: TF-IDF gibi)

Modelleme (Part 3):
Verinin eğitim ve test olarak ayrılması
Sınıflandırma modellerinin eğitimi
Model başarımlarının değerlendirilmesi (doğruluk, confusion matrix vs.)
Sonuçlara göre öneriler sunulması


### in English

📘 tiktok1.ipynb
Purpose:
To test whether there is a significant difference in video view counts between verified and unverified TikTok accounts.
Summary:
Data loading and exploration
Outlier detection
Missing value handling
Grouping by verified_status
Hypothesis testing:
H₀: No difference between groups
H₁: Significant difference exists

📗 tiktok2.ipynb
Purpose:
To build a logistic regression model that predicts whether a TikTok video is from a verified account based on various features.
Summary:
Data cleaning (missing values, duplicates)
Outlier detection (boxplots)
Feature engineering (OneHotEncoder, TF-IDF)
Resampling to balance classes
Logistic regression model training and evaluation

📕 tiktok3.ipynb
Purpose:
To develop a machine learning model that classifies TikTok videos as either a “claim” or an “opinion” to help reduce misinformation.
Summary:
Ethical considerations around the model’s goal
Feature engineering (e.g., text length, TF-IDF)
Data preparation and train-test split
Binary classification modeling and performance evaluation
