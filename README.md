# EEM4011 Biyomedikal Mühendisliği Projesi - Aşama 2

**Öğrenci:** Rafi Erkoç  
**Proje Konusu:** EKG Sinyalinde R Tepesi Tespiti ve Filtreleme Başarımı

## Veri Seti
Bu projede PhysioNet üzerinde açık erişimli olan **MIT-BIH Arrhythmia Database** kullanılmıştır.  
* Veri seti linki: https://physionet.org/content/mitdb/1.0.0/  
*(Veri dosyaları telif ve boyut kuralları gereği depoya yüklenmemiştir; kod doğrudan link üzerinden okumaktadır.)*

## Kodun Çalıştırılması
Analizler Google Colab üzerinde Python ile yapılmıştır.
1. `EEM4011_EKG_Asama2.ipynb` dosyasını Google Colab'da açın.
2. `wfdb` kütüphanesi ilk hücrede otomatik kurulur.
3. Hücreleri sırasıyla çalıştırarak 0.5–45 Hz Butterworth bant geçiren filtreleme ve R tepesi tespitini gerçekleştirin.

## Ana Sonuçlar (5 Kayıt Ortalaması)
* **Kayıt Sayısı:** 5 (100, 101, 102, 103, 105)
* **Ana Metrik:** F1 Skoru
* **Baseline (Ham Sinyal):** F1 = 0.482
* **İyileştirilmiş Yöntem (0.5–45 Hz Filtre):** F1 = 0.906

## Çıktı Grafiği
Grafik ilk 10 saniyelik EKG sinyali üzerinde filtrelenmiş dalgayı, tespit edilen R tepelerini ve uzman referanslarını göstermektedir (`sekil1.png`).
