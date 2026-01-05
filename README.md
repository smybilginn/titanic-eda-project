# titanic-eda-projec
Exploratory Data Analysis (EDA) on the Titanic dataset

---

## 🧠 Kullanılan Teknolojiler

Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

- **pandas** – veri işleme  
- **numpy** – sayısal işlemler  
- **matplotlib** – temel grafikler  
- **seaborn** – gelişmiş görselleştirme  

---

## 🔍 Analiz Adımları

1. **Veri Yükleme & İnceleme:**  
   CSV formatındaki veri seti `pandas` ile yüklendi ve ilk bakışta sütun türleri, satır/özellik sayısı incelendi.

2. **Eksik Değer Analizi:**  
   Özellikle `Age`, `Cabin`, `Embarked` gibi sütunlarda eksik değerler tespit edildi ve uygun stratejilerle (ortalama/medyan/mod) dolduruldu. :contentReference[oaicite:1]{index=1}

3. **Görselleştirmeler:**  
   - **Hayatta kalma oranı vs cinsiyet**  
   - **Pclass’a göre dağılımlar**  
   - **Yaşa göre hayatta kalma eğilimleri**

   gibi önemli değişkenler grafiklerle incelendi.

---

## 📊 Öne Çıkan İçgörüler

💡 **Kadın yolcuların hayatta kalma oranı erkeklere göre daha yüksektir.**  
💡 **1. sınıf yolcuların hayatta kalma olasılığı daha yüksek görülmektedir.**  
💡 **Yaş grupları, hayatta kalma oranında farklılıklar göstermektedir.**

Bu bulgular verinin görselleştirmeleri üzerinden çıkarılmıştır ve Titanic veri analizinde sıkça rastlanan sonuçlardır. :contentReference[oaicite:2]{index=2}

---
