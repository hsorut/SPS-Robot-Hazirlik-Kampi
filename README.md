# 🚀 IEEE DEU SPS Robot Hazırlık Kampı: "60 Günlük Büyük Vizyon"

**Slogan:** *"1. Ayda Uzmanlaş, 2. Ayda İmzanı At!"*

Bu depo, ekibimizin geliştireceği büyük **"SPS Etkileşimli Robot"** projesi öncesinde kurgulanan; 45 günlük (6 hafta) yoğun teknik eğitim ve ardından gelen 15 günlük (2 hafta) inşa sürecinden oluşan toplam 60 günlük hazırlık kampının merkezidir.

---

## 📅 FAZ 1: 45 Günlük Eğitim Müfredatı (6 Hafta)

> **⚠️ Kritik Kural:** İlk 2 hafta Grup 1 ve Grup 2 ayrımı yoktur. Herkes "Python Okuryazarı" olmak zorundadır.

| Hafta | Tema | Grup 1 (Veri Bilimi & ML) | Grup 2 (Sistem, Algı & Donanım) |
| :--- | :--- | :--- | :--- |
| **1** | **Python Temelleri I** | **ORTAK:** Değişkenler, Veri Tipleri, Sayısal Mantık, Thonny IDE Kurulumu. | **ORTAK:** Değişkenler, Veri Tipleri, Sayısal Mantık, Thonny IDE Kurulumu. |
| **2** | **Python Temelleri II** | **ORTAK:** Listeler, Sözlükler, Fonksiyonlar, Karar Mekanizmaları (`if/else`) ve Hata Yönetimi. | **ORTAK:** Listeler, Sözlükler, Fonksiyonlar, Karar Mekanizmaları (`if/else`) ve Hata Yönetimi. |
| **3** | **Matematiksel Temel** | **NumPy:** Veri Seti Manipülasyonu, Matris İşlemleri ve İstatistik. | **NumPy:** Görüntü Matrisleri. **MicroPython:** `machine`, `time`, `utime` modülleri. |
| **4** | **Veri ve Analiz** | **Pandas:** Tablo Yönetimi, Veri Temizleme. **Matplotlib/Seaborn:** Görselleştirme. | **Pandas:** Sensör Kayıt Analizi. **MicroPython:** `network`, `usocket`, `ujson`. |
| **5** | **Zeka ve Algı** | **Scikit-learn:** Regresyon, Sınıflandırma, Model Eğitimi (Zeka Katmanı). | **OpenCV & Mediapipe:** Obje Tespiti, El İzleme ve Poz Tahmini (Algı Katmanı). |
| **6** | **Etkileşim ve Sistem** | **Model Optimizasyonu:** Tahminleme Servisleri ve Model Doğrulama. | **gTTS & SpeechRecognition:** Sesli Etkileşim. **FastAPI & WebSockets:** PC-ESP32 Köprüsü. |

---

## 👥 Takım Yapılanması (Neden Bu Eğitimleri Alıyoruz?)

### 🧠 Grup 1: Zeka Katmanı (Beyin)
Robotun topladığı verileri anlamlandırır. *"Önümde bir insan var mı?", "Bana bir komut verildi mi?", "Bir sonraki hareketim ne olmalı?"* sorularına **Makine Öğrenmesi** modelleriyle cevap verir.

### 🦾 Grup 2: Algı ve Hareket Katmanı (Beden)
Robotun fiziksel dünyayla temasını sağlar. **OpenCV** ile görür, **Mediapipe** ile hareketleri takip eder, **MicroPython** ile motorları sürer ve **WebSockets** ile beyniyle (PC) konuşur.

---

## 🏗️ FAZ 2: 15 Günlük Büyük Robot İnşası (2 Hafta)

Eğitimin sonunda herkesin bilgisi tek bir projede düğümlenir:

* **Haberleşme Ağı:** ESP32 (Grup 2), PC'ye (Grup 1) WebSocket üzerinden sürekli sensör ve görüntü verisi aktarır.
* **Karar Mekanizması:** Grup 1'in eğittiği modeller, gelen veriyi işleyip saniyeler içinde karar verir.
* **Aksiyon:** Karar verildikten sonra ESP32'ye hareket komutu gider ve robot fiziksel tepki verir.
* **Entegre Etkileşim:** Robot, **gTTS** ile konuşur, **SpeechRecognition** ile dinler ve **State Machine** (Durum Makinesi) yapısı ile otonom davranır.

---

## 🛠️ Kullanılan Tüm Araçlar (Bağımlılık Listesi)

* **Editörler:** Thonny IDE (ESP32 için), VS Code veya PyCharm (PC için).
* **Gömülü:** MicroPython (`machine`, `network`, `ujson`, `usocket`, `utime`).
* **Veri/ML:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn.
* **Algı/Ses:** OpenCV, Mediapipe, gTTS, SpeechRecognition.
* **Ağ:** FastAPI, WebSockets, JSON.

---

## 📝 Raporlama Sistemi (Agile Sprint)
Her üye, her Pazar günü saat 23:59'a kadar `Haftalik_Raporlar` klasörü altında raporunu teslim etmelidir:

* **Done:** Tamamlanan teknik kazanımlar.
* **Blockers:** İlerlemeyi durduran donanım veya yazılım hataları.
* **To-Do:** Bir sonraki sprint hedefi.

---
*Bu kampın sonunda, sadece kod yazmayı değil, yaşayan bir sistemi sıfırdan inşa etmeyi öğrenmiş olacağız.* **IEEE DEU SPS Ekibi**
