# TensorFlow Kedi-Köpek Sınıflandırma Projesi

Bu proje, TensorFlow ve Keras kullanarak 25.000 resimlik bir veri seti ile bir modeli eğitir ve bu modeli kedi/köpek tahmini yapmak için kullanır.

## Proje Dosyaları
* `main.py`: Modeli eğitir ve `cats_vs_dogs_model.h5` olarak kaydeder.
* `predict.py`: Kaydedilmiş modeli yükler ve `test_image.jpg` üzerinde tahmin yapar.

## Kurulum ve Kullanım

1. **Gerekli kütüphaneler:**
   ```bash
   pip install tensorflow matplotlib h5py