# Electronika-Engenering-Cv.sadewa-teknik : Agung dwi surya tahta
# Tema : Aplikasi IOT dasar dan penerapan
# Judul : Menghidupkan Lampu LED menggunakan HP koneksi WIFI Lokal

# Alat Bahan
Esp 32
Laptop/Komputer + Software Arduino IDE
Kabel micro USB
Resistor 220 - 330 ohm
Jumper wires male to female
Lampu Led 3mm
Project board/Bearboard

# Skema Wiring/Perkabelan
1) Hubungkan pin ESP32 menggunakan jumper wires male to female (Pastikan saat menghubungkan pin,pin harus sama seperti pada program dan pin juga bisa diganti dengan yang anda mau dan program hanya tinggal menyesuaikan saja pada pin yang anda pakai)
2)setelah itu pasang LED ke Project board,lalu hubungkan jumper wires male to female yang telah dihubungkan ke pin esp32 ke kaki (Anoda +) LED
3)Pasang Resistor Ke project board searah dengan kaki (Katoda -) LED,dan kaki resistor satunya masuk ke project board Ground (-)
4)Hubungkan Ground (GND) ESP32 menggunakan jumper wires male to female dan pasang ke project board (Ground -)
5)Hubungkan ESP32 dengan laptop/Komputer menggunakan Kabel Micro USB

# Langkah Kerja
• Anda harus mendownload Library Arduino IDE,Link sebagai berikut https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
• Masukkan link tersebut pada arduino IDE anda
  1)Masuk arduino Ide
  2)Klik File dan pilih preference
  3)Masukkan link tersebut pada "Additional Boards Manager urls" setelah itu klik "ok" pada pojok kanan bawah
  4)setelah itu anda masuk pada "Tools" pilih "board" lalu pilih "board manager" Lalu cari "ESP32" pilih "Esspresif System" Klik "Instal" dan tunggu sampai selesai terinstal ,pastikan sebelum instal Library sudah yang terbaru dengan melihat seri pada samping kiri tulisan instal
 4)setelah terinstal ,Anda harus menghubungkan Esp32 pada Laptop/Komputer menggunakan Kabel micro USB yang telah disiapkan
 5)Setelah dihubungkan anda harus masuk pada "Tools" pilih "Board" lalu pilih "ESP32" dan cari "ESP DEVKIT" lalu klik
 6)Pastikan port telah terhubung pada esp32 anda, dengan cara masuk ke "Tools" pilih "Port" dan sesuaikan pada port anda ,dan jika telah terhubung akan muncul tulisan "On Com" Pada pojok kanan bawah 
•Setelah langkah-langkah tersebut,anda tinggal memasukkan program yang telah saya siapkan untuk menghidupkan Lampu LED menggunakan HP koneksi WIFI lokal
• Setelah memasukkan Program, anda klik "Verify (√)" pada pojok kiri atas dan tunggu upload selesai dengan melihat loading pada pojok kanan bawah. Setelah selesai upload, anda klik "Uploading" dan tunggu hingga selesai upload hingga muncul tulisan "Done uploading" pada pojok kiri bawah.
• Setelah itu lihat pada "Serial monitor" yaitu pada pojok kanan atas lalu klik, setelah masuk pada serial monitor anda harus menyesuaikan Baud rate pada serial monitor dengan program anda.Dengan cara :
 1)cari "Serial.begin(115200)"
 2)masuk ke serial monitor
 3)lalu klik pada bagian bawah serial monitor dan pilih baud rate yang sesuai dengan program 
 4)Klik tombol "ENEABLE (EN)" pada esp32 dan lihat pada serial monitor
 5)Setelah muncul,cari "IP ADDRESS"
 6)Setelah itu,anda harus menghubungkan WIFI HP/KOMPUTER anda dengan Jaringan WIFI ESP32. (NAMA WIFI DAN PASSWORD BISA ANDA CUSTOM SESUAI YANG ANDA MAU).
 7)Lalu masuk ke crome "SEARCH" dengan memasukkan "IP ADDRESS,Contoh : 192.168.4.1 (Semua IP ADDRESS berbeda ,anda perlu memasukkan IP ADDRESS yang sesuai dari serial monitor anda)
• Setelah itu anda tinggal mengoprasikannya menggunakan Handphone/Komputer
# DENGAN CATATAN : JANGAN KELUAR DARI SERIAL MONITOR ANDA, KARENA KETIKA MENGOPRASIKAN LED AKAN MUNCUL TULISAN PADA SERIAL MONITOR.
