# pemweb-kel-13
Michelle Evelyn Dyvani (160), Lutfia Nur Sabrina (175), Novia Farah Harwati (176), Gratia Novelin Tamba (178)

Air Biru - Aplikasi Pemesanan Air Galon
Proyek ini dibuat untuk memenuhi tugas Praktikum Mandiri 2 mata kuliah Pemrograman Web.
Berisi 4 halaman HTML yang dibuat berdasarkan studi kasus dari Bab 5 modul.

Struktur Folder
air-biru/
├── index.html
├── about.html
├── order.html
├── report.html
└── README.md

Penjelasan Halaman:

1. index.html (Halaman Beranda)
Halaman utama yang pertama kali dilihat pengunjung saat membuka situs Air Biru.
- Isi halaman:
Header navigasi menuju semua halaman
Hero section berisi tagline dan tombol menuju halaman pemesanan
Daftar fitur unggulan aplikasi (berbasis lokasi, lacak pengiriman, reminder minum, langganan otomatis)
Kotak reminder pengingat minum air harian
Tabel riwayat pesanan terakhir
- Modifikasi dari modul:
Awalnya hanya mengikuti contoh struktur dasar dari Bab 5 modul (header, nav, section, footer)
Ditambahkan tabel riwayat pesanan menggunakan tag <table> sesuai materi Bab 1.3
Ditambahkan section reminder minum air sesuai fitur utama aplikasi Air Biru
Navigasi menggunakan <ul> dan <li> sesuai contoh di modul


2. about.html (Halaman Profil)
Halaman yang menjelaskan latar belakang usaha Air Biru kepada pengunjung.
- Isi halaman:
Hero section dengan deskripsi singkat dan statistik (12+ depot, 5K+ pelanggan)
Profil singkat usaha beserta informasi detail (tahun berdiri, wilayah, jam operasional, rating)
Visi dan misi dalam bentuk daftar terurut
Pengenalan tim layanan (Tim Kurir, Admin Depot, Customer Service)
- Modifikasi dari modul:
Awalnya hanya mengikuti contoh about.html sederhana dari Bab 5 modul dengan <section>, <h2>, dan <p>
Ditambahkan tabel statistik usaha menggunakan atribut bgcolor dan cellpadding
Misi ditampilkan menggunakan <ol> sesuai materi daftar berurutan di Bab 1.3
Ditambahkan section tim layanan yang tidak ada di contoh modul

3. order.html (Halaman Pemesanan)
Halaman utama untuk melakukan pemesanan air galon.
- Isi halaman:
Hero section dengan judul halaman pemesanan
Kartu pilihan produk (Galon 19 Liter dan Galon 5 Liter) beserta harga
Form pemesanan lengkap dengan validasi HTML5
Tabel estimasi waktu pengiriman
- Modifikasi dari modul:
Awalnya hanya mengikuti contoh form dasar dari Bab 2.1 modul (<form>, <input>, <button>)
Ditambahkan type="tel", type="number", type="date" sesuai materi input HTML5 Bab 2.1.2
Ditambahkan atribut required pada field wajib sesuai materi validasi form Bab 2.1.3
Ditambahkan <select> untuk pilihan produk dan jadwal pengiriman
Ditambahkan <textarea> untuk catatan tambahan sesuai contoh form di modul
Pilihan produk galon ditampilkan menggunakan layout tabel dua kolom


4. report.html (Halaman Laporan Masalah)
Halaman untuk pelanggan menyampaikan keluhan atau laporan terkait layanan Air Biru.
- Isi halaman:
Hero section dengan penjelasan tujuan halaman
Daftar kategori masalah (keterlambatan, kualitas air, kondisi galon, salah pesanan, pelayanan kurir, lainnya)
Form laporan dengan upload foto menggunakan type="file"
Tabel riwayat laporan yang pernah dikirim
- Modifikasi dari modul:
Awalnya hanya mengikuti contoh contact.html dari Bab 5 modul
Ditambahkan <input type="file"> sesuai materi file upload Bab 2.1.4 modul
Ditambahkan <select> untuk kategori masalah
Ditambahkan tabel riwayat laporan menggunakan <table>, <tr>, <td> sesuai Bab 1.3
Kategori masalah ditampilkan sebagai tabel horizontal satu baris

Teknologi yang Digunakan
- HTML5
Tidak menggunakan CSS eksternal — semua tampilan menggunakan atribut HTML bawaan seperti bgcolor, cellpadding, cellspacing, align, width, dan tag <font>
- Cara Menjalankan:
Download semua file ke dalam satu folder
Buka index.html menggunakan browser (Chrome / Firefox / Edge)
Navigasi antar halaman menggunakan menu di bagian atas
- Validasi
Seluruh halaman telah divalidasi menggunakan W3C Markup Validation Service dan tidak ditemukan error.

© 2026 Air Biru. Dibuat untuk tugas mata kuliah Pemrograman Web.

&copy; 2026 Air Biru. Dibuat untuk tugas mata kuliah Pemrograman Web.
