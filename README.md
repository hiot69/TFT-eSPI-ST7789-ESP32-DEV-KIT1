# 📌 TFT_eSPI untuk ESP32 Dev Kit

Panduan ini digunakan untuk menyesuaikan library **TFT_eSPI** agar kompatibel dengan modul **ESP32 Dev Kit** yang menggunakan layar TFT ST7789.


## ⚠️ Peringatan
Sebelum memulai, **backup file asli** pada folder library TFT_eSPI agar mudah dikembalikan jika terjadi masalah.


## 📂 Langkah Instalasi

1. **Buat Folder**
     ...\Documents\Arduino\libraries\TFT_eSPI_Setups

2. **Copy File Custom Setup**
   - Salin file **Setup24_ST7789_ESP32_DEV_KIT1.h** ke folder:
     ...\Documents\Arduino\libraries\TFT_eSPI_Setups

3. **Copy File**
   - Salin file **User_Setup_Select.h** ke folder:
     ...\Documents\Arduino\libraries\TFT_eSPI

4. **Konfigurasi Pin GPIO**
   Gunakan pin berikut untuk koneksi layar TFT:
   - SCLK = GPIO 18
   - MOSI/SDA = GPIO 23
   - RST = GPIO 4
   - DC = GPIO 2

5. **Uji Coba**
- Setelah instalasi selesai, buka contoh sketch:
  File → Examples → TFT_eSPI → random_painter
- Upload ke board ESP32 Dev Kit untuk memastikan semuanya berjalan.

Salam,
H IoT


## 📝 Lisensi
Dokumen ini bebas digunakan untuk tujuan belajar dan pengembangan.
