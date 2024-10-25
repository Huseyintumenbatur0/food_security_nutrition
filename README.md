# Food Security and Nutrition Analysis

## Proje Açıklaması
Bu proje, dünya genelinde gıda güvenliği ve beslenme durumunu değerlendirmek amacıyla yapılmıştır. Kullanılan veri seti, çeşitli ülkelerin gıda güvenliği ile ilgili istatistiklerini içermektedir. Projede, ülkelerin gıda güvenliği endekslerini belirlemek için makine öğrenimi yöntemleri kullanılmıştır.

## Veri Seti
Veri seti, **Food Security and Nutrition in the World** başlığı altında toplanmıştır. Toplamda 113 ülkenin gıda güvenliği ile ilgili çeşitli özellikleri içermektedir. Kullanılan değişkenler:

- **Overall score:** Genel gıda güvenliği skoru
- **Affordability:** Gıda erişilebilirliği
- **Availability:** Gıdanın mevcut durumu
- **Quality and Safety:** Gıdanın kalitesi ve güvenliği
- **Sustainability and Adaptation:** Sürdürülebilirlik ve adaptasyon
- **Target:** Hedef değişken (Overall score > 75, 1; diğerleri, 0)

## Yöntem
Bu projede **Random Forest Classifier** makine öğrenimi algoritması kullanılmıştır. Model, %80 eğitim ve %20 test olarak ikiye ayrılarak değerlendirilmiştir.

## Sonuçlar
Modelin test setindeki doğruluk oranı değerlendirildi ve ROC eğrisi çizildi. AUC değeri hesaplanarak modelin performansı belirlendi. Model, gıda güvenliği endeksi için belirlenen eşik üzerinde yeterli sonuçlar sağladı.

## Kullanım
Projenin çalıştırılması için gerekli kütüphaneler:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
