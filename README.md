1. Pendahuluan
Website ini adalah aplikasi toko online yang dibangun menggunakan Laravel dan Livewire dengan integrasi Midtrans untuk sistem pembayaran. Website ini dirancang untuk memfasilitasi proses pembelian dan checkout secara efisien, namun untuk bagian antar muka pengguna masih sangat sederhana
dikarenakan website ini bertujuan untuk pembelajaran dan latihan semata. 

3. Bagian Admin
2.1. Dashboard
Fitur Utama: Menyediakan overview dari aktivitas terkini, seperti jumlah pesanan, produk terbaru, dan statistik penjualan.
Komponen:
Statistik: Grafis dan chart untuk menampilkan data penjualan dan aktivitas pengguna.
Notifikasi: Sistem pemberitahuan untuk peringatan dan update penting.

![image](https://github.com/user-attachments/assets/7b645f3e-cdda-4d2e-8459-d1ad7c4374cc)


2.2. Manajemen Produk
Fitur Utama: Menambah, mengedit, dan menghapus produk dari toko.
Komponen:
Formulir Produk: Input untuk nama produk, deskripsi, harga, kategori, dan gambar.
Daftar Produk: Tabel untuk menampilkan semua produk yang ada di toko.

![image](https://github.com/user-attachments/assets/84a2da1e-6c16-483f-9e89-3bed9c3e094a)


2.3. Manajemen Kategori
Fitur Utama: Mengatur kategori produk untuk memudahkan pencarian dan pengelompokan.
Komponen:
Formulir Kategori: Input untuk nama kategori dan deskripsi.
Daftar Kategori: Tabel untuk menampilkan kategori yang ada.

2.4. Manajemen Pengguna
Fitur Utama: Mengelola akun pengguna dan hak akses.
Komponen:
Daftar Pengguna: Tabel untuk menampilkan informasi pengguna.
Detail Pengguna: Formulir untuk melihat dan mengedit informasi pengguna.

2.5. Manajemen Pesanan
Fitur Utama: Melihat dan mengelola pesanan yang masuk.
Komponen:
Daftar Pesanan: Tabel untuk menampilkan status pesanan, informasi pelanggan, dan total harga.
Detail Pesanan: Formulir untuk melihat rincian pesanan dan status pengiriman.

![image](https://github.com/user-attachments/assets/ce147e65-2dd3-4cb2-8336-6eefb6458447)

![image](https://github.com/user-attachments/assets/9054a8e0-399d-4fb0-a755-977cf65e6a3a)




4. Komponen dan Paket
3.1. Laravel
Versi: Versi yang digunakan dalam proyek ini adalah Laravel (sebutkan versi spesifik jika ada).
Fungsi: Framework PHP utama yang digunakan untuk pengembangan aplikasi web.

3.2. Livewire
Fungsi: Komponen interaktif dalam Laravel yang memungkinkan pembuatan UI yang dinamis tanpa menulis JavaScript secara langsung.
Instalasi: composer require livewire/livewire

3.3. Midtrans
Fungsi: Sistem pembayaran online yang terintegrasi untuk memproses transaksi.
Paket: midtrans/midtrans-php
Konfigurasi:
MIDTRANS_CLIENTKEY dan MIDTRANS_SERVERKEY untuk autentikasi.
MIDTRANS_IS_PRODUCTION, MIDTRANS_IS_SANITIZED, dan MIDTRANS_IS_3DS untuk pengaturan mode dan keamanan transaksi.

3.4. Paket Lainnya
Fruitcake/laravel-cors: Dihapus karena sudah usang.
Swiftmailer/swiftmailer: Dihapus karena sudah usang, diganti dengan symfony/mailer.
Fzaninotto/faker: Dihapus karena sudah usang.
PHPUnit/php-token-stream: Dihapus karena sudah usang.

3.5. Dependencies dan Configuration
Composer: Digunakan untuk mengelola dependensi PHP.
Artisan: Tool command-line Laravel untuk berbagai tugas pengelolaan aplikasi.
.env: File konfigurasi lingkungan untuk mengatur variabel seperti database dan kunci API.

6. Pengaturan Lingkungan
Database: MySQL dengan konfigurasi di .env.
Cache dan Session: Disimpan dalam file untuk pengaturan lokal.
Mail: Konfigurasi SMTP untuk pengiriman email menggunakan Mailtrap (untuk pengembangan).

8. Pengembangan dan Deployment
Git: Versi kontrol untuk mengelola kode sumber.
GitHub: Platform untuk hosting repository dan kolaborasi tim.

10. Penutup
Website ini dirancang untuk memberikan pengalaman pengguna yang optimal dengan fitur-fitur yang mendukung administrasi toko, manajemen produk, dan pemrosesan pembayaran. Pastikan untuk memperbarui kunci API dan konfigurasi sesuai kebutuhan saat memindahkan aplikasi ke lingkungan produksi.
