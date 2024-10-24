# Proje: Hiperparametre Optimizasyonu ile Görüntü Sınıflandırma
### Bu proje, bir balık veri kümesi kullanarak görüntü sınıflandırma modeli geliştirmeye odaklanmaktadır. Modelin performansını artırmak için hiperparametre optimizasyonu uygulanmış ve aşırı öğrenmeyi önlemek hedeflenmiştir. 
### Kaggle Notebook: https://www.kaggle.com/code/buketgrlek/global-ai-hub-deep-learning-project
### Aşağıdaki adımlar uygulanmıştır:

## Veri Toplama ve Ön İşleme:

* Büyük ölçekli veri kümesinden görsel yolları ve etiketler çıkarılır.
* Görseller boyutlandırılır ve normalize edilir.
## Eğitim-Test Ayrımı:

* Veriler %80 - %20 oranında eğitim ve test setlerine ayrılır.
## Etiket Kodlama:

* LabelEncoder ve One-Hot Encoding ile etiketler sayısal formata dönüştürülür.
## Model Eğitimi ve Hiperparametre Optimizasyonu:

* Batch işleme uygulanır ve en uygun konfigürasyonu bulmak için hiperparametreler ayarlanır.
## Gereksinimler
* Python 3.x
* NumPy, Pandas, Scikit-learn, TensorFlow/Keras (model eğitimi için)
* Görüntü kütüphaneleri: PIL veya TensorFlow Image API
## Nasıl Çalıştırılır?
1. Gerekli kütüphaneleri pip install -r requirements.txt komutuyla kurun.
2. Veri kümesini ilgili dizine yükleyin.
3. Not defterini çalıştırın: jupyter notebook Image Classification with Hyperparameter Optimize.ipynb.
4. Model performansını değerlendirin ve hiperparametreleri gerektiğinde ayarlayın.
