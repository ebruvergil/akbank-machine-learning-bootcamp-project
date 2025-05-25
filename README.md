# Airbnb Open Data ML Demo

## Proje Açıklaması
Bu proje, Airbnb Open Data veri seti üzerinde makine öğrenimi algoritmalarını uygulamayı ve karşılaştırmayı amaçlamaktadır. Proje kapsamında hem gözetimli (sınıflandırma) hem de gözetimsiz (kümeleme) analizleri yapılmıştır.

Notebook ve dataset erişimi için kullanabileceğiniz kaggle linkleri: https://www.kaggle.com/code/ebruvergil/supervised
https://www.kaggle.com/code/ebruvergil/unsupervised

**Kullanılan Algoritmalar ve Uygulamalar:** 

* **Gözetimli Öğrenme:** Lojistik Regresyon, Karar Ağacı ve K-En Yakın Komşu (KNN) algoritmaları kullanılarak veri setindeki fiyat sınıflandırması yapılmış, model karşılaştırmaları ve hiperparametre optimizasyonu (Çapraz doğrulama ve GridSearchCV ile) gerçekleştirilmiştir.
* **Gözetimsiz Öğrenme:** K-Ortalama (K-Means) ve Hiyerarşik Kümeleme algoritmaları ile kümeleme analizi yapılmış, boyut indirgeme için PCA kullanılmış ve Silhouette skoru ile model değerlendirmesi yapılmıştır.

## Veri Seti
- **datasets/Airbnb_Open_Data.csv**: Airbnb New York City açık veri seti. Fiyat, hizmet ücreti, minimum gece, oda tipi, mahalle, konum, inceleme sayısı gibi özellikler içerir.
- Kaynak: https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata

## Sonuç ve Gelecek Çalışmalar
Projenin mevcut hali, temel bir fiyat sınıflandırma sistemi sunmaktadır. Şu anda kullanıcı arayüzü (UI) bulunmadığı için model doğrudan etkileşimli olarak kullanılmamaktadır. İleride basit bir web arayüzü eklenerek kullanıcıların modeli daha kolay deneyimleyebilmesi sağlanabilir. Ayrıca, çalışmada yalnızca New York verisi kullanıldığı için, veri kümesi farklı şehirlerle genişletilerek modelin kapsamı artırılabilir.

## Kaynaklar
- https://www.kaggle.com/code/ebruvergil/supervised
- https://www.kaggle.com/code/ebruvergil/unsupervised
- https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata
- https://gokerguner.medium.com/machine-learning-1-7d4581caa291
- https://gokerguner.medium.com/machine-learning-2-korelasyon-matrisi-%C3%B6zellik-se%C3%A7imi-s%C4%B1n%C4%B1flar%C4%B1n-dengesizli%C4%9Fi-karar-a%C4%9Fa%C3%A7lar%C4%B1-af993bd8ea66
---

**Hazırlayan:** Ebru Vergil


