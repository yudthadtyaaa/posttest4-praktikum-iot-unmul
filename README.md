## Judul Studi Kasus:
Implementasi IoT untuk Kontrol LED dan Monitoring Suhu & Kelembapan dengan Telegram Bot pada ESP8266

## Group Members:
- Sancto Metano Crozart (2109106112)
- Muhammad Akbar Fahrezi (2109106117)
- M. Yudith Aryanta Aditya (2109106122)

## Deskripsi:
Proyek ini bertujuan untuk mengembangkan sebuah sistem IoT yang memungkinkan pengguna untuk mengontrol empat buah LED dan memantau suhu serta kelembapan lingkungan melalui bot Telegram. 
Dengan menggunakan modul WiFi ESP8266, proyek ini menghubungkan perangkat keras dengan internet sehingga dapat diakses dari mana saja selama pengguna terhubung ke internet. 
Tiga dari empat LED dapat dikontrol secara individu oleh anggota kelompok tertentu melalui chat ID mereka di Telegram, sedangkan satu LED lainnya dapat dikontrol oleh semua anggota kelompok.

## Cara Kerja Alat
1. ESP8266 terhubung ke jaringan WiFi.
2. Bot Telegram diatur untuk menerima perintah dari pengguna.
3. Pengguna mengirim perintah melalui chat Telegram untuk melakukan kontrol LED atau meminta data suhu dan kelembapan.
4. Berdasarkan perintah yang diterima, ESP8266 akan mengaktifkan/deaktifkan LED yang sesuai atau membaca data dari sensor DHT11 dan mengirimkannya kembali ke pengguna melalui Telegram.

## Pembagian Tugas per Individu:
- Sancto Metano Crozart (2109106112):
  - Membuat grup telegram dan list command-nya.
  - Dan menyiapkan Bot Telegram.
- Muhammad Akbar Fahrezi (2109106117):
- - Merangkai rangkaian hardware NodeMCU .
  - Menyiapkan Bot Telegram.
- M. Yudith Aryanta Aditya (2109106122):
  - Membuat Script Code Arduino.
  - Melakukan pengujian keseluruhan script.
  - Membuat Skematik Design

## Komponen yang Digunakan:
1. ESP8266 (NodeMCU atau Wemos D1 Mini): Digunakan sebagai mikrokontroler utama yang terhubung ke jaringan WiFi dan menjalankan logika kontrol serta komunikasi dengan bot Telegram.
2. LED (4 buah): Diindikasikan sebagai output yang dikontrol berdasarkan perintah dari Telegram. Tiga LED untuk kontrol individu berdasarkan `chat_id` dan satu LED yang bisa dikontrol oleh semua anggota.
3. Resistor 220 Ohm (4 buah): Digunakan untuk mengurangi arus yang mengalir ke LED dan mencegah kerusakan.
4. Sensor DHT11: Digunakan untuk mengukur suhu dan kelembapan lingkungan.
5. Breadboard dan Jumper Wires: Untuk membuat rangkaian tanpa perlu solder.
6. Kabel Data
7. Aplikasi Telegram
8. Bot Telegram (Bot Father)


## Board Skematic:


# 1. Design Skematic
![posttest4_skematik_design](https://github.com/yudthadtyaaa/posttest3-praktikum-iot-unmul/assets/95072812/c5f2fc1d-346b-4b15-88f6-3805687cdd8d)

# 2. Design Real
![posttest4_skematik_real](https://github.com/yudthadtyaaa/posttest3-praktikum-iot-unmul/assets/95072812/5779773b-f9d9-4ed7-a027-8fe7711328f6)
