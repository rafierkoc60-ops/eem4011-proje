# İddia Tablosu (EEM4011 - Hafta 1)

## Tek Cümlelik Katkı
Combining a third-order Butterworth bandpass filter (0.5–45 Hz) with peak prominence thresholding increases R-peak detection performance from a baseline F1-score of 0.477 ± 0.162 to 0.831 ± 0.119 on five independent test records of the MIT-BIH Arrhythmia Database under a ±50 ms matching tolerance.

## İddia Tablosu

| # | İddia | Kanıt | Şekil / Tablo | Durum |
|---|---|---|---|---|
| 1 | Bant geçiren filtreleme ve tepe belirginliği kombinasyonu, bağımsız test kayıtlarında ham sinyale göre R-tepesi tespit başarısını artırır. | Ham sinyal F1 = 0.477 ± 0.162 iken yöntemde F1 = 0.831 ± 0.119 (fark: +0.354). | Tablo 1 ve Şekil 2 (ablasyon grafiği) | var |
| 2 | 0.5–45 Hz Butterworth filtreleme, solunum kaynaklı taban çizgisi kaymasını ve yüksek frekans gürültülerini bastırır. | 10 saniyelik EKG kesitinde filtrelenmiş sinyal sıfır eksenine oturmakta ve R tepeleri referansla ±50 ms içinde örtüşmektedir. | Şekil 1 (sekil_kesit.png) | var |
| 3 | Belirginlik eşiği ve 200 ms refrakter süre kısıtı, yüksek T dalgalarından kaynaklanan yanlış pozitifleri azaltır. | Yalnız filtrede F1 = 0.655 iken belirginlik eklendiğinde F1 = 0.831'e yükselmiştir. | Tablo 1 (Ablasyon Tablosu) | var |
| 4 | Önerilen kural tabanlı boru hattı, harici karmaşık donanım veya derin öğrenme gerektirmeden bağımsız test hastalarında genellenebilir. | 5 farklı hasta kaydında (106, 108, 109, 118, 200) ortalama 0.831 F1 elde edilmiştir. | Tablo 2 (Test Kayıtları Tablosu) | var |
