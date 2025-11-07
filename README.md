# uts-pemograman-web

# NAMA : KEYSIA NURHAYATI BR PANJAITAN
# NIM : 312410350
# KELAS : TI 24 A4
# Struktur Folder project

    project-pemesanan-buku/
    │
    ├── index.html
    ├── login.html
    ├── dashboard.html
    ├── stok.html
    ├── checkout.html
    ├── tracking.html
    │
    ├── css/
    │   ├── style.css
    │
    ├── js/
    │   ├── data.js   (isi data dummy katalog buku)
    │   ├── script.js (fungsi umum)
    │
    └── assets/
        ├── images/
        └── icons/


1. login.html

Input: email, password

Tombol Login

Jika salah → alert("Email/Password salah")

Tombol Lupa Password dan Daftar

Muncul dalam modal box (pop-up)

> JS file: login.js
Fitur: validasi form, manipulasi DOM, dan pop-up modal.


 2. dashboard.html
    
 Menu navigasi ke:
 
 Stok/Katalog
 
 Tracking Pengiriman
 
 Laporan Pemesanan
 
 History Transaksi
 
Menampilkan ucapan/greeting otomatis sesuai waktu lokal:
“Selamat Pagi”, “Selamat Siang”, “Selamat Sore”

> JS file: main.js
 
 3. stok.html

Menampilkan data dari data.js:

const dataKatalogBuku = [

  { id: 1, judul: "Pemrograman Web", stok: 10, harga: 75000 },
  { id: 2, judul: "Basis Data", stok: 5, harga: 85000 },
];

Bisa menambahkan data buku baru dengan manipulasi DOM (append row ke tabel).


 4. checkout.html

Menampilkan data pemesanan (buku yang dipilih)

Form data pemesan & pembayaran

Bisa ubah jumlah buku dan total harga otomatis.


 5. tracking.html

Input: Nomor Delivery Order

Tombol Cari

Menampilkan:

Nama Pemesan

Status Pengiriman (pakai progress bar atau warna)

Detail ekspedisi, tanggal kirim, jenis paket, total pembayaran







