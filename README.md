# Parmak Algılama ve Sayma Projesi

Gerçek zamanlı olarak parmakları algılayan ve sayan bir bilgisayar görüsü projesi. Kameranın önünde elinizi açtığınızda kaç parmak gösterdiğinizi anlık olarak tespit ediyor.

## 🖐️ Ne İşe Yarar? 

Ellerinizi kamera önünde hareket ettirdiğinizde, sistem parmak sayısını tespit edip sayıyor. Hızlı, güvenilir ve gerçek zamanlı çalışıyor. Temassız kontrol sistemleri, eğitim araçları veya erişilebilirlik çözümleri için harika bir başlangıç noktası.

## ✨ Özellikler

- ⚡ **Gerçek Zamanlı Tespit**: Anlık ve hızlı işleme
- ✋ **Parmak Sayma**: 0-5 arası parmak tespiti
- 🎯 **Yüksek Doğruluk**: Güvenilir el ve parmak tanıma
- 🚀 **Optimize Edilmiş**: Performans odaklı kod yapısı
- 📹 **Webcam Desteği**: Herhangi bir kamerayla çalışır

## 🎮 Kullanım Alanları

- **Temassız Arayüzler**: Dokunmadan kontrol sistemleri
- **Eğitim Araçları**: İşaret dili öğrenme uygulamaları
- **Oyun Geliştirme**: El hareketleriyle oyun kontrolü
- **Erişilebilirlik**: Engelli bireyler için alternatif kontrol yöntemleri
- **Sunum Araçları**: Uzaktan kumanda yerine el hareketleri

## 📦 Gereksinimler

Projeyi çalıştırmak için şunlara ihtiyacınız var:

```bash
pip install opencv-python
pip install mediapipe
pip install numpy
```

## 🚀 Nasıl Çalıştırılır?

1. Projeyi bilgisayarınıza indirin: 

```bash
git clone https://github.com/faikaktss/Finger_Detection_and_Counting_Project.git
cd Finger_Detection_and_Counting_Project
```

2. Gerekli kütüphaneleri yükleyin: 

```bash
pip install -r requirements.txt
```

3. Ana dosyayı çalıştırın:

```bash
python main.py
```

4. Kameranızın karşısına geçin ve elinizi gösterin!  🖐️

## 🎯 Nasıl Çalışır?

Proje, Google'ın MediaPipe kütüphanesini ve OpenCV'yi kullanarak: 

1.  Kameradan görüntü alır
2. Eldeki kilit noktaları (landmark) tespit eder
3. Parmak pozisyonlarını analiz eder
4. Kaç parmağın açık olduğunu sayar
5. Sonucu ekranda gösterir

Tüm bu işlemler saniyede onlarca kez tekrarlanarak gerçek zamanlı deneyim sağlar.

## 🛠️ Geliştirme Fikirleri

Bu projeyi şöyle geliştirebilirsiniz: 

- 👆 Farklı el jestlerini tanıma (rock, paper, scissors)
- 🎨 Sanal beyaz tahtaya parmakla çizim yapma
- 🎵 El hareketleriyle müzik kontrolü
- 🎮 Basit oyunlar için kontrol mekanizması
- 📊 İstatistik ve kayıt özellikleri

## 🤝 Katkıda Bulunun

Bu projeyi daha iyi hale getirmek için fikirlerinizi paylaşabilirsiniz:

- 🐛 Hata buldunuz mu? [Issue açın](https://github.com/faikaktss/Finger_Detection_and_Counting_Project/issues)
- 💡 Yeni bir özellik mi aklınıza geldi? Pull request gönderin!
- ⭐ Beğendiyseniz yıldız vermeyi unutmayın

## 📝 Notlar

- İyi ışıklandırma sonuçları iyileştirir
- Kamera mesafesi 40-80 cm arası ideal
- Karmaşık arka planlar performansı etkileyebilir
- Tek el tespiti için optimize edilmiştir

## 🔧 Sorun Giderme

**Kamera açılmıyor mu?**  
Kamera izinlerini kontrol edin veya başka bir kamera indeksi deneyin.

**Parmaklar doğru sayılmıyor mu?**  
Işık koşullarınızı düzeltin ve kamerayı düz tutun.

**Yavaş çalışıyor mu?**  
Görüntü çözünürlüğünü düşürün veya FPS sınırı koyun.

## 📄 Lisans

Açık kaynak bir projedir. Öğrenmek, geliştirmek ve paylaşmak için özgürce kullanabilirsiniz.

---

