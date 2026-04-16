<img width="1280" height="960" alt="WhatsApp Image 2026-04-16 at 3 15 56 PM" src="https://github.com/user-attachments/assets/bbcb73ae-33ad-4821-9a5f-dca1b176903d" />⚡ **Smart Electromagnetic Charging Highway (Prototype)**
 Overview

Project ini merupakan prototipe jalan raya pintar (smart highway) yang mampu melakukan pengisian daya kendaraan listrik secara nirkabel saat kendaraan bergerak. Sistem menggunakan konsep inductive charging berbasis elektromagnetik dengan kumparan (coil) yang ditanam di bawah permukaan jalan.

Fokus utama dari project ini adalah:

**Hardware**: Prototipe jalan dengan coil elektromagnetik untuk transfer energi
**Software (IoT)**: Monitoring kondisi baterai kendaraan secara real-time menggunakan Arduino IoT Cloud

**Concept**

Sistem bekerja dengan prinsip induksi elektromagnetik, di mana:

Kumparan primer (transmitter) ditanam di bawah jalan
Kumparan sekunder (receiver) berada di kendaraan
Ketika kendaraan melewati jalan, medan elektromagnetik menghasilkan arus listrik pada receiver
Energi tersebut digunakan untuk mengisi baterai kendaraan secara langsung

**Objectives**
Mengurangi ketergantungan pada charging station statis
Meningkatkan efisiensi penggunaan kendaraan listrik
Mengembangkan solusi energi berkelanjutan di sektor transportasi
Membuat prototipe sistem yang dapat diimplementasikan secara modular

**System Architecture**
1. Hardware
Kumparan elektromagnetik (transmitter coil)
Driver coil / rangkaian switching
Power supply
Receiver coil pada kendaraan (prototype)
Modul mikrokontroler (ESP8266 / ESP32)
Sensor monitoring baterai (tegangan & arus)

2. Software & IoT
Platform: Arduino IoT Cloud
Monitoring:
Tegangan baterai
Arus pengisian
Status charging
Dashboard berbasis web untuk visualisasi data real-time

**Technologies Used**
ESP8266
Inductive Power Transfer (IPT)
Sensor tegangan & arus
WiFi Communication
Arduino IoT Cloud

**How It Works**
Sistem coil pada jalan diaktifkan oleh sumber daya listrik
Kendaraan dengan receiver coil melewati jalur
Energi ditransfer secara nirkabel melalui medan elektromagnetik
Sensor membaca kondisi baterai
Data dikirim ke cloud melalui ESP
Data ditampilkan pada dashboard IoT secara real-time
📷 Prototype Illustration

