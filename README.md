# aygazyapayzeka

Fashion MNIST veri seti, kıyafet ve ayakkabı gibi 10 farklı kategoriye ait gri tonlamalı görüntülerden oluşur. Bu projede, Fashion MNIST veri seti üzerinde basit bir yapay sinir ağı (ANN) modeli ve iki klasik makine öğrenme modeli (Random Forest ve Decision Tree) kullanarak sınıflandırma yapılmıştır. 

Projede kullanılan ana Python kütüphaneleri ve araçları şunlardır:

- `numpy`: Sayısal işlemler ve diziler için.
- `pandas`: Veri manipülasyonu ve analizi için.
- `matplotlib`: Grafikler ve görselleştirme için.
- `seaborn`: Gelişmiş veri görselleştirmeleri için.
- `sklearn`: Makine öğrenme algoritmaları ve değerlendirme metrikleri için.
- `tensorflow.keras`: Derin öğrenme modelleri için.
- `warnings`: Uyarıları yönetmek için.

Fashion MNIST, MNIST veri setine benzer, ancak daha modern giysi görselleri içeren bir veri setidir. Her görüntü, 28x28 piksel boyutunda gri tonlamalı bir görüntüdür. Veri seti, toplam 70.000 görüntü içerir: 

- Eğitim seti: 60.000 görüntü
- Test seti: 10.000 görüntü

Her görüntü, 0 ile 9 arasında bir etikete sahiptir. Etiketler şunlardır:

1. Tişört
2. Pantolon
3. Kazak
4. Elbise
5. Ceket
6. Sandalet
7. Gömlek
8. Spor Ayakkabı
9. Çanta
10. Bot

Proje aşağıdaki adımlardan oluşmaktadır:

1. **Kütüphanelerin Eklenmesi**:
   - Gerekli kütüphaneler projeye dahil edilir.

2. **Veri Yükleme ve Hazırlama**:
   - Fashion MNIST veri seti yüklenir ve eğitim/test setlerine ayrılır.
   - Veriler normalize edilir (0-255 aralığındaki piksel değerleri 0-1 aralığına çekilir).

3. **Veri Görselleştirme**:
   - Eğitim setinden örnek görüntüler görselleştirilir.
   - Eğitim ve doğrulama kaybı ve doğruluk değerlerinin zaman içindeki değişimi grafiği çizilir.

4. **Model Eğitimi**:
   - Basit bir yapay sinir ağı (ANN) modeli oluşturulur ve eğitilir.
   - Modelin eğitim ve doğrulama performansı izlenir.

5. **Klasik Makine Öğrenmesi Modelleri**:
   - Random Forest ve Decision Tree algoritmaları kullanılarak modeller eğitilir ve değerlendirilir.
   - Bu modeller için karmaşıklık matrisleri oluşturulur ve görselleştirilir.

Projenin sonucunda her bir modelin performansı değerlendirilmiş ve karşılaştırılmıştır. ANN modeli genellikle daha yüksek doğruluk sağlar, ancak Random Forest ve Decision Tree modelleri de hızlı ve açıklanabilir sonuçlar sunar.

## Referanslar

- Fashion MNIST Veri Seti
- Keras Documentation
- Scikit-Learn Documentation
