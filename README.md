# 🚦 CNN ve Transfer Learning ile Trafik İşaretlerinin Sınıflandırılması

Bu proje **Akbank Derin Öğrenme Bootcamp (Eylül 2025)** kapsamında hazırlanmıştır.  
Amaç, **Traffic Signs Preprocessed** veri seti üzerinde **CNN tabanlı bir derin öğrenme modeli** geliştirerek 43 farklı trafik işaretini sınıflandırmaktır.

---

## 📌 Projenin Amacı
- Görüntü sınıflandırma alanında CNN mimarisini uygulamak  
- Veri önişleme ve augmentation teknikleri ile model performansını artırmak  
- Modeli eğitim, doğrulama ve test setlerinde değerlendirerek başarıyı raporlamak  
- Grad-CAM ile modelin karar mekanizmasını görselleştirmek  

---

## 📊 Veri Seti
- Kaynak: [Traffic Signs Preprocessed Dataset](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-preprocessed/data)  
- Sınıf Sayısı: 43  
- Görsel Sayısı: ~50.000  
- Train / Validation / Test ayrımı hazır olarak verilmiştir.  

---

## 🧠 Kullanılan Yöntemler
- **Convolutional Neural Networks (CNN)**  
- **Data Augmentation** (Rotation, Flip, Zoom, Color Jitter)  
- **Dropout** (Overfitting önlemek için)  
- **Hiperparametre Denemeleri** (Batch size, Dropout, Learning Rate vb.)  
- **Grad-CAM Görselleştirme** (Modelin hangi bölgelerden etkilendiğini görmek için)  

---

## 📈 Sonuçlar
- En iyi doğruluk (Validation Accuracy): **%96**  ile CNN Modelinde elde edildi. Transfer Learning de ise oran **%49** olarak elde edilmiştir.
- Confusion Matrix ve Classification Report ile sınıf bazlı performans ölçüldü.  
- Grad-CAM ile modelin trafik işaretlerinde hangi bölgelerden etkilendiği görselleştirildi.  


## 🔗 Kaggle Notebook Linki
👉 https://www.kaggle.com/code/tuekarakaya/cnn-le-trafik-aretlerini-s-n-fland-rma

---

## 📂 Dosya Yapısı
- `Traffic_Signs_CNN_Project.ipynb` → Notebook dosyası  
- `README.md` → Proje açıklaması  


---
