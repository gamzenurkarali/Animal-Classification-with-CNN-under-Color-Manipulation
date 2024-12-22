# Animal-Classification-with-CNN-under-Color-Manipulation 

Bu proje, farklı hayvan türlerini sınıflandırmak için bir CNN modelinin geliştirilmesi ve eğitilmesini içermektedir. Projede kullanılan veri seti, çeşitli hayvan türlerini içeren ve farklı aydınlatma koşullarında manipüle edilmiş görsellerden oluşmaktadır. Manipülasyon sonrası renk sabitliği uygulanarak model performansı analiz edilmiştir.

## Veri Seti Özellikleri
- Veri setinden 10 adet sınıfın verileri kullanılmıştır: `collie`, `dolphin`, `elephant`, `fox`, `moose`, `rabbit`, `sheep`, `squirrel`, `giant panda`, ve `polar bear`.
- Manipülasyon: Veriler, mor ışık altında manipüle edilmiş ve modelin genelleştirme yeteneğini test etmek için renk sabitliği uygulanmıştır.

## Kullanılan Kütüphaneler
Projede kullanılan temel Python kütüphaneleri:
- **TensorFlow/Keras**: CNN modelinin tasarımı, eğitimi ve değerlendirilmesi için kullanılmıştır.
- **NumPy**: Sayısal hesaplamalar ve veri manipülasyonu için kullanılmıştır.
- **Matplotlib & Seaborn**: Veri görselleştirme ve karışıklık matrisi gibi grafiklerin oluşturulmasında kullanılmıştır.
- **Scikit-learn**: Karışıklık matrisi ve diğer değerlendirme metrikleri için kullanılmıştır.


## Projenin Amacı
Bu proje, derin öğrenme modellerinin manipüle edilmiş görsellere karşı dayanıklılığını test etmek ve renk sabitliği gibi ön işleme yöntemlerinin bu tür manipülasyonların olumsuz etkilerini nasıl azalttığını incelemek için gerçekleştirilmiştir.
