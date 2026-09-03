📚 Perpustakaan Sekolah
 
Sistem Informasi Manajemen Perpustakaan Sekolah — membantu admin mengelola data buku, anggota, peminjaman, dan pengembalian secara mudah & terorganisir 
 
🔗 Website: https://perpustakaansekolah.site.je/
 
 Wireframe https://raw.githubusercontent.com/liyanaafiah431-byte/UKK-PERPUSTAKAAN/refs/heads/main/flowchart.jpeg
 
 📚 Perpustakaan Sekolah
 
Sistem Informasi Manajemen Perpustakaan Sekolah — membantu admin mengelola data buku, anggota, peminjaman, dan pengembalian secara mudah & terorganisir 
 
🔗 Website: https://perpustakaansekolah.site.je/
 
 
 
📖 Tentang Proyek
 
Perpustakaan Sekolah adalah sistem berbasis web yang berfungsi untuk mengelola operasional perpustakaan sekolah secara digital. Sistem ini memudahkan pengelolaan koleksi buku, data anggota, serta transaksi peminjaman dan pengembalian buku.
 
"Membaca adalah jendela dunia"
 
 
 
✨ Fitur Utama
 
Fitur Keterangan 
📚 Data Buku Mengelola data buku yang tersedia di perpustakaan 
👥 Data Anggota Mengelola data siswa yang terdaftar sebagai anggota 
📖 Peminjaman & Pengembalian Mengelola proses peminjaman dan pengembalian buku 
📊 Statistik Menampilkan aktivitas peminjaman buku bulanan[__LINK_ICON] 
🔐 Login Admin Akses khusus untuk pengelolaan sistem 
 
 
 
🛠️ Teknologi yang Digunakan
 
- Bahasa Pemrograman: PHP
- Database: MySQL ( perpustakaan_sekolah ) 
- Server: Apache / Nginx
- Frontend: HTML5, CSS3, JavaScript 
 
 
 
🚀 Cara Instalasi
 
1. Persiapan Lingkungan
 
Pastikan sudah terpasang:
 
- PHP 7.4+
- MySQL / MariaDB
- Web Server (XAMPP, WAMP, atau sejenisnya)
 
2. Konfigurasi Database
 
Ubah file konfigurasi koneksi database:
 
php
  
// --- KONFIGURASI DATABASE ---
$host = "localhost";
$user = "root";
$pass = "";
$db   = "perpustakaan_sekolah";
 
 
3. Impor Database
 
- Buat database bernama  perpustakaan_sekolah 
- Impor file  perpustakaan_sekolah.sql  ke dalam database
 
4. Jalankan Aplikasi
 
- Letakkan file proyek di folder web server
- Akses melalui browser:  http://localhost/perpustakaan_sekolah/ 
 
 
 
📋 Panduan Penggunaan
 
Menjadi Anggota Perpustakaan
 
Siswa dapat mendaftar langsung melalui petugas perpustakaan di sekolah dengan membawa Kartu Tanda Siswa (KTS) yang aktif.
 
Aturan Peminjaman
 
- Batas waktu peminjaman: 7 hari kerja
- Perpanjangan: Dapat diperpanjang 1 kali jika buku tidak dipesan orang lain
- Keterlambatan: Dikenakan sanksi denda sesuai tata tertib yang berlaku
 
 
 
📁 Struktur Proyek
 
plaintext
  
perpustakaan_sekolah/
├── index.php              # Halaman utama
├── login.php              # Halaman login admin
├── config/
│   └── koneksi.php        # Konfigurasi database
├── buku/                  # Modul data buku
├── anggota/               # Modul data anggota
├── peminjaman/            # Modul peminjaman & pengembalian
├── assets/                # File CSS, JS, gambar
└── README.md              # Dokumentasi proyek
 
 
 
 
🤝 Kontribusi
 
Kontribusi sangat diterima! Silakan:
 
1. Fork repositori ini
2. Buat branch fitur:  git checkout -b fitur-baru 
3. Commit perubahan:  git commit -m 'Tambah fitur baru' 
4. Push ke branch:  git push origin fitur-baru 
5. Buat Pull Request
 
 
 
📄 Lisensi
 
Proyek ini dikembangkan untuk kebutuhan pendidikan dan perpustakaan sekolah — bebas digunakan dan dimodifikasi untuk tujuan pendidikan.
 
 
 
💡 Masukan atau saran? Silakan buka Issue atau hubungi kami melalui halaman kontak di website. Terima kasih telah menggunakan sistem ini! 📚✨
📖 Tentang Proyek
 
Perpustakaan Sekolah adalah sistem berbasis web yang berfungsi untuk mengelola operasional perpustakaan sekolah secara digital. Sistem ini memudahkan pengelolaan koleksi buku, data anggota, serta transaksi peminjaman dan pengembalian buku.
 
"Membaca adalah jendela dunia"
 
 
 
✨ Fitur Utama
 
Fitur Keterangan 
📚 Data Buku Mengelola data buku yang tersedia di perpustakaan 
👥 Data Anggota Mengelola data siswa yang terdaftar sebagai anggota 
📖 Peminjaman & Pengembalian Mengelola proses peminjaman dan pengembalian buku 
📊 Statistik Menampilkan aktivitas peminjaman buku bulanan[__LINK_ICON] 
🔐 Login Admin Akses khusus untuk pengelolaan sistem 
 
 
 
🛠️ Teknologi yang Digunakan
 
- Bahasa Pemrograman: PHP
- Database: MySQL ( perpustakaan_sekolah ) 
- Server: Apache / Nginx
- Frontend: HTML5, CSS3, JavaScript 
 
 
 
🚀 Cara Instalasi
 
1. Persiapan Lingkungan
 
Pastikan sudah terpasang:
 
- PHP 7.4+
- MySQL / MariaDB
- Web Server (XAMPP, WAMP, atau sejenisnya)
 
2. Konfigurasi Database
 
Ubah file konfigurasi koneksi database:
 
php
  
// --- KONFIGURASI DATABASE ---
$host = "localhost";
$user = "root";
$pass = "";
$db   = "perpustakaan_sekolah";
 
 
3. Impor Database
 
- Buat database bernama  perpustakaan_sekolah 
- Impor file  perpustakaan_sekolah.sql  ke dalam database
 
4. Jalankan Aplikasi
 
- Letakkan file proyek di folder web server
- Akses melalui browser:  http://localhost/perpustakaan_sekolah/ 
 
 
 
📋 Panduan Penggunaan
 
Menjadi Anggota Perpustakaan
 
Siswa dapat mendaftar langsung melalui petugas perpustakaan di sekolah dengan membawa Kartu Tanda Siswa (KTS) yang aktif.
 
Aturan Peminjaman
 
- Batas waktu peminjaman: 7 hari kerja
- Perpanjangan: Dapat diperpanjang 1 kali jika buku tidak dipesan orang lain
- Keterlambatan: Dikenakan sanksi denda sesuai tata tertib yang berlaku
 
 
 
📁 Struktur Proyek
 
plaintext
  
perpustakaan_sekolah/
├── index.php              # Halaman utama
├── login.php              # Halaman login admin
├── config/
│   └── koneksi.php        # Konfigurasi database
├── buku/                  # Modul data buku
├── anggota/               # Modul data anggota
├── peminjaman/            # Modul peminjaman & pengembalian
├── assets/                # File CSS, JS, gambar
└── README.md              # Dokumentasi proyek
 
 
 
 
🤝 Kontribusi
 
Kontribusi sangat diterima! Silakan:
 
1. Fork repositori ini
2. Buat branch fitur:  git checkout -b fitur-baru 
3. Commit perubahan:  git commit -m 'Tambah fitur baru' 
4. Push ke branch:  git push origin fitur-baru 
5. Buat Pull Request
 
 
 
📄 Lisensi
 
Proyek ini dikembangkan untuk kebutuhan pendidikan dan perpustakaan sekolah — bebas digunakan dan dimodifikasi untuk tujuan pendidikan.
 
 
 
💡 Masukan atau saran? Silakan buka Issue atau hubungi kami melalui halaman kontak di website. Terima kasih telah menggunakan sistem ini! 📚✨
