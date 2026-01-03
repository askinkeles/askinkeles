# 🧱 Donanım Mühendisliği & Gömülü Sistemler

Bu bölüm, elektronik tasarımı, bileşen seçimi ve firmware mimarisi konusundaki teknik uzmanlığımı ve açık kaynak rehberlerimi içerir.

## ⚡ Elektronik Bileşenler & Düşük Seviye Haberleşme
* **Ayrık Bileşenler:** Endüstriyel gereksinimlere göre Aktif/Pasif bileşen seçim rehberleri.
* **Yüksek Hız (SPI):** DMA (Doğrudan Bellek Erişimi) entegrasyonu ve Thread-Safe (İş parçacığı güvenli) işlemler.
  * ↳ 📂 *Referans Proje:* [**ESP32 SPI & DMA Ustalık Rehberi**](https://github.com/askinkeles/Embedded-SPI-Guide)
* **Sensör Ağları (I2C):** Çoklu slave yönetimi, zaman aşımı (timeout) kurtarma ve lojik analizör ile hata ayıklama.
  * ↳ 📂 *Referans Proje:* [**Sağlam I2C Haberleşme Rehberi**](https://github.com/askinkeles/Embedded-I2C-Guide)

## 🧩 Elektronik Modüller & Endüstriyel Sensörler
* **Endüstriyel Seri Haberleşme (RS-485):** Gürültü bastırma, Ring Buffer yapıları ve Asenkron ayrıştırma teknikleri.
  * ↳ 📂 *Referans Proje:* [**Endüstriyel UART & RS-485 Rehberi**](https://github.com/askinkeles/Embedded-UART-Guide)
* **Otomotiv & Ağır Sanayi (CAN Bus):** Donanımsal filtreleme (Mask/Code), Tahkim (Arbitration) mantığı ve OBD-II diyagnostik.
  * ↳ 📂 *Referans Proje:* [**ESP32 TWAI (CAN Bus) El Kitabı**](https://github.com/askinkeles/Embedded-CANBus-Guide)
* **HMI Ekranlar:** Endüstriyel arayüzler için DWIN, Nextion ve OLED ekranların programlanması.

## 🛠️ Gömülü Mühendislik & Firmware Mimarisi
* **Profesyonel Firmware Mimarisi:** Modüler C++ tasarım kalıpları, HAL (Donanım Soyutlama Katmanı) ve Bağımlılık Ayrıştırma.
  * ↳ 📂 *Referans Proje:* [**ESP32 Pro Firmware Mimarisi**](https://github.com/askinkeles/ESP32-Pro-Firmware-Architecture)
* **RTOS Uygulamaları:** FreeRTOS görev yönetimi (Task management), süreçler arası iletişim (Kuyruklar, Semaforlar) ve Çekirdek Sabitleme.
* **PCB Tasarımı:** Çok katmanlı yönlendirme (routing), EMI/EMC azaltma teknikleri ve diferansiyel çift yönlendirme.

---
[← Ana Profile Dön](./README.tr.md)