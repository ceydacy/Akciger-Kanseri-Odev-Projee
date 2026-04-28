🫁 Akciğer Kanseri Tahmini (Lung Cancer Prediction)
Bu proje, klinik ve demografik verileri kullanarak bir bireyde akciğer kanseri olup olmadığını tahmin etmek amacıyla geliştirilmiş bir makine öğrenmesi çalışmasıdır. Proje kapsamında farklı sınıflandırma algoritmaları eğitilmiş ve performansları karşılaştırılmıştır.

📊 Veri Seti Hakkında
Kullanılan veri seti, 309 farklı bireyden toplanan 16 klinik parametreyi içermektedir. Veri setindeki temel özellikler şunlardır:

Demografik Bilgiler: Yaş, Cinsiyet.

Klinik Parametreler: Sigara kullanımı, parmaklarda sararma, anksiyete, akran baskısı, kronik hastalıklar, yorgunluk, alerji, hırıltılı nefes alma, alkol tüketimi, öksürük, nefes darlığı, yutma güçlüğü, göğüs ağrısı.

Hedef Değişken (Target): LUNG_CANCER (Akciğer Kanseri Durumu - Evet/Hayır)

🛠️ Kullanılan Teknolojiler
Python (Dil)

Pandas & NumPy (Veri Analizi)

Matplotlib & Seaborn (Veri Görselleştirme)

Scikit-learn (Makine Öğrenmesi Modelleri ve Metrikler)

🧠 Makine Öğrenmesi Modelleri
Proje boyunca aşağıdaki modeller eğitilmiş ve test edilmiştir:

Random Forest Classifier (%96.77 Doğruluk) - En Başarılı Model

K-Nearest Neighbors (KNN) (%95.16 Doğruluk)

Logistic Regression (%95.16 Doğruluk)

Decision Tree Classifier (%96.77 Doğruluk)

📈 Model Performansı ve Bulgular
Random Forest, hem doğruluk hem de Duyarlılık (Recall: %98.33) oranları ile sağlık verileri için en güvenilir sonuçları vermiştir.

Lojistik Regresyon, doğrusal ilişkileri anlamada ve küçük veri setlerinde oldukça stabil sonuçlar sergilemiştir.

Veri setindeki sınıflar arasında dengesizlik (kanser vakalarının yoğunluğu) saptanmış, bu durumun model eğitimine etkisi analiz edilmiştir.
