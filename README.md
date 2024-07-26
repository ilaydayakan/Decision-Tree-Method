# Şarap Kalitesi Tahmini Projesi

Bu proje, farklı fizikokimyasal özellikler kullanılarak şarap kalitesini tahmin etmeyi amaçlamaktadır. Veri seti, 1599 şarap örneğinden oluşmakta ve toplamda 12 sütun içermektedir. Bu sütunlar, şarabın kimyasal özelliklerini ve kalitesini temsil etmektedir. Kalite, 3 ile 8 arasında değişen bir ölçekle derecelendirilmiştir.

Model ve Hiperparametre Optimizasyonu
Şarap kalitesini tahmin etmek için Karar Ağacı Sınıflandırıcısı kullanılmıştır. Modelin performansını artırmak amacıyla, hiperparametre optimizasyonu için GridSearchCV yöntemi uygulanmıştır. En iyi model parametresi olarak max_depth=4 belirlenmiştir.

Sınıflandırma Raporu ve Karmaşıklık Matrisi
Modelin sınıflandırma performansı aşağıdaki gibidir:

Doğruluk Oranı: %53.13
Precision, recall ve f1-score değerleri kalite sınıflarına göre değişkenlik göstermektedir. Özellikle kalite sınıflarının dengesiz dağılımı, model performansını olumsuz etkilemiştir.
Karmaşıklık Matrisi, modelin hangi sınıfları doğru veya yanlış tahmin ettiğini göstermektedir.
Özellik Önem Düzeyleri
Modelde kullanılan özelliklerin önem düzeyleri aşağıdaki gibidir:

Alkol, sülfatlar ve toplam kükürt dioksit en önemli özellikler arasında yer almaktadır. Bu özellikler, şarap kalitesini belirlemede daha büyük bir etkiye sahiptir.

Sonuç ve Değerlendirme
Bu projede, karar ağacı modeli kullanılarak şarap kalitesi tahmin edilmiştir. %53.13 doğruluk oranı, modelin iyileştirilmesi gerektiğini göstermektedir. Daha karmaşık modellerin kullanılması veya ek özellik mühendisliği ile daha yüksek performans elde edilebilir. Bu çalışma, şarap kalitesini etkileyen faktörlerin temel bir anlayışını sunmakta ve gelecekteki çalışmalar için bir temel oluşturmaktadır.
