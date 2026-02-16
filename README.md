# 🖐️ B.G.B.O.

MediaPipe ve OpenCV kullanarak geliştirilmiş, el hareketleriyle bilgisayarın temel fonksiyonlarını kontrol etmeyi sağlayan gelişmiş bir yapay zeka arayüzüdür. Ses, parlaklık, medya ve interaktif bir çizim tahtasını temassız bir şekilde yönetmenize olanak tanır.

## 🚀 Öne Çıkan Özellikler

* **Akıllı El Kilitleme:** Ekrandaki birden fazla el arasından ana kullanıcıyı takip eder, kontrol karmaşasını önler.
* **Çoklu Kontrol Modları:**
* 🔊 **Ses Kontrolü:** Dikey bir bar üzerinden sistem sesini ayarlar.
* ☀️ **Parlaklık:** Ekran parlaklığını gerçek zamanlı günceller.
* 🎵 **Medya Kontrolü:** Şarkı geçme/durdurma (pyautogui entegrasyonu).
* 🎨 **Neon Canvas:** Çift el destekli çizim modu. Bir elinizle kalem/silgi seçerken diğeriyle çizim yapabilirsiniz.


* **Neon UI Arayüzü:** OpenCV üzerinde oluşturulmuş, görsel geri bildirim veren şık ve modern butonlar.
* **Tam Ekran Desteği:** Tek bir el hareketiyle pencere modundan tam ekrana geçiş.

## 🛠️ Teknik Gereksinimler

Projenin çalışması için aşağıdaki kütüphanelerin yüklü olması gerekir:

```
pip install opencv-python mediapipe numpy screen-brightness-control pyautogui pycaw comtypes
```

## 🎮 Kullanım Talimatları

1. **Tıklama Mantığı:** İşaret parmağı ve baş parmağınızı birbirine yaklaştırmak "Tıklama" (Click) işlemini gerçekleştirir.
2. **Menü Geçişleri:** Menüdeki butonların üzerine gelip parmaklarınızı birleştirerek modlar arasında geçiş yapın.
3. **Çizim Modu:** * Sol elinizle sol taraftaki **KALEM** kutusunun üzerinde bekleyin.
* Sağ elinizle ekranda çizim yapmaya başlayın.
* Temizlemek için üstteki **SIL** butonunu kullanın.


### ⚠️ Not

Bu uygulama kamera erişimi ve sistem ayarlarını (ses/parlaklık) değiştirme yetkisi gerektirir. En iyi performans için iyi aydınlatılmış bir ortam önerilir.
