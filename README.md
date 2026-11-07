# V2N SUPPLY.CO — Storefront Demo

Website storefront fashion berbasis HTML, CSS, dan JavaScript murni. Proyek ini disiapkan sebagai demo portofolio dan fondasi pengembangan toko online V2N SUPPLY.CO.

## Struktur proyek

```
v2n-supply-website/
├── index.html
├── style.css
├── script.js
├── README.md
├── asset.zip
└── asset-extracted/
    ├── ASSET-MANIFEST.txt
    └── asset/
        └── ...foto produk hasil ekstraksi...
```

Struktur folder dipertahankan sesuai repositori saat ini.

## Fitur demo

- Landing page responsive untuk desktop dan perangkat mobile.
- Navigasi kategori yang mengarahkan ke katalog sekaligus menerapkan filter kategori.
- Katalog produk dengan pencarian, filter, dan pengurutan.
- Detail produk dengan pilihan ukuran sebelum ditambahkan ke keranjang.
- Wishlist dan keranjang yang tersimpan secara lokal di browser.
- Pengaturan jumlah dan penghapusan item keranjang.
- Ringkasan pesanan melalui WhatsApp setelah nomor toko dikonfigurasi.
- FAQ, navigasi mobile, notifikasi, dan dukungan reduced motion.

## Menjalankan

Buka `index.html` melalui browser atau jalankan menggunakan Live Server.

## Konfigurasi sebelum menerima pesanan

1. Isi `STORE_CONFIG.whatsappNumber` pada `script.js` dengan nomor WhatsApp toko format internasional tanpa tanda plus, misalnya `62812xxxxxxxx`.
2. Ganti seluruh data contoh pada array `products` dengan nama, kategori, harga, warna, foto, deskripsi, dan ukuran resmi.
3. Verifikasi setiap foto produk, harga, ukuran, dan informasi ketersediaan.
4. Pastikan kebijakan pengiriman, pembayaran, retur, dan kontak toko sudah benar.
5. Uji proses pemesanan di perangkat mobile dan desktop sebelum website dipublikasikan.

## Batasan versi saat ini

Ini masih storefront demo/front-end. Katalog produk berada di array JavaScript dan keranjang tersimpan di browser pengunjung melalui localStorage. Belum tersedia database, dashboard admin, autentikasi, sinkronisasi stok, manajemen pesanan, atau pembayaran otomatis.

Nomor WhatsApp masih kosong dan data produk yang ada merupakan data contoh. Karena itu, website belum boleh diperlakukan sebagai toko live untuk menerima pembayaran atau menjanjikan ketersediaan barang sampai data resmi dan konfigurasi toko dimasukkan.

## Teknologi

- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage
- Google Fonts dan Material Symbols
