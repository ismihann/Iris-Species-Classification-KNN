
Iris Species Classification with KNN
Bu proje, makine öğrenmesi dünyasının klasiklerinden biri olan Iris Veri Seti üzerinde K-En Yakın Komşu (K-Nearest Neighbors - KNN) algoritmasını kullanarak çiçek türlerini sınıflandırmayı amaçlamaktadır. Proje kapsamında veri ön işleme, model eğitimi, başarı metriklerinin analizi ve karar sınırlarının görselleştirilmesi yapılmıştır.

 Proje İçeriği ve Adımları
1. Veri Keşfi ve Ön İşleme
Veri seti yüklendi ve eksik değer kontrolü yapıldı.

Species (Tür) sütunu, modelin işleyebilmesi için sayısal değerlere (0, 1, 2) dönüştürüldü.

Verilerin dağılımını görmek için Seaborn ile görselleştirmeler yapıldı.

Özellikler (Features) ve Hedef değişken (Target) ayrıldı.

2. Model Hazırlığı
Veri seti %70 Eğitim ve %30 Test olarak ayrıldı.

Veriler, KNN algoritmasının performansını artırmak amacıyla StandardScaler kullanılarak ölçeklendirildi.

3. Model Eğitimi ve Performans
K=5 değeri ile bir KNN modeli eğitildi.

Model, test verileri üzerinde %100 doğruluk (accuracy) oranına ulaştı.

Confusion Matrix ve Classification Report ile modelin başarısı detaylandırıldı.

4. Optimizasyon ve Görselleştirme
En İyi K Değeri: 1'den 30'a kadar olan K değerleri test edilerek model performans grafiği oluşturuldu. Yapılan analiz sonucunda en yüksek doğruluğu veren k=3 değeri tespit edildi.

Decision Boundary (Karar Sınırı): Modelin sınıfları birbirinden nasıl ayırdığını görmek için 2 boyutlu bir karar sınırı grafiği oluşturuldu.

 Kullanılan Teknolojiler
Python 3

Pandas & Numpy: Veri manipülasyonu.

Matplotlib & Seaborn: Veri ve sonuç görselleştirme.

Scikit-Learn: Makine öğrenmesi modeli ve metrikler.

📈 Sonuçlar
Model, Iris-Setosa, Iris-Versicolor ve Iris-Virginica türlerini kusursuz bir şekilde birbirinden ayırabilmektedir. K değerinin seçimi, modelin genelleme yeteneği üzerinde doğrudan etkilidir.

 Iris-Virginica türlerini kusursuz bir şekilde birbirinden ayırabilmektedir. K değerinin seçimi, modelin genelleme yeteneği üzerinde doğrudan etkilidir.
