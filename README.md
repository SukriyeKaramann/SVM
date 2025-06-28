# SVM ile İris Veri Seti Sınıflandırması

Bu proje, sklearn kütüphanesindeki İris veri setini kullanarak **Destek Vektör Makinesi (SVM)** ile iki sınıflı bir sınıflandırma gerçekleştirmektedir. İki farklı çekirdek (kernel) fonksiyonu ile modeller eğitilip karşılaştırılmıştır.

---

## 🚀 Proje Özeti

- Veri seti: İris veri seti (yalnızca iki sınıf ve ilk iki özellik kullanılmıştır)
- Amaç: İki tür iris çiçeğini (setosa ve versicolor) sepal uzunluğu ve genişliği kullanarak sınıflandırmak
- Modeller:
  - Linear kernel ile SVM
  - RBF (Radial Basis Function) kernel ile SVM
- Performans değerlendirmesi:
  - Sınıflandırma raporu (precision, recall, f1-score)
  - Karışıklık matrisi (confusion matrix)
- Karar sınırlarının görselleştirilmesi

---

## 📋 Kullanılan Kütüphaneler

- numpy
- matplotlib
- scikit-learn

---

## 📈 Model Eğitimi ve Değerlendirme

1. Veri ön işleme:
   - İris veri setinden sadece iki sınıf (`setosa` ve `versicolor`) ve ilk iki özellik (sepal length, sepal width) seçildi.
   - Veri %80 eğitim, %20 test olarak ayrıldı.

2. Modeller:
   - **Linear SVM**: Doğrusal ayırıcı kullanıldı.
   - **RBF SVM**: Radial Basis Function kernel ile karmaşık karar sınırları öğrenildi.

3. Performans değerlendirmesi:
   - Her modelin test verisi üzerindeki sınıflandırma raporu yazdırıldı.
   - RBF SVM için karışıklık matrisi gösterildi.
   - Eğitim verisi üzerinde karar sınırları grafik olarak çizildi.

---

## 🛠️ Çalıştırma Talimatları

1. Gerekli kütüphaneleri yükleyin:

```bash
pip install numpy matplotlib scikit-learn
