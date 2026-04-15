##Tugas 6 - Sistem Mikroprosesor (Sismik)##
Nama: Lula

NIM: H1H024064

Repositori ini berisi implementasi kode Arduino untuk menampilkan teks berjalan (scrolling text) pada LCD 16x2 menggunakan library Adafruit LiquidCrystal. Program ini menggunakan metode kustom pingPongScroll untuk menggerakkan teks dari kanan ke kiri dan kembali lagi.

📝 Deskripsi Proyek
Proyek ini bertujuan untuk mendemonstrasikan kontrol output visual pada modul LCD. Fitur utama dari kode ini adalah:

Efek Ping-Pong: Teks tidak hanya lewat satu arah, tapi memantul kembali setelah mencapai ujung.

Modular Function: Menggunakan fungsi renderFrame dan hapusBaris1 agar kode lebih terstruktur dan mudah dimodifikasi.

Custom Timing: Pengaturan delay yang halus untuk memastikan teks dapat dibaca dengan nyaman.

🛠️ Komponen & Library
Hardware: Arduino (Uno/Nano/Mega) & LCD 16x2 (I2C Module).

Library: Adafruit LiquidCrystal.

🚀 Konfigurasi Kode
Kamu bisa mengatur variabel berikut di dalam file .ino untuk mengubah tampilan:

Variabel	Fungsi	Nilai Default
quoteText	Teks yang akan ditampilkan	"Lulassssss, cintaa sismik"
SCROLL_DELAY	Kecepatan pergerakan teks (ms)	280
PAUSE_END	Jeda saat teks sampai di ujung (ms)	1200
💻 Cara Penggunaan
Clone repositori ini atau salin kode ke Arduino IDE.

Pastikan library Adafruit LiquidCrystal sudah terinstal melalui Library Manager.

Hubungkan LCD ke pin I2C Arduino (biasanya A4 untuk SDA dan A5 untuk SCL).

Upload kode dan buka layar LCD kamu.
