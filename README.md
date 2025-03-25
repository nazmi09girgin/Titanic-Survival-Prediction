# Titanic-Survival-Prediction
Bu proje, Titanic yolcularının hayatta kalma durumlarını tahmin etmek amacıyla farklı makine öğrenimi modellerini (Logistic Regression, Decision Tree, Random Forest ve K-Nearest Neighbors (KNN)) kullanarak bir sınıflandırma analizi yapmaktadır.

Adımlar:
1. Veri Seti Yükleme:
Titanic verisi train.csv ve test.csv dosyalarından pandas ile yüklenir.

3. Veri Ön İşleme:
Eksik değerler uygun yöntemlerle (ortalama, medyan, mod) doldurulur. Kategorik değişkenler (Sex, Embarked) etiketlenir ve gereksiz sütunlar (örn. Cabin, Name) çıkarılır.

4. Görselleştirme:
Veri setindeki bazı önemli özelliklerin dağılımları ve ilişkileri görselleştirilir. countplot ve histplot gibi grafiklerle verinin genel yapısı analiz edilir.

5. Model Kurma:
Veri eğitim ve test setlerine ayrılır. Logistic Regression, Decision Tree, Random Forest, and K-Nearest Neighbors (KNN) modelleri oluşturulup eğitilir.

6. Model Değerlendirme:
Her modelin performansı accuracy, precision, recall ve F1 skoru gibi metriklerle değerlendirilir. Çapraz doğrulama (cross-validation) ile modelin genel performansı ölçülür.
