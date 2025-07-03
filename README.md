# 🚀 NRFBox Blujammer ESP32 - INSTALLATION GUIDE

Selamat datang di project **NRFBox Blujammer for ESP32**!  
Firmware ini dirancang khusus untuk melakukan scanning dan jamming perangkat **nRF24** via ESP32.  
🛠️ Sangat cocok untuk edukasi dan pengembangan alat RF.

---

## 📦 Download Firmware

🔽 Klik untuk langsung download file `.bin`:  
👉 [Download Firmware v1.0](https://github.com/namaprojekmu/nrfbox/releases/download/v1.0/nrfbox_blujammer_esp32.bin)

---

## 🧰 Alat dan Bahan

| Komponen        | Keterangan               |
|----------------|--------------------------|
| 🔌 ESP32 Board  | Minimal pakai DOIT DevKit V1 |
| 📱 Android/PC   | Untuk kontrol via Bluetooth/WiFi |
| 📡 Modul NRF24L01 | Wajib! Buat target RF-nya |
| 📟 OLED SSD1306 | (Opsional) Buat tampilan menu |

---

## 📲 Cara Install Firmware (Tanpa Arduino IDE)

1. **Download** dulu file `.bin` di atas ☝️  
2. Install software flash tool seperti [ESP32 Flash Download Tool](https://www.espressif.com/en/support/download/other-tools)  
3. Hubungkan ESP32 ke PC via kabel USB  
4. Buka tool, pilih port dan file `.bin`  
5. Setting offset ke `0x1000`  
6. Klik **Start**  
7. Tunggu hingga proses selesai ✅

---

## 🎮 Kontrol lewat Aplikasi

- Gunakan aplikasi **Serial Bluetooth Terminal** (Android)  
- Atau akses via Web UI kalau tersedia WiFi mode

---

## 📋 Menu yang Tersedia

- 🔍 **Scan Device**
- 🎯 **Select Target**
- 💣 **Start Jamming**
- 🧪 **Test Packet**
- ⚙️ **Settings & Mode**

---

## 📸 Tampilan OLED (opsional)

Kalau kamu pasang OLED SSD1306:
- Menu interaktif
- Animasi smooth 😍
- LED indikator per menu

---

## 🤖 Credits

> Dibuat oleh **ARYA25**  
> Project ini bersifat edukatif dan tidak untuk disalahgunakan.  
> Semua kode dan hardware diuji oleh teknisi berpengalaman.

---

## 🛑 Disclaimer

⚠️ **Gunakan hanya untuk edukasi dan riset.**  
Dilarang menggunakan alat ini untuk menyerang jaringan publik tanpa izin.

---

## ❤️ Support

⭐ Kasih bintang repo ini di GitHub kalau kamu suka!  
