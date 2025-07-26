# Website Koperasi Simpan Pinjam
Website manajemen koperasi simpan pinjam berbasis **Framework Laravel**.

# Fitur
- Manajemen data anggota koperasi
- Pencatatan simpanan pokok, simpanan wajib, dan tabungan
- Pengajuan dan pelunasan pinjaman
- Riwayat transaksi dan laporan keuangan
- Sistem autentikasi untuk admin dan anggota

# Alat yang Dibutuhkan
Pastikan perangkat telah memiliki alat berikut:
- **PHP >= 8.1**
- **Composer** – Manajer dependensi Laravel  
  Unduh: [https://getcomposer.org/](https://getcomposer.org/)
- **XAMPP / Laragon** – Untuk server lokal dan database MySQL  
  Unduh: [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)
- **Visual Studio Code** – Editor kode sumber  
  Unduh: [https://code.visualstudio.com/](https://code.visualstudio.com/)
- **Google Chrome** – Browser yang direkomendasikan untuk pengujian
> Laravel CLI (opsional) akan mempermudah dalam menjalankan beberapa perintah Artisan.

---
# Cara Mengunduh / Clone & Langkah Instalasi
## Download ZIP
1. Klik tombol `Code` berwarna hijau di halaman repository GitHub.
2. Pilih **Download ZIP**.
3. Ekstrak file ke direktori lokal.
4. Buka terminal atau CMD, lalu masuk ke folder proyek hasil ekstraksi.
5. Jalankan perintah instalasi (lihat langkah di bawah).

## Clone via Git (direkomendasikan)
Jalankan perintah berikut di terminal untuk meng-clone repository:

```bash
git clone https://github.com/Kesyza15/koperasi-simpan-pinjam.git

composer install
atau 
composer update

cp .env.example .env

DB_DATABASE=nama_database
DB_USERNAME=root
DB_PASSWORD=

php artisan key:generate

php artisan migrate --seed

php artisan serve
