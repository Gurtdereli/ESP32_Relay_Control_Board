# ESP32 Röle Kontrol Kartı Tasarımı

Bu proje, **Altium Designer** kullanılarak geliştirilen bir **ESP32 tabanlı röle kontrol kartı**na ait PCB tasarımını içerir. Çalışma kapsamında, şematik çizimden üretim dosyalarının hazırlanmasına kadar tüm adımlar ele alınmıştır.

📚 Kaynak kurs: [PCB Uygulaması-3: ESP32 Röle Kontrol Kartı Tasarımı](https://xbowtie.com/kurs/pcb-uygulamasi-3-esp32-role-kontrol-karti-tasarimi-c3649) (Mart 2025 güncellemesi)

---

## 📑 İçindekiler

1. [Proje Hakkında](#proje-hakkında)  
2. [Gereksinimler](#gereksinimler)  
3. [Amaçlar](#amaçlar)  
4. [Adımlar](#adımlar)  
5. [Dosya Yapısı](#dosya-yapısı)  
6. [Kurulum ve Çalıştırma](#kurulum-ve-çalıştırma)  
7. [Üretim Çıktıları](#üretim-çıktıları)  
8. [Lisans](#lisans)  
9. [Katkıda Bulunanlar](#katkıda-bulunanlar)

---

## 🔎 Proje Hakkında

Bu proje, **ESP32 röle kontrol kartı** tasarımının adım adım oluşturulmasını amaçlar. Kurs sürecinde şematik tasarım, komponent yerleşimi, routing (yol çizimi), DRC kontrolleri ve Gerber dosyalarının hazırlanması gibi tüm PCB tasarım aşamaları gösterilmektedir.  

Ayrıca, proje GitHub’a yüklenerek paylaşım adımları da örneklendirilmiştir.

---

## 💻 Gereksinimler

- **Donanım:** En az 8 GB RAM’e sahip bilgisayar  
- **Yazılım:** Altium Designer  
- **Bilgi:** Temel elektronik devre ve PCB tasarımı bilgisi önerilir

---

## 🎯 Amaçlar

- ESP32 tabanlı röle kontrol devresini tasarlamak  
- USB ve güç devresini projeye eklemek (CH340C USB–Serial, voltaj regülatörü)  
- Şematik ve PCB tasarım süreçlerini öğrenmek  
- Routing (temel yollar, differential pair, GND pour) tekniklerini uygulamak  
- DRC kontrollerini gerçekleştirmek  
- Gerber dosyaları ve 3D çıktılar almak  
- GitHub üzerinden paylaşım yapmak  

---

## 🛠️ Adımlar

1. Genel diagramın oluşturulması  
2. USB ve güç bağlantılarının eklenmesi  
3. ESP32 ve röle devresinin şematik tasarımı  
4. Konektör ve bileşen yerleşimi  
5. Routing (yol çizimi) ve katman yönetimi  
6. Yazıların ve referansların düzenlenmesi  
7. DRC kontrollerinin yapılması  
8. Gerber ve 3D çıktılarının hazırlanması  
9. Projenin GitHub’a yüklenmesi  

---

## 📂 Dosya Yapısı

```
ESP32-Relay-PCB/
├── schematics/       # Şematik çizim dosyaları (.SchDoc)
├── pcb_layout/       # PCB tasarım dosyaları (.PcbDoc)
├── gerber/           # Gerber ve üretim çıktıları
├── libraries/        # Kullanılan komponent kütüphaneleri
├── README.md         # Proje açıklamaları (bu dosya)
└── LICENSE           # Lisans dosyası
```

---

## 🚀 Kurulum ve Çalıştırma

1. **Altium Designer** açın.  
2. `schematics/` klasöründeki `.SchDoc` dosyasını açın.  
3. `pcb_layout/` klasöründeki `.PcbDoc` dosyası üzerinden PCB tasarımını inceleyin.  
4. `gerber/` klasöründen üretim dosyalarına erişebilirsiniz.  

---

## 📦 Üretim Çıktıları

- Gerber dosyaları (PCB üretimi için hazır)  
- 3D model çıktıları  
- Şematik ve PCB dosyaları  

---

## 📜 Lisans

Bu proje için **MIT Lisansı** önerilmektedir.  
Lisans dosyasını (`LICENSE`) inceleyebilirsiniz.

---

## 👥 Katkıda Bulunanlar

- **Hazırlayan:** Arif Mandal  
- **Kurs Sağlayıcısı:** [xBowtie](https://xbowtie.com) (Mart 2025 güncellemesi)  

---
