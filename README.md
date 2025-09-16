# 💰 Yıllık Gelir Tahmini Projesi

Proje makine öğrenmesi problemlerinden biri olan gelir seviyesi tahmini üzerine yaptığım bir çalışmayı içeriyor.

Temel amaç bir kişinin yaş, eğitim, meslek gibi bilgilerine bakarak yıllık gelirinin **50.000$'ı aşıp aşmayacağını** tahmin eden bir sınıflandırma modeli geliştirmek.

## 📊 Veri Seti

Projede kullanılan veri seti `data/income_evaluation.csv` dizininde bulunuyor. Amerika'da yaşayan insanlara ait çeşitli bilgiler içeren ve makine öğrenmesi dünyasında oldukça popüler olan bir veri setidir.

## 🛠️ Kullandığım Kütüphaneler

* **Pandas & Numpy**
* **Matplotlib & Seaborn**
* **Scikit-learn:**

## 🚀 Nasıl Çalıştırılır?

**1. Projeyi Bilgisayara Klonlayın:**

```bash
git clone https://github.com/emregergin/income-evaluation
cd income-evaluation
```

**2. Gerekli Kütüphaneleri Yükleyin:**

```bash
pip install -r requirements.txt
```

**3. Jupyter Notebook'u Başlatın:**

```bash
jupyter notebook
```

Artık kodları inceleyebilirsiniz ve hücreleri çalıştırarak sonuçları kendiniz de görebilirsiniz.

## 📝 Projeden Notlar

Notebook'un içinde veri ön işleme, eksik verilerin doldurulması ve veri görselleştirme gibi adımları bulabilirsiniz. İlk başta model olarak RandomForestClassifier kullandım. Sonrasında ise en iyi performansı veren modeli bulmak için RandomizedSearchCV kullandım.

Sonuç olarak geliştirdiğim model test verisi üzerinde yaklaşık %86 doğruluk (accuracy) oranına ulaştı. Sonuçları görmek için notebook'taki classification_report ve confusion_matrix çıktılarına göz atabilirsiniz.
