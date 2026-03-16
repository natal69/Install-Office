📦 Panduan Instalasi Microsoft Office (Metode ODT)

Dokumen ini berisi panduan lengkap untuk melakukan instalasi Microsoft Office menggunakan Office Deployment Tool (ODT). Metode ini lebih efisien karena memungkinkan Anda memilih aplikasi tertentu saja yang ingin diinstal.

📋 Prasyarat

Koneksi internet yang stabil.

Hak akses Administrator pada laptop/PC.

🛠️ Langkah-Langkah Instalasi

1. Konfigurasi Online

Buka browser dan akses Office Customization Tool.

Pilih Architecture yang sesuai (32-bit atau 64-bit).

Pada bagian Office Suites, pilih paket Office sesuai kebutuhan.

Di bagian Apps, pilih aplikasi yang ingin diinstal (contoh: Word, Excel, PowerPoint).

Pada bagian Language, pilih bahasa utama: English (United States).

Klik Ekspor, pilih Office Open XML Formats, lalu klik OK untuk mengunduh file configuration.xml.

2. Persiapan Deployment

Unduh Office Deployment Tool dari Situs Resmi Microsoft.

Buat folder baru di Disk C dengan nama Install Office.

Masukkan file configuration.xml dan file installer ODT yang sudah diunduh ke dalam folder tersebut.

Jalankan officedeploymenttool.exe dan ekstrak isinya ke folder yang sama.

3. Eksekusi via Command Prompt (CMD)

Buka CMD dengan opsi Run as Administrator.

Masuk ke folder instalasi dengan perintah:

cd C:\Install Office


Jalankan perintah untuk mengunduh file instalasi:

setup.exe /download configuration.xml


Tunggu hingga proses download selesai (kursor akan kembali muncul).

Jalankan perintah untuk memulai instalasi:

setup.exe /configure configuration.xml


🏁 Selesai

Tunggu hingga proses loading selesai. Jika sudah muncul notifikasi berhasil, Microsoft Office Anda sudah siap digunakan!

Dibuat oleh: Natal Zega
