# Sahte Haber Tespiti (Apache Spark ile)

Bu proje, sahte ve gerçek haberleri ayırt etmek için Apache Spark kullanılarak geliştirilmiş bir makine öğrenmesi uygulamasıdır. Proje kapsamında model eğitimi, veri işleme ve tahmin süreci Jupyter Notebook ortamında gerçekleştirilmiştir.

## 🧠 Kullanılan Teknolojiler

- Python
- Apache Spark
- PySpark
- Jupyter Notebook
- Makine Öğrenmesi (MLlib)
- Doğal Dil İşleme (NLP)

## ⚙️ Kurulum

1. Depoyu klonlayın:
    ```bash
    git clone https://github.com/kullanici_adi/spark-sahteHaberTespiti.git
    cd spark-sahteHaberTespiti
    ```

2. Gerekli Python kütüphanelerini yükleyin (örnek):
    ```bash
    pip install pyspark notebook
    ```

3. `etiketli_haberler.csv` dosyasını kullanarak `modelegitim.ipynb` üzerinden modeli eğitin veya mevcut `fake_news_model.zip` dosyasını kullanarak `app.ipynb` üzerinden tahminler yapın.

## 📝 Notlar

- Model eğitimi sırasında metinler temizlenmiş, TF-IDF vektörleri kullanılmış ve sınıflandırma için bir MLlib algoritması tercih edilmiştir.
- Bu proje eğitim amaçlıdır ve daha gelişmiş uygulamalar için farklı veri kaynakları ve modellerle genişletilebilir.
