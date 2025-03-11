# 📸 OpenCV Öğrenme Alanı

## 📌 Proje Hakkında
Bu repo, **OpenCV ve NumPy** kullanarak temel görüntü işleme tekniklerini öğrenmek ve denemek amacıyla oluşturulmuştur. İçerikte, OpenCV'nin temel fonksiyonları, matris işlemleri, görüntü filtreleme ve manipülasyon gibi konular ele alınmaktadır.

---

## 📂 Dosya Yapısı
Projedeki ana dosyalar şunlardır:

- **`openCV.ipynb`** → OpenCV'nin temel fonksiyonlarını öğrenmek için oluşturulmuş Jupyter Notebook dosyası
- **Görseller** → Çalıştırma sırasında kullanılan örnek görseller
- **Diğer yardımcı dosyalar** (Gerektiğinde eklenebilir)

---

## 🔧 Kullanılan Kütüphaneler
Bu proje kapsamında aşağıdaki Python kütüphaneleri kullanılmıştır:

- **OpenCV (cv2)** → Görüntü işleme fonksiyonları
- **NumPy** → Matris işlemleri ve veri manipülasyonu
- **Matplotlib** → Görsellerin gösterimi

Kurulum için aşağıdaki komutu çalıştırabilirsiniz:
```bash
pip install opencv-python numpy matplotlib
```

---

## ⚙️ Kurulum & Çalıştırma
1. Gerekli kütüphaneleri yükleyin.
2. Jupyter Notebook ortamında **openCV.ipynb** dosyasını açın.
3. Hücreleri adım adım çalıştırarak OpenCV işlemlerini öğrenin.

Alternatif olarak, Jupyter Notebook kurulu değilse aşağıdaki komutla çalıştırabilirsiniz:
```bash
jupyter notebook
```
ve ardından **openCV.ipynb** dosyasını açabilirsiniz.

---

## 📊 OpenCV Temelleri
Bu notebook içinde aşağıdaki konular işlenmektedir:

- OpenCV ile **görüntü okuma ve gösterme**
- **Matris işlemleri** ve NumPy ile entegrasyon
- **Filtreleme ve görüntü manipülasyonu**
- **Kenar algılama ve eşikleme teknikleri**

Örnek bir kod parçası:
```python
import cv2
import numpy as np
import matplotlib.pyplot as plt

img = cv2.imread('ornek_resim.jpg', cv2.IMREAD_GRAYSCALE)
plt.imshow(img, cmap='gray')
plt.show()
```

---

## 📝 Katkıda Bulunma & Lisans
Bu proje kişisel öğrenme amaçlıdır ve herkese açıktır. Geliştirmeye katkıda bulunmak isterseniz **pull request** gönderebilir veya issue açabilirsiniz!

🚀 **Hazırlayan:** NamKodX
