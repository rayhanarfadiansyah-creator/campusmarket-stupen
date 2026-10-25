# CampusMarket

**CampusMarket** adalah aplikasi web marketplace yang dikembangkan untuk mendukung aktivitas jual beli produk di lingkungan kampus. Proyek ini dikembangkan menggunakan PHP dan MySQL dengan antarmuka berbasis HTML dan CSS.

## 🔗 Link Proyek

- **Repository GitHub:** https://github.com/rayhanarfadiansyah-creator/campusmarket-stupen
- **Website Live:** https://campusmarket.freepage.cc/

## 🎯 Tujuan Proyek

CampusMarket bertujuan menyediakan platform marketplace sederhana yang memungkinkan pengguna mengelola produk dan melakukan aktivitas pemesanan melalui aplikasi web.

Proyek ini juga dikembangkan sebagai bagian dari penugasan Modul 8, dengan fokus pada pengembangan aplikasi web yang terhubung dengan database dan memiliki fungsionalitas interaktif.

## 🛠️ Teknologi yang Digunakan

- **PHP** — logika aplikasi dan pemrosesan request.
- **MySQL** — penyimpanan data aplikasi.
- **HTML** — struktur halaman web.
- **CSS** — styling dan tampilan antarmuka.
- **PDO** — koneksi database dan eksekusi query menggunakan PHP.
- **Git dan GitHub** — pengelolaan versi kode sumber.
- **InfinityFree** — hosting website.

## ✨ Fitur Aplikasi

Fitur yang tersedia dalam kode proyek meliputi:

- **Manajemen akun:** registrasi, login, dan logout.
- **Manajemen produk:** menambahkan, mengedit, menghapus, dan melihat produk.
- **Keranjang belanja:** menambahkan produk ke keranjang.
- **Checkout dan pemesanan:** memproses pesanan pengguna.
- **Pembayaran:** halaman pembayaran dan pengelolaan bukti pembayaran.
- **Manajemen pesanan:** melihat pesanan pengguna dan pesanan masuk.
- **Profil pengguna:** mengelola informasi profil.
- **Dashboard penjual:** mengelola produk dan aktivitas penjualan.

Fitur yang tersedia dan berjalan pada website live perlu diverifikasi kembali sebelum pengumpulan tugas.

## 🗂️ Struktur Proyek

```text
campusmarket-stupen/
├── assets/
│   └── css/
│       └── style.css
├── config/
│   └── database.php
├── index.php
├── register.php
├── login.php
├── logout.php
├── add_product.php
├── edit_product.php
├── delete_product.php
├── my_products.php
├── add_to_cart.php
├── cart.php
├── checkout.php
├── process_order.php
├── payment.php
├── my_orders.php
├── incoming_orders.php
├── seller_dashboard.php
├── profile.php
├── product_helpers.php
├── uploads/
└── .gitignore
```

## ⚙️ Persiapan dan Instalasi

### 1. Persyaratan

Siapkan lingkungan yang mendukung:

- PHP dengan ekstensi PDO MySQL.
- MySQL atau MariaDB.
- Web server seperti Apache.
- Browser modern.

### 2. Clone repository

```bash
git clone https://github.com/rayhanarfadiansyah-creator/campusmarket-stupen.git
cd campusmarket-stupen
```

### 3. Siapkan database

Buat database MySQL untuk CampusMarket, lalu siapkan tabel sesuai kebutuhan query pada aplikasi.

**Catatan:** Pastikan file SQL untuk struktur tabel dan data awal disertakan dalam repository atau disediakan sebagai bagian dari dokumentasi instalasi.

### 4. Konfigurasikan koneksi database

Sesuaikan `config/database.php` dengan kredensial database pada lingkungan yang digunakan.

Untuk pengembangan lokal, gunakan kredensial database lokal. Untuk hosting, gunakan hostname, nama database, username, dan password yang diberikan penyedia hosting.

Jangan mengunggah password atau kredensial rahasia ke repository publik.

### 5. Jalankan aplikasi

Jalankan aplikasi melalui web server lokal atau unggah file proyek ke direktori website pada hosting.

Buka `index.php` melalui alamat lokal atau URL website yang telah dikonfigurasikan.

## 🧪 Panduan Pengujian

Mentor dapat menguji aplikasi melalui langkah-langkah berikut:

1. Buka halaman utama CampusMarket.
2. Periksa daftar produk yang ditampilkan.
3. Coba registrasi dan login jika fitur akun tersedia.
4. Coba menambahkan atau mengelola produk.
5. Tambahkan produk ke keranjang.
6. Uji proses checkout dan pemesanan.
7. Periksa halaman pesanan serta dashboard penjual.
8. Uji validasi form menggunakan input kosong dan input yang tidak sesuai.

Fitur pencarian, filter, loading state, empty state, error state, dan toast notification juga perlu diuji apabila sudah diterapkan pada versi terbaru aplikasi.

## 🔒 Keamanan

- Kredensial database tidak boleh dipublikasikan.
- File konfigurasi lokal dan file rahasia harus dikecualikan melalui `.gitignore`.
- Input pengguna perlu divalidasi dan dibersihkan sesuai konteks.
- Query database sebaiknya menggunakan prepared statements.
- File pengujian koneksi database sebaiknya dihapus atau diamankan setelah selesai digunakan.

## 📝 Dokumentasi Pengembangan

Proyek dikembangkan dan disempurnakan secara bertahap dengan mempertahankan tampilan antarmuka yang telah dibuat sebelumnya.

Catatan pengembangan, prompt AI yang digunakan, serta perbaikan manual perlu dilengkapi berdasarkan proses pengerjaan yang benar-benar dilakukan.

## 👨‍💻 Pengembang

**Nama proyek:** CampusMarket  
**Repository:** `campusmarket-stupen`  
**Program:** Penugasan Modul 8 — Data Dinamis & Logika Aplikasi
