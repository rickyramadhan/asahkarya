# Xpert Institute — Frontend v1

Frontend lengkap 24 layar aplikasi + panduan presentasi.
Stack: HTML, CSS, JavaScript vanilla. Tidak perlu npm install atau build.

## Cara menjalankan
1. Ekstrak ZIP.
2. Buka folder Xpert-Institute-Frontend di VS Code.
3. Jalankan index.html dengan ekstensi Live Server.

Alternatif XAMPP:
- Salin folder ke C:/xampp/htdocs/xpert-institute
- Aktifkan Apache.
- Buka http://localhost/xpert-institute/

Alternatif Python (dari folder hasil ekstrak):
    python -m http.server 8000
Lalu buka http://localhost:8000

## File yang diedit
- index.html: kerangka HTML, judul awal, pemuatan CSS/JS.
- style.css: seluruh tampilan, warna, tipografi, responsive.
- app.js: data kelas, template 24 layar, routing, dan interaksi.
- assets/logo.png: logo asli yang diberikan.
- assets/hero.jpg: gambar hero ilustrasi hasil generasi.

## Petunjuk edit
- Data kelas: array courses pada bagian awal app.js.
- Daftar layar: array screens.
- Halaman: fungsi home(), catalog(), detail(), dashboard(), dst.
- Navigasi: hash route, contoh #/catalog dan #/dashboard.
- Panduan presentasi: #/presentation.
- Warna global: variabel CSS di :root pada style.css.
- Font: DM Sans dan Manrope melalui Google Fonts, dengan fallback sans-serif.
- Gunakan Format Document di VS Code untuk merapikan kode sebelum mengedit.

## Penyimpanan demo
Progres, catatan, tautan tugas, dan preferensi menggunakan localStorage browser.
Untuk reset: buka DevTools > Application > Local Storage, lalu hapus key berawalan xpert-.
Interaksi lain hanya berlaku pada sesi demo.

## Batas frontend
Belum ada backend, autentikasi, pembayaran aktif, email, streaming video, atau AI sungguhan.
Nama peserta/mentor, kelas, harga, statistik, sertifikat, dan perusahaan adalah ilustrasi.
Jawaban assistant menggunakan skenario terprogram.
Setiap halaman dapat dikembangkan menjadi template atau komponen framework sesuai kebutuhan.

## Deploy mandiri
Upload index.html, style.css, app.js, dan folder assets ke direktori web server yang sama.
Routing menggunakan hash sehingga tidak memerlukan aturan rewrite khusus.
