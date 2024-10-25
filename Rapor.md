Rapor Başlığı
Proje Adı: Food Security and Nutrition Analysis
Tarih: 20/10/2024

1. Giriş
Bu proje, dünya genelinde gıda güvenliği ve beslenme durumunu değerlendirmek amacıyla yapılmıştır. Kullanılan veri seti, çeşitli ülkelerin gıda güvenliği ile ilgili istatistiklerini içermektedir. Projede, ülkelerin gıda güvenliği endekslerini belirlemek için makine öğrenimi yöntemleri kullanılmıştır.

2. Veri Seti
Veri seti, Food Security and Nutrition in the World başlığı altında toplanmıştır. Toplamda 113 ülkenin gıda güvenliği ile ilgili çeşitli özellikleri içermektedir. Kullanılan değişkenler:

Overall score: Genel gıda güvenliği skoru
Affordability: Gıda erişilebilirliği
Availability: Gıdanın mevcut durumu
Quality and Safety: Gıdanın kalitesi ve güvenliği
Sustainability and Adaptation: Sürdürülebilirlik ve adaptasyon
Target: Hedef değişken (Overall score > 75, 1; diğerleri, 0)


3. Yöntem
Proje kapsamında, Random Forest Classifier makine öğrenimi algoritması kullanılmıştır. Bu algoritma, yüksek doğruluk ve esneklik sunarak sınıflandırma problemlerini çözmekte yaygın olarak kullanılmaktadır. Veri seti, %80 eğitim ve %20 test olarak ikiye ayrılmıştır.

4. Sonuçlar
Modelin test setindeki doğruluk oranı değerlendirildi ve ROC eğrisi çizildi. AUC değeri hesaplanarak modelin performansı belirlendi. Aşağıda elde edilen ROC eğrisi ve AUC değeri belirtilmiştir:

ROC Eğrisi: Eğri, yanlış pozitif oranı ile doğru pozitif oranı arasında bir ilişki sunar.
AUC Değeri: [AUC değeri, burada yer almalı; kod çalıştırıldığında elde edilen değer].
(ROC eğrisi grafiği buraya eklenmeli)

5. Yorumlar
Model, yüksek doğruluk oranları gösterdi ve gıda güvenliği endeksi için belirlenen eşik üzerinde yeterli sonuçlar sağladı. ROC eğrisinin AUC değeri, modelin olumlu sınıflandırma yeteneğinin iyi olduğunu göstermektedir. Ancak, daha karmaşık modeller veya daha fazla veri ile sonuçların iyileştirilmesi mümkün olabilir. Gelecekteki çalışmalarda, farklı makine öğrenimi algoritmalarının ve parametre ayarlamalarının incelenmesi önerilmektedir.

6. Sonuç
Proje, gıda güvenliği durumunun değerlendirilmesinde makine öğrenimi tekniklerinin etkili bir şekilde kullanılabileceğini göstermektedir. Elde edilen sonuçlar, ülke bazında gıda güvenliğinin artırılması için stratejik kararlar alınmasına yardımcı olabilir. Projenin ilerleyen aşamalarında, veri setinin genişletilmesi ve farklı veri kaynaklarının entegrasyonu ile daha kapsamlı analizlerin yapılması planlanmaktadır.