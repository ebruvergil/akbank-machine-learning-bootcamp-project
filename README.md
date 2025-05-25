# Airbnb Open Data ML Demo

## Proje Açıklaması
Bu proje, Airbnb Open Data veri seti üzerinde makine öğrenimi algoritmalarını uygulamayı ve karşılaştırmayı amaçlamaktadır. Proje kapsamında hem gözetimli (sınıflandırma) hem de gözetimsiz (kümeleme) analizleri yapılmıştır.

**Kullanılan Algoritmalar ve Uygulamalar:**

* **Gözetimli Öğrenme:** Lojistik Regresyon, Karar Ağacı ve K-En Yakın Komşu (KNN) algoritmaları kullanılarak veri setindeki fiyat sınıflandırması yapılmış, model karşılaştırmaları ve hiperparametre optimizasyonu (Çapraz doğrulama ve GridSearchCV ile) gerçekleştirilmiştir.
* **Gözetimsiz Öğrenme:** K-Ortalama (K-Means) ve Hiyerarşik Kümeleme algoritmaları ile kümeleme analizi yapılmış, boyut indirgeme için PCA kullanılmış ve Silhouette skoru ile model değerlendirmesi yapılmıştır.

## Veri Seti
- **datasets/Airbnb_Open_Data.csv**: Airbnb New York City açık veri seti. Fiyat, hizmet ücreti, minimum gece, oda tipi, mahalle, konum, inceleme sayısı gibi özellikler içerir.

## Sonuç ve Gelecek Çalışmalar
Projenin mevcut hali, temel bir fiyat sınıflandırma sistemi sunmaktadır. Şu anda kullanıcı arayüzü (UI) bulunmadığı için model doğrudan etkileşimli olarak kullanılmamaktadır. İleride basit bir web arayüzü eklenerek kullanıcıların modeli daha kolay deneyimleyebilmesi sağlanabilir. Ayrıca, çalışmada yalnızca New York verisi kullanıldığı için, veri kümesi farklı şehirlerle genişletilerek modelin kapsamı artırılabilir.

---

**Hazırlayan:** Ebru Vergil


