Elbette! İşte **bu dosyaya uygun bir README.md** örneği (Jupyter Notebook için hazırlanmış, eğitim veya proje formatına uygun şekilde):

---

# 🖼️ Dijital Görüntü İşleme – Hafta 2

### 📘 OpenCV ile Görüntü Okuma ve Temel Kanal Yapısı

Bu dosya, dijital görüntü işleme dersinin ikinci haftasında ele alınan **görüntü okuma, renk kanalları ve piksel temsili** konularını içermektedir.
Python ve OpenCV kütüphanesi kullanılarak, dijital bir görüntünün bilgisayar ortamında nasıl temsil edildiği adım adım açıklanmıştır.

---

## 📚 İçerik Başlıkları

1. **Görüntü Okuma (cv2.imread)**

   * Renkli (RGB/BGR) ve gri seviye (Grayscale) görüntülerin okunması
   * Dosya okuma modları:

     * `cv2.imread(dosya, 0)` → Gri seviye
     * `cv2.imread(dosya, 1)` → Renkli (RGB/BGR)

2. **Renk Modelleri: RGB ve BGR**

   * OpenCV’nin varsayılan olarak BGR kanal sıralamasını kullanması
   * RGB ↔ BGR dönüşümü

3. **Piksel Değerleri ve Veri Tipleri**

   * `uint8` veri tipi: 0–255 arası değerler
   * 8 bitlik kanal yapısının anlamı

4. **Görüntü Boyutları ve Yapısı**

   * Satır (yükseklik) ↔ sütun (genişlik) ilişkisi
   * Kanal sayısının görüntü türüne göre değişimi

     * 1 kanal → Gri ton
     * 3 kanal → Renkli (RGB)

---

## 🧩 Kullanılan Kütüphaneler

* `cv2` (OpenCV)
* `numpy` *(bazı işlemlerde gereklidir)*

---

## 🚀 Çalıştırma

1. Gerekli kütüphaneleri kurun:

   ```bash
   pip install opencv-python numpy
   ```

2. Jupyter Notebook ortamında dosyayı açın:

   ```bash
   jupyter notebook BST_Hafta_2.ipynb
   ```

3. Hücreleri sırayla çalıştırarak görüntü okuma ve kanal analizini inceleyin.

---

## 🎯 Amaç

Bu çalışmanın amacı, dijital görüntülerin bilgisayar ortamında nasıl temsil edildiğini, renkli ve gri seviye görüntüler arasındaki farkı anlamak ve **OpenCV kütüphanesi ile temel görüntü çözümleme temellerini öğrenmektir.**

---

İstersen bu README’ye örnek çıktı görselleri veya “Sonuç” bölümü de ekleyebilirim (örneğin bir RGB ve grayscale görüntü örneği açıklamasıyla). Ekleyeyim mi?
