# 🧾 KasirCuan — Premium Business App

**KasirCuan** adalah aplikasi kasir (POS) desktop untuk UMKM — cocok buat kafe, resto, coffee shop, hingga usaha kuliner rumahan. Dibangun sebagai aplikasi native Windows (installer `.exe`/`.msi`) menggunakan **Tauri**, dengan frontend **HTML/CSS/JS**, backend **PHP**, dan tooling build via **npm**. Ringan, cepat, dan bisa jalan offline-first di komputer kasir.

---

## ✨ Fitur Utama

### 📊 Dashboard
Ringkasan bisnis dalam satu layar: omzet hari ini, total transaksi, status stok kritis, dan saldo kas bersih. Dilengkapi grafik penjualan 7 hari terakhir dan panel peringatan stok kritis secara real-time.

### 🛒 POS (Point of Sale)
Mode kasir untuk transaksi cepat, dengan riwayat transaksi lengkap (status, waktu, nominal, metode pembayaran cash, hingga info meja). Setiap transaksi bisa dilihat detail atau dibatalkan.

### 🧮 HPP Calculator
Kelola daftar produk beserta **Harga Pokok Penjualan (HPP)** dan harga jual secara otomatis — sistem menghitung margin keuntungan per produk. Mendukung mode perhitungan per **unit** maupun **batch** (produksi massal), scan barcode, dan import produk lewat CSV.

### 📦 Stock & Recipes (Manajemen Stok)
Pantau bahan baku secara detail: satuan, harga beli, stok tersedia, dan batas stok minimum. Ada tab khusus untuk **Stok Kritis** (bahan yang perlu direstok) dan **Stok Opname** (audit stok berkala), plus ringkasan total aset dan total jenis bahan.

### 💰 Cashflow
Catat pemasukan dan pengeluaran non-penjualan (biaya operasional, dll) dengan kategori kustom. Menampilkan total pemasukan, total pengeluaran, dan laba bersih secara otomatis, terintegrasi dengan data transaksi HPP & penjualan.

### 📈 Reports (Laporan Penjualan)
Analisis performa bisnis dengan filter **Harian / Mingguan / Bulanan** atau rentang tanggal custom. Menyajikan total penjualan, rata-rata per transaksi, dan breakdown penjualan per kategori produk. Bisa export ke Excel atau langsung print.

### 🗓️ Z-Report (Tutup Kasir)
Fitur rekonsiliasi kas harian ala kasir profesional — hitung uang tunai fisik, bandingkan dengan *expected cash* dari sistem, dan sistem otomatis menghitung selisihnya. Bisa langsung dicetak sebagai laporan tutup kasir.

### 👥 Tim & Kasir (Multi-user & Role Management)
Kelola anggota tim dengan dua role: **Owner** (akses penuh) dan **Kasir** (akses terbatas ke Dashboard & POS saja). Owner bisa menambah, mengedit, atau menghapus akun kasir langsung dari dashboard.

### 🔔 Notifikasi Real-time
Sistem notifikasi in-app untuk update transaksi baru, perubahan/penambahan anggota tim, hingga error sistem (misalnya gagal simpan data) — semua tercatat dengan timestamp.

### 🏢 Multi-Workspace
Mendukung banyak workspace dalam satu aplikasi, cocok untuk pemilik usaha dengan lebih dari satu cabang/brand.

### 🔐 Autentikasi
Login sederhana berbasis email & password dengan sistem role-based access — tampilan sidebar otomatis menyesuaikan hak akses (Owner Mode vs Kasir Mode).

---

## 🛠️ Tech Stack

| Layer | Teknologi |
|---|---|
| Desktop shell | [Tauri](https://tauri.app/) (Rust-based, ringan & aman) |
| Frontend | HTML, CSS, JavaScript |
| Backend / Logic | PHP |
| Build tooling | npm |
| Target platform | Windows (`.exe` / `.msi` installer) |

---

## 📷 Preview

Aplikasi mencakup halaman: Login, Dashboard, POS, HPP Calculator, Stock & Recipes, Cashflow, Reports, Z-Report, dan Tim & Kasir — semuanya dengan tampilan modern, tema hijau khas KasirCuan, dan dukungan dark mode.

---

## 🚀 Cocok untuk

- Kafe & coffee shop
- Restoran / warung makan
- Usaha kuliner rumahan / UMKM
- Bisnis dengan kebutuhan manajemen stok bahan baku & perhitungan HPP otomatis

---
JIKA BERMINAT BUSA HUBUNGI :
whatsapp : 087743323205
instagram : arulll.adami
