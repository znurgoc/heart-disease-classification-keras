
Keras ile Kalp Hastalığı Sınıflandırma Projesi
🎯 Proje Amacı
Bu proje, açık kaynak bir veri seti üzerinde, Derin Öğrenme (Deep Learning) kullanarak kalp hastalığı varlığını tahmin eden bir model geliştirmeyi amaçlamaktadır. Proje, veri ön işleme, sinir ağı modelleme ve model performansını kapsamlı bir şekilde değerlendirme adımlarını içermektedir.

📊 Veri Seti
Bu proje için kullanılan veri seti, Kaggle'da bulunan halka açık Heart Disease Data Set veri setidir.

🛠️ Kullanılan Teknolojiler
Python

TensorFlow / Keras: Derin öğrenme modeli için

Pandas: Veri manipülasyonu için

Scikit-learn: Veri bölme ve değerlendirme metrikleri için

Matplotlib / Seaborn: Veri görselleştirme ve grafikler için

🧠 Model Mimarisi
Model, bir dizi yoğun (Dense) ve düşürme (Dropout) katmanından oluşan sıralı (Sequential) bir sinir ağıdır. Aşırı uyum (overfitting) sorununu önlemek için Dropout katmanları eklenmiştir.

📈 Model Performansı
Model, eğitim süreci sonunda ve test verisi üzerinde mükemmel bir performans sergilemiştir.

Test Verisi Doğruluğu: %82.07

Modelin En Yüksek Performans Metriği: AUC (Area Under the Curve)

AUC-ROC Eğrisi

Aşağıdaki grafik, modelin iki sınıfı birbirinden ayırma gücünü göstermektedir. Eğrinin sol üst köşeye ne kadar yakın olması, modelin performansının o kadar yüksek olduğunu gösterir.

Grafikte görüldüğü gibi, modelin AUC değeri 0.90'dır. Bu, modelin kalp hastalığı olan ve olmayan hastaları ayırt etme yeteneğinin çok güçlü olduğunu kanıtlamaktadır.

✅ Sonuç
Geliştirilen derin öğrenme modeli, kalp hastalığı tahmininde güvenilir ve yüksek bir doğrulukla çalışmaktadır. Bu proje, derin öğrenmenin tıbbi veri analizi gibi hassas alanlarda nasıl kullanılabileceğini göstermektedir.




<img width="918" height="630" alt="Ekran görüntüsü 2025-08-19 143628" src="https://github.com/user-attachments/assets/74636107-3485-4214-81c2-a24e4418e465" />






<img width="918" height="630" alt="Ekran görüntüsü 2025-08-19 143628" src="https://github.com/user-attachments/assets/b795e0db-95e8-4a22-aeb5-9554c76eeb65" />
