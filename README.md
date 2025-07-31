# 2 farklı zaman diliminde çekilmiş uydu görüntülerinin değişim tespiti

## ChangeSTAR derin öğrenme modeli analizi gerçekleştiriliyor:

1. **Değişim Tespiti**: Hangi bölgelerde değişiklik olduğunu gösterir
2. **Arazi Sınıflandırması**: 9 farklı arazi türünü tanımlayarak (orman, bina, yol, su vb.) değişimin türünü belirler

## Kullanılan Teknoloji
- **Model**: s9_init_s9c1_changestar_vitb_1x256
- **Mimari**: Vision Transformer tabanlı ChangeSTAR

## Arazi Türleri
Model 9 sınıf tanıyor: Bilinmeyen, Çıplak arazi, Mera, Gelişmiş alan, Yol, Ağaç, Su, Tarım arazisi, Bina.

## Nasıl Çalışır
1. before/ ve after/ klasörlerindeki görüntüleri yükler 
2. Her iki görüntüyü model ile analiz eder
3. Değişim haritası ve arazi türü haritalarını görselleştirir

## Kullanım
Notebook'u çalıştırın. Model otomatik olarak indirilir ve analiz başlar.

## Kaynakça
https://github.com/Z-Zheng/pytorch-change-models/tree/main
