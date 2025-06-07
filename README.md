# hafiza-oyunu-pic16f877a
PIC16F877A ile geliştirilen renk-sayı eşleşmeli, LCD ve LED destekli hafıza oyunu.
## 🧠 Hafıza Oyunu (Gömülü Sistemler Projesi)

Bu proje, **PIC16F877A** mikrodenetleyicisi kullanılarak geliştirilen bir **hafıza ve dikkat odaklı oyun sistemidir**. Kullanıcının kısa süreli hafıza becerilerini test etmek için tasarlanmış, LED'ler, LCD ekran ve buzzer gibi çevresel donanımlarla desteklenmiş bir uygulamadır.

> 🧑‍💻 Proje sahibi: **Rukiye İlhan**

---

### 🎯 Projenin Amacı

Bu oyun sistemi, kullanıcılara kısa süreli **renk-sayı eşleşmeleri** sunarak ezberleme ve hatırlama yeteneklerini test eder. Kullanıcılar bu eşleşmeleri doğru hatırlayıp, **ilgili butona** basarak puan kazanır. Yanlış hatırlamalarda puan kaybeder ve sesli uyarı alırlar.

---

### ⚙️ Kullanılan Donanım Bileşenleri

* ✅ **PIC16F877A** mikrodenetleyici
* ✅ **5 adet LED** (renkli)
* ✅ **5 adet buton**
* ✅ **16x2 LCD ekran**
* ✅ **Aktif buzzer**
* ✅ Kristal osilatör (20 MHz)
* ✅ Breadboard ve jumper kabloları
* ✅ Proteus ile simülasyon desteği

---

### 🎮 Oyun Kuralları

* Kullanıcıya rastgele **5 sayı-renk eşleşmesi** gösterilir.
* Her doğru renk seçimi: **+20 puan**
* Her yanlış renk seçimi: **-5 puan + sesli uyarı**
* Oyun toplam **3 tur** sürer.
* Oyun sonunda toplam puan LCD üzerinde gösterilir.

---

### 🧠 Proje Özellikleri

| Özellik            | Açıklama                                   |
| ------------------ | ------------------------------------------ |
| **Rastgelelik**    | Timer0 üzerinden üretilen değerlerle       |
| **Giriş kontrolü** | Her buton için ayrı kontrol ve debounce    |
| **Geribildirim**   | LED yanması, buzzer sesi, LCD ekran mesajı |
| **Skor sistemi**   | Her turda güncellenen toplam skor          |
| **Yazılım**        | PIC Assembly yerine C dili kullanılmıştır  |

---

### 📷 Görsel Örnekler

> Proteus simülasyonu ve breadboard kurulumu ile ilgili görseller `
> ![image](https://github.com/user-attachments/assets/83ee8659-3672-4a69-861e-8bdc30ce322e)
![image](https://github.com/user-attachments/assets/f5070d3f-fd4c-467a-9041-84223e479caf)
![image](https://github.com/user-attachments/assets/0629dfed-7d7a-43f5-a694-e9b52bb5061e)
![image](https://github.com/user-attachments/assets/0dbd34a3-32a8-4e63-9c07-ce122548bee5)
![image](https://github.com/user-attachments/assets/2f3671e6-f9ba-4cfc-abd3-022feab86d35)
![image](https://github.com/user-attachments/assets/cc700b66-e9b6-4483-915e-cf75efc601ea)
![image](https://github.com/user-attachments/assets/0e2e7b82-6cf0-4e68-b1b8-1f49a9f118df)


---

### 🔍 Teknik Yeterlilik

Bu proje ile;

* ✅ Gömülü sistemlerde temel programlama bilgisi
* ✅ PIC mikrodenetleyici ile donanım etkileşimi
* ✅ Simülasyon ve gerçek devre farklarının yönetimi
* ✅ Oyun mantığı, zamanlama, giriş/çıkış kontrolleri

gibi birçok mühendislik yetkinliği tek başına geliştirilmiştir.
---

### 🗂️ Dosya Yapısı

```plaintext
/proje_kodu/     -> Ana C dosyası (.c)
/proteus/        -> Proteus çizimi (.dsn)
/images/         -> Proje görselleri
README.md        -> Açıklama dosyası
```

---

### 🗒️ Geliştirme Süreci

| Tarih      | Aşama                           |
| ---------- | ------------------------------- |
| 20.05.2025 | Fikir belirleme ve planlama     |
| 21.05.2025 | Devre çizimi ve malzeme listesi |
| 25.05.2025 | Kodlamaya başlandı              |
| 30.05.2025 | Simülasyon ve testler           |
| 02.06.2025 | Gerçek devre kurulumu ve sunum  |

---

### 📌 Ek Bilgiler

* Kod **PIC16F877A**'ya özel olarak yazılmıştır.
* Simülasyon, **Proteus** yazılımında denenmiş ve başarıyla çalışmıştır.
* Breadboard devresi fiziksel olarak test edilmiştir.

---

### 🤝 Lisans

Bu proje eğitim amaçlıdır. Kaynak kodları açık olup, bireysel çalışmalar ve benzeri eğitim projelerinde referans olarak kullanılabilir.

---

### 📮 İletişim

> **Rukiye İlhan**
> Bilgisayar Mühendisliği Öğrencisi
> `ilhanxrukiye@gmail.com`
