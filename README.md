# uts-pemograman-web

# NAMA : KEYSIA NURHAYATI BR PANJAITAN
# NIM : 312410350
# KELAS : TI 24 A4
# matakuliah : UTS pemograman web1
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


# 1. login.html

Input: email, password

Tombol Login

Jika salah → alert("Email/Password salah")

Tombol Lupa Password dan Daftar

Muncul dalam modal box (pop-up)

> JS file: login.js
Fitur: validasi form, manipulasi DOM, dan pop-up modal.

<img width="1920" height="1200" alt="Screenshot 2025-11-07 160857" src="https://github.com/user-attachments/assets/46f79ff5-7e78-4998-b5ba-d7d01e7d8e09" />

# login.html
        <!DOCTYPE html>
        <html lang="id">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Login - Toko Buku Online</title>
            <link rel="stylesheet" href="css/style.css">
        </head>
        <body>
            <div class="login-container">
                <h2>Login</h2>
                <form id="loginForm">
                    <label for="email">Email</label>
                    <input type="email" id="email" placeholder="Masukkan email" required>
        
                    <label for="password">Password</label>
                    <input type="password" id="password" placeholder="Masukkan password" required>
        
                    <button type="submit">Login</button>
                </form>
        
                <div class="extra-links">
                    <button id="btnLupa">Lupa Password</button>
                    <button id="btnDaftar">Daftar</button>
                </div>
            </div>
        
            <!-- Modal Box -->
            <div id="modalBox" class="modal">
                <div class="modal-content">
                    <span id="closeModal">&times;</span>
                    <h3 id="modalTitle"></h3>
                    <p id="modalText"></p>
                </div>
            </div>

    <script src="js/script.js"></script>
    </body>
    </html>

 # 2. dashboard.html
    
 Menu navigasi ke:
 
 Stok/Katalog
 
 Tracking Pengiriman
 
 Laporan Pemesanan
 
 History Transaksi
 
Menampilkan ucapan/greeting otomatis sesuai waktu lokal:
“Selamat Pagi”, “Selamat Siang”, “Selamat Sore”

> JS file: main.js

<img width="1920" height="1200" alt="Screenshot 2025-11-07 161901" src="https://github.com/user-attachments/assets/3e829b10-cfb0-4f24-ad14-e05a3cdf1164" />


 # 3. stok.html

Menampilkan data dari data.js:

const dataKatalogBuku = [

  { id: 1, judul: "Pemrograman Web", stok: 10, harga: 75000 },
  { id: 2, judul: "Basis Data", stok: 5, harga: 85000 },
];

Bisa menambahkan data buku baru dengan manipulasi DOM (append row ke tabel).

<img width="1920" height="1200" alt="Screenshot 2025-11-07 161929" src="https://github.com/user-attachments/assets/9188b645-15f3-421d-b291-c7c7af7bedcd" />


 # 4. checkout.html

Menampilkan data pemesanan (buku yang dipilih)

Form data pemesan & pembayaran

Bisa ubah jumlah buku dan total harga otomatis.

<img width="1920" height="1200" alt="Screenshot 2025-11-07 161833" src="https://github.com/user-attachments/assets/dd04c42b-1f3b-4d3c-a8a1-96c8108b9f50" />


 # 5. tracking.html

Input: Nomor Delivery Order

Tombol Cari

Menampilkan:

Nama Pemesan

Status Pengiriman (pakai progress bar atau warna)

Detail ekspedisi, tanggal kirim, jenis paket, total pembayaran

<img width="1920" height="1200" alt="Screenshot 2025-11-07 161952" src="https://github.com/user-attachments/assets/c47b0980-e70c-4d30-ab7e-8474866fb101" />








