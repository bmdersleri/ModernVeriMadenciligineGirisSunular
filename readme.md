# Modern Veri Madenciliğine Giriş - Ders Sunuları

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/bmdersleri/ModernVeriMadenciligineGirisSunular.svg)](https://github.com/bmdersleri/ModernVeriMadenciligineGirisSunular/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/bmdersleri/ModernVeriMadenciligineGirisSunular.svg)](https://github.com/bmdersleri/ModernVeriMadenciligineGirisSunular/issues)

Bu depo, lisans ve lisansüstü düzeyde verilen **Modern Veri Madenciliğine Giriş** dersi kapsamında kullanılan haftalık ders sunumlarını, yardımcı görsel materyalleri ve ilgili kaynakları içermektedir.

---

## 📌 İçindekiler

- [Ders Hakkında](#-ders-hakkında)
- [Haftalık Ders Planı ve Sunular](#-haftalık-ders-planı-ve-sunular)
- [Kullanılan Teknolojiler ve Araçlar](#-kullanılan-teknolojiler-ve-araçlar)
- [Önerilen Kaynaklar ve Kitaplar](#-önerilen-kaynaklar-ve-kitaplar)
- [Katkıda Bulunma](#-katkıda-bulunma)
- [İletişim & Lisans](#-iletişim--lisans)

---

## 📖 Ders Hakkında

Veri madenciliği; büyük ölçekli veri yığınları içerisinden gizli, anlamlı, geçerli ve eyleme dönüştürülebilir örüntülerin keşfedilmesi sürecidir. 

Bu dersin temel amaçları:
- Veri ön işleme, temizleme ve normalizasyon yöntemlerini öğretmek.
- Temel gözetimli (supervised) ve gözetimsiz (unsupervised) öğrenme algoritmalarının matematiksel temellerini ve çalışma prensiplerini aktarmak.
- Modern veri madenciliği araçları ve büyük veri mimarileriyle uygulama yetkinliği kazandırmak.
- Model değerlendirme, doğrulama ve metrik analizlerini pratik örneklerle pekiştirmek.

---

## 📂 Haftalık Ders Planı ve Sunular

| Hafta | Konu Başlığı | İlgili Dosya / Sunum |
| :---: | :--- | :---: |
| **01** | Veri Madenciliğine Giriş: Temel Kavramlar ve Veri Yaşam Döngüsü | [Hafta-01.pdf](./Hafta-01/) |
| **02** | Veri Tipleri, Veri Keşfi ve İstatistiksel Betimleme | [Hafta-02.pdf](./Hafta-02/) |
| **03** | Veri Ön İşleme (Veri Temizleme, Entegrasyon, Dönüşüm ve İndirgeme) | [Hafta-03.pdf](./Hafta-03/) |
| **04** | Birliktelik Kuralı Madenciliği (Apriori, FP-Growth Algoritmaları) | [Hafta-04.pdf](./Hafta-04/) |
| **05** | Sınıflandırma-I: Karar Ağaçları (ID3, C4.5, CART) | [Hafta-05.pdf](./Hafta-05/) |
| **06** | Sınıflandırma-II: İstatistiksel & Olasılıksal Yöntemler (Naive Bayes, Lojistik Regresyon) | [Hafta-06.pdf](./Hafta-06/) |
| **07** | Sınıflandırma-III: Mesafe Temelli ve Doğrusal Olmayan Modeller (k-NN, Destek Vektör Makineleri) | [Hafta-07.pdf](./Hafta-07/) |
| **08** | **Ara Sınav / Değerlendirme Haftası** | — |
| **09** | Topluluk Öğrenmesi (Ensemble Learning: Bagging, Boosting, Random Forest) | [Hafta-09.pdf](./Hafta-09/) |
| **10** | Kümeleme Analizi-I: Bölümlemeli ve Hiyerarşik Kümeleme (k-Means, Agglomerative) | [Hafta-10.pdf](./Hafta-10/) |
| **11** | Kümeleme Analizi-II: Yoğunluk Temelli Kümeleme (DBSCAN) ve Anomali Tespiti | [Hafta-11.pdf](./Hafta-11/) |
| **12** | Model Doğrulama ve Başarım Değerlendirme (Confusion Matrix, ROC/AUC, Çapraz Doğrulama) | [Hafta-12.pdf](./Hafta-12/) |
| **13** | Metin ve Web Madenciliği Temelleri | [Hafta-13.pdf](./Hafta-13/) |
| **14** | Büyük Veri Analitiği ve Modern Veri Madenciliği Trendleri | [Hafta-14.pdf](./Hafta-14/) |

> *Not: Sunum dosyalarının formatına göre bağlantı yollarını güncelleyebilirsiniz (`.pdf`, `.pptx` vb.).*

---

## 🛠 Kullanılan Teknolojiler ve Araçlar

Ders içi uygulamalar ve ödev çalışmalarında sıklıkla başvurulan ortamlar:

- **Diller:** Python, R
- **Python Kütüphaneleri:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- **Görsel/Grafik Arayüzlü Araçlar:** KNIME, Weka, Orange Data Mining
- **Ortamlar:** Jupyter Notebook, Google Colab

---

## 📚 Önerilen Kaynaklar ve Kitaplar

- **Introduction to Data Mining** — Pang-Ning Tan, Michael Steinbach, Anuj Karpatne, Vipin Kumar
- **Data Mining: Concepts and Techniques** — Jiawei Han, Micheline Kamber, Jian Pei
- **The Elements of Statistical Learning** — Trevor Hastie, Robert Tibshirani, Jerome Friedman

---

## 🤝 Katkıda Bulunma

Sunumlardaki yazım hatalarını düzeltmek, içerik güncellemesi önermek veya ek örnek materyaller eklemek isterseniz:

1. Bu depoyu çatallayın (Fork).
2. Yeni bir dal (branch) açın:
   ```bash
   git checkout -b ozellik/yeni-konu
   ```
3. Değişikliklerinizi commit edin:
   ```bash
   git commit -m 'feat: 3. hafta eksik slayt eklendi'
   ```
4. Dalınızı uzak depoya gönderin:
   ```bash
   git push origin ozellik/yeni-konu
   ```
5. Bir **Pull Request (PR)** açın.

---

## 📄 Lisans

Bu projedeki eğitim materyalleri eğitim ve araştırma amaçlı serbestçe kullanılabilir. Detaylar için [LICENSE](LICENSE) dosyasına göz atabilirsiniz.