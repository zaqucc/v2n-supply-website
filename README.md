# V2N SUPPLY.CO — Storefront

Website toko online fashion berbasis HTML, CSS, dan JavaScript murni. Dibuat dengan pendekatan mobile-first dan tanpa framework agar ringan serta mudah dikembangkan.

## Struktur proyek

```
v2n-supply-website/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
```

## Fitur saat ini

- Landing page editorial dan responsive untuk desktop maupun mobile.
- Katalog produk berbasis data JavaScript.
- Filter kategori, pencarian, dan pengurutan harga/nama.
- Halaman detail produk dalam modal.
- Pilihan ukuran per produk.
- Keranjang dengan tambah/kurangi jumlah dan hapus item.
- Keranjang tersimpan di browser menggunakan localStorage.
- Checkout membentuk ringkasan pesanan melalui WhatsApp.
- FAQ, navigasi mobile, notifikasi, dan dukungan reduced motion.

## Menjalankan secara lokal

Buka `index.html` di browser atau jalankan menggunakan Live Server.

## Konfigurasi wajib sebelum menerima pesanan

1. Buka `script.js`.
2. Isi `STORE_CONFIG.whatsappNumber` dengan nomor WhatsApp toko format internasional tanpa tanda plus, contoh `62812xxxxxxxx`.
3. Ganti seluruh data produk contoh pada array `products` dengan data resmi V2N: nama, kategori, harga, warna, foto, deskripsi, dan ukuran.
4. Ganti URL foto eksternal dengan foto produk resmi yang sudah mendapat izin.
5. Periksa kembali seluruh harga, ukuran, dan informasi toko sebelum dipublikasikan.

## Data dan database

Saat ini katalog disimpan di array `products` dan keranjang disimpan secara lokal pada browser pengunjung. Belum ada database, autentikasi admin, sinkronisasi stok, atau pembayaran otomatis. Struktur ini sengaja dibuat agar integrasi API/database dapat ditambahkan pada tahap berikutnya.

## Catatan konten

Nama produk, harga, deskripsi, ukuran, dan foto yang tersedia saat ini adalah konten awal untuk pengembangan tampilan, bukan data katalog resmi V2N SUPPLY.CO. Jangan gunakan harga atau stok contoh sebagai informasi penjualan aktual.
