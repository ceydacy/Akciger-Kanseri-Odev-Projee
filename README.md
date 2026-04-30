# 🫁 Akciğer Kanseri Tahmini (Lung Cancer Prediction)

Bu proje, klinik ve demografik verileri kullanarak bir bireyde akciğer kanseri olup olmadığını tahmin etmek amacıyla geliştirilmiş bir makine öğrenmesi çalışmasıdır. Proje kapsamında farklı sınıflandırma algoritmaları eğitilmiş ve performansları karşılaştırılmıştır.

## Veri Seti Analizi (EDA)
Kullanılan veri seti, 309 bireye ait 16 farklı klinik parametre içermektedir.
*   **Klinik Bulgular:** Sigara kullanımı, anksiyete, kronik hastalıklar, hırıltılı solunum, alkol kullanımı, öksürük, nefes darlığı, yutma güçlüğü ve göğüs ağrısı.
*   **İstatistiksel Özellikler:** Veri setindeki yaş ortalaması **62.6**'dır ve kanserli vaka yoğunluğu ("YES") yüksektir.

## Kullanılan Teknolojiler
*   **Dil:** Python
*   **Kütüphaneler:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
*   **Platform:** Google Colab / Jupyter Notebook

## Makine Öğrenmesi Modelleri
Projede aşağıdaki sınıflandırma modelleri uygulanmış ve karşılaştırılmıştır:
1. **Random Forest Classifier**
2. **K-Nearest Neighbors (KNN)**
3. **Logistic Regression**
4. **Decision Tree Classifier**

## Performans Sonuçları
Veri seti **%80 eğitim** ve **%20 test** olarak bölünerek modeller objektif bir şekilde değerlendirilmiştir. Elde edilen temel bulgular şöyledir:

*   **En Başarılı Model:** Random Forest ve Decision Tree modelleri **%96.77** doğruluk (Accuracy) oranıyla en yüksek performansı göstermiştir.
*   **Sağlık Sektörü İçin Kritik Metrik (Recall):** Kanser vakalarını kaçırmama oranı (Recall), Random Forest modelinde **%98.33** ile en güvenilir seviyededir.
*   **Hata Analizi:** Random Forest modeli, 62 test verisinden sadece 2 tanesinde hatalı tahmin yapmıştır.

## Model Açıklanabilirliği (Feature Importance)
Modelin karar verme sürecinde en çok hangi semptomlara önem verdiği analiz edilmiştir. Bu analiz, teşhis sürecinde hangi klinik bulguların (örneğin; nefes darlığı veya hırıltılı solunum) model tahmini için daha belirleyici olduğunu bilimsel olarak ortaya koymaktadır.

## Kurulum ve Çalıştırma
Projeyi yerel ortamınızda çalıştırmak için:
1. Bu depoyu klonlayın: `git clone https://github.com/ceydacy/Akciger-Kanseri-Odev-Projee.git`
2. Gerekli kütüphaneleri yükleyin: `pip install pandas scikit-learn matplotlib seaborn`
3. `.ipynb` dosyasını Jupyter Notebook veya Google Colab ile açarak tüm hücreleri çalıştırın.

---
## Proje Ekibi
Bu proje aşağıdaki ekip üyeleri tarafından ortaklaşa geliştirilmiştir:

*   **[Ceyda Çay]**
*   **[Sefa İçbudak]** 
*   **[Ali Sadi Akkuş]** 
---
*Bu çalışma, Makine Öğrenmesi dersi kapsamında hazırlanan ortak bir projedir.*
