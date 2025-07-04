Sleep, Stress and Health Analysis Using Machine Learning

Bu proje, uyku kalitesi, uyku düzeni, uyku süresi ile bireylerin stres seviyesi ve yaşam tarzı arasındaki ilişkileri makine öğrenmesi yöntemleriyle incelemektedir. Projede "SleepHealthandLifestyleDataset" veri seti kullanılmıştır. Veri setinde 374 bireye ait 14 özellik (yaş, meslek, uyku süresi, stres seviyesi vb.) bulunmaktadır.

Veri temizleme aşamasında eksik değerler doldurulmuş, kategorik veriler etiketlenmiştir.

Korelasyon analizi ile anlamlı değişkenler seçilmiştir.

Pandas, NumPy, Seaborn, Matplotlib ve Scikit-learn kütüphaneleri kullanılmıştır.

Uyku süresi ve stres ilişkisi Support Vector Regression (SVR) modeliyle %97 doğrulukla modellenmiştir.

Uyku kalitesi ve sağlık durumu arasındaki ilişki SVR ile %82 başarıyla tahmin edilmiştir.

Psikolojik sağlık ve mesleki stres tahmini için Random Forest sınıflandırma modeli %90 doğruluk oranına ulaşmıştır.

Vardiyalı ve yoğun çalışanlarda uyku düzeni bozuklukları daha sık görülmüş, bu durum Random Forest modeliyle %90 doğrulukla tahmin edilmiştir.

Kullanılan Modeller

Uyku Süresi ve Stres Seviyesi: Lineer Regresyon, Ridge Regresyon, SVR (En iyi model: SVR, R²=0.97)

Uyku Kalitesi ve Sağlık Durumu: Lineer Regresyon, Ridge Regresyon, SVR (En iyi model: SVR, R²=0.82)

Mesleki Stres, Yaşam Tarzı ve Uyku Düzeni: Karar Ağaçları, Lojistik Regresyon, Random Forest (En iyi model: Random Forest, %90 doğruluk)

Bu çalışma, uyku ile ilgili sağlık ve stres verilerini anlamlandırarak bireylerin yaşam kalitesini artırmaya yönelik öneriler geliştirmeyi amaçlamaktadır.
