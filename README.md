# Cilt Kanseri Sınıflandırması ve Performans Analizi 🔬

Bu proje, bilgisayarlı görü (computer vision) teknikleri kullanılarak cilt lezyonlarının iyi huylu veya kötü huylu (kanserli) olup olmadığını sınıflandırmayı amaçlayan bir akademik araştırma ve modelleme çalışmasıdır.

Farklı derin öğrenme mimarileri (CNN ve Transformer tabanlı) eğitilmiş ve performansları doğruluk (accuracy), kesinlik (precision), duyarlılık (recall) ve F1-Skoru gibi metrikler üzerinden karşılaştırmalı olarak analiz edilmiştir.

## 🚀 Kullanılan Modeller ve Yaklaşımlar

Proje kapsamında aşağıdaki mimariler kullanılmış ve performans kıyaslamaları yapılmıştır:
*   **ResNet50:** Temel model (Baseline) olarak kullanılmıştır.
*   **EfficientNet-B0:** Daha az parametre ile yüksek verim elde etmek amacıyla test edilmiştir.
*   **EfficientNet + SVM:** EfficientNet mimarisinin çıkışındaki özellikler (feature extraction) alınarak sınıflandırma aşamasında Destek Vektör Makineleri (SVM) kullanılmıştır.
*   **Vision Transformer (ViT):** Görüntü sınıflandırmada dikkat mekanizmalarının (attention mechanisms) etkisini gözlemlemek için modele entegre edilmiştir.

## 📊 Rapor ve Bulgular
Projenin detaylı analizlerine, eğitim süreçlerindeki kayıp/doğruluk (loss/accuracy) grafiklerine ve nihai sonuçlarına `docs/` klasörü altındaki proje raporundan ulaşabilirsiniz.

## 🛠️ Kurulum ve Kullanım
1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/Mert1628/skin-cancer-classification.git](https://github.com/Mert1628/skin-cancer-classification.git)
