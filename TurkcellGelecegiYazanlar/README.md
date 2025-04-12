# 📊 Turkcell Geleceği Yazanlar - Makine Öğrenmesi Uygulamaları – 

Bu repoda, Turkcell Geleceği Yazanlar Veri Bilimi eğitim programı kapsamında gerçekleştirilmiş çeşitli makine öğrenmesi algoritmalarının uygulamaları yer almaktadır. Kodlar Jupyter Notebook ortamında yazılmış olup her model için örnek veri setleriyle birlikte sonuçlar değerlendirilmiştir.

---

## 🧱 Klasör Yapısı

### 📁 `201/` – Regresyon Modelleri

Bu bölümde farklı regresyon algoritmaları kullanılarak tahmin modelleri oluşturulmuştur.

| Model                 | Açıklama                                      |
|----------------------|-----------------------------------------------|
| `Coklu-Dogrusal-Reg` | Birden fazla bağımsız değişkenli regresyon     |
| `Dogrusal-Reg`       | Basit doğrusal regresyon                       |
| `Elasticnet`         | L1 ve L2 ceza terimlerinin kombinasyonu       |
| `Lasso-Reg`          | L1 tabanlı ceza ile değişken seçimi           |
| `Ridge-Reg`          | L2 tabanlı ceza ile aşırı öğrenmenin azaltılması |

Her klasörde:
- Model uygulaması: `.ipynb`
- Örnek veri: `data.csv`

---

### 📁 `301/` – Sınıflandırma Modelleri

Bu bölümde farklı sınıflandırma algoritmaları ile veri kümesi sınıflandırılmıştır.

| Model | Açıklama                            |
|-------|-------------------------------------|
| `ANN` | Yapay Sinir Ağı (Artificial Neural Network) |
| `CART`| Karar ağacı tabanlı sınıflandırıcı |
| `K-NN`| K-En Yakın Komşu algoritması        |
| `SVM` | Destek Vektör Makineleri            |

Her klasörde:
- Model uygulaması: `.ipynb`
- Örnek veri: `data.csv`

---

## ⚙️ Kullanım

Kurulum için aşağıdaki Python kütüphaneleri gereklidir:

```bash
pip install pandas scikit-learn matplotlib seaborn

