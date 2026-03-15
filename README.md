# Görüntüleme Cihazlarında Radyasyon Maruziyeti ve Kanser Riski

Bu proje, **TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Desteği Programı (2024, 1. Dönem)** kapsamında desteklenmeye hak kazanmıştır. Proje, tıbbi görüntüleme yöntemlerine maruz kalan hastaların kanser riskini tahmin eden **yapay zeka destekli bir sistem** geliştirmeyi amaçlamaktadır.

---

## 👥 Proje Ekibi ve Görev Dağılımı

- **Proje Yürütücüsü:** Mustafacan Ünal  
- **Akademik Danışman:** Ahmet ERHARMAN  

**Proje Araştırmacıları / Geliştiriciler:**  

| İsim | Görev |
|------|-------|
| **Fatma Betül Pehlivan** | İhtiyaç analizi ve proje planlaması; radyasyon dozu ve demografik faktörlere dayalı veri setinin toplanması, temizlenmesi ve işlenmesi (Veri Ön İşleme) |
| **Ahmet Buğra Öztürk** | Model ve arayüz test süreçlerinin yönetimi, doğrulama ve optimizasyon çalışmaları |
| **Melek Güngül** | Algoritma ve model geliştirme; web tabanlı kullanıcı arayüzünün (UI) kodlanması |

---

## 🎯 Projenin Amacı ve Özgün Değeri

- Tıbbi görüntüleme (özellikle BT) hastalık tanısında kritik öneme sahiptir, ancak **iyonize radyasyona maruz kalma** nedeniyle uzun vadede sağlık riskleri oluşturur (ör. tiroid kanseri).  
- Bu proje, hastaların demografik bilgilerini, genetik yatkınlıklarını, tıbbi geçmişlerini ve maruz kaldıkları radyasyon dozlarını kullanarak **tiroid kanseri riskini %95 doğrulukla tahmin eden bir sistem** geliştirmektedir.  
- Sistem, doktorlara **gereksiz radyasyon maruziyetini önlemek için MR veya ultrason gibi alternatif görüntüleme yöntemlerini öneren** klinik karar desteği sağlar.  

---

## ⚙️ Kullanılan Teknolojiler ve Yöntemler

### Veri Bilimi ve Yapay Zeka

- **Diller / Kütüphaneler:** Python, TensorFlow, PyTorch  
- **Modeller:** Logistic Regression, Naive Bayes, SVM, Random Forest, XGBoost  
- **Özellik Mühendisliği:** Kümülatif radyasyon dozu, maruz kalma yaşı, genetik sağlık geçmişi  
- **Model Yorumlanabilirliği (Explainable AI):** SHAP ve LIME ile hangi değişkenlerin tahmine katkısı gösterilmiştir  
- **Performans Metrikleri:** Accuracy, Precision, Recall, AUC-ROC

### Web Geliştirme (Full-Stack)

- **Frontend:** HTML, CSS, JavaScript ile kullanıcı dostu arayüz  
- **Backend:** Python tabanlı API ile yapay zeka modelinin entegrasyonu  
- **Çıktı Görselleştirme:** Riskler; Düşük (%1-10), Orta (%11-30), Yüksek (%31+) olarak sınıflandırılmıştır

---

## 📊 Beklenen Yaygın Etki

- Tıbbi radyasyon risk analizi için **yeni bir paradigma** sunar  
- Klinik pratikte ve toplum sağlığında **farkındalık yaratır**  
- Çıktılar, ticari patent başvuruları ve sağlık sektöründeki **Spin-off / Start-up girişimlerini** destekleyebilir

---

📂 Alternatif Erişim (Opsiyonel)

Proje verileri ve çıktıları, GitHub üzerinden görüntülemekte sorun yaşayan kullanıcılar için Google Drive üzerinden de erişilebilir:https://drive.google.com/file/d/1cdR5iJfiycU_yQtudDBf1Kh8hyMy5nmb/view?usp=sharing
