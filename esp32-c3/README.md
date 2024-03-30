# ESP32 C3

## Overview
ESP32-C3 Supermini adalah versi miniaturisasi dari modul ESP32-C3 yang populer, yang dirancang untuk aplikasi IoT (Internet of Things) dengan kebutuhan ruang yang sangat terbatas. ESP32-C3 merupakan chip yang dikembangkan oleh Espressif Systems, menawarkan konektivitas Wi-Fi dan Bluetooth Low Energy (BLE) dengan harga yang ekonomis dan konsumsi daya yang rendah. Versi Supermini ini dirancang untuk meminimalisir ukuran fisik modul sambil tetap menyediakan fitur inti dari ESP32-C3.

#### Front View
![Front](https://europe1.discourse-cdn.com/arduino/original/4X/9/2/f/92f1e8e2fcc888726ff7838dad725dd94f43438d.jpeg)

#### Back View
![Back](https://europe1.discourse-cdn.com/arduino/original/4X/b/4/1/b41cb5d47221f72dce90d2227369a7aa359fa2d0.jpeg)

Berikut adalah penjelasan singkat tentang pinout ESP32-C3 Supermini:

- GPIO (General Purpose Input/Output): ESP32-C3 Supermini menyediakan sejumlah pin GPIO yang dapat diprogram untuk berbagai fungsi seperti input digital, output digital, PWM, I2C, SPI, dan lain-lain. Pin-pin ini bisa digunakan untuk menghubungkan berbagai sensor dan aktuator ke modul.

- Power Pins (VCC, GND): Pin ini digunakan untuk menyuplai daya ke modul. VCC untuk tegangan positif dan GND untuk ground.

- UART Pins (TXD, RXD): Pin ini digunakan untuk komunikasi serial UART, memungkinkan ESP32-C3 Supermini untuk berkomunikasi dengan mikrokontroler atau komputer lain.

- SPI, I2C, ADC Pins: Untuk komunikasi dengan perangkat atau sensor yang menggunakan protokol SPI atau I2C, serta pin ADC untuk membaca nilai analog.

- Reset dan Boot Pins: Pin reset digunakan untuk mereset modul, sedangkan pin boot digunakan untuk mode pemrograman.

Desain pinout ESP32-C3 Supermini mungkin berbeda-beda tergantung pada produsen atau versi spesifik dari modul. Oleh karena itu, selalu penting untuk merujuk pada datasheet modul yang spesifik untuk informasi pinout yang akurat dan detail tentang konfigurasi pin tambahan. Dengan ukurannya yang sangat kecil, ESP32-C3 Supermini sangat cocok untuk proyek-proyek IoT yang memerlukan konektivitas dalam paket yang sangat kompak.



## Instalasi Tools Pemrograman ESP32 C3
### Linux
linux part
### MacOSX
macosx part
### Windows
windows part


## Resources
- https://docs.micropython.org/en/latest/esp32/tutorial/intro.html
- https://micropython.org/download/ESP32_GENERIC_C3/
- https://pypi.org/project/esptool/
- https://labs.arduino.cc/en/labs/micropython