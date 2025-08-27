# Layout HTML Bootstrap

Proyek halaman sederhana menggunakan Bootstrap 5 via CDN (tanpa npm) yang berisi:
- Navbar sticky di atas
- Carousel gambar + caption
- Breadcrumb
- Layout 2 kolom: Sidebar di kiri, konten utama di kanan
- Tabel 5 kolom 10 baris (placeholder)
- Form isian siswa (placeholder)

## Teknologi
- HTML5
- Bootstrap 5.3 CDN (CSS + JS)

## Cara Menjalankan
1. Buka file `Index.html` langsung di browser, atau
2. VS Code: install ekstensi “Live Server” → klik kanan `Index.html` → Open with Live Server.

Koneksi internet diperlukan untuk memuat Bootstrap dan gambar dari CDN.

## Struktur
```
layout_html_bootstrap/
├─ Index.html
└─ README.md
```

## Kustomisasi Cepat
- Warna navbar:
  - Gelap: `bg-dark navbar-dark`
  - Biru: `bg-primary navbar-dark`
  - Terang: `bg-light navbar-light`
- Navbar tetap di atas: tambahkan `sticky-top` pada `<nav>`.
- Sidebar lebih sempit: ubah grid sidebar/main, misal:
  - Sidebar: `col-lg-2` → `col-lg-1`
  - Konten: `col-lg-10` → `col-lg-11`
- Tinggi sidebar relatif layar: `min-vh-25 | 50 | 75 | 100`
- Gambar carousel:
  - Ukuran konsisten: atur `w-75` atau `w-50` pada `<img>` dan `mx-auto` agar di tengah.
  - Caption di tengah: tambahkan `text-center` pada `.carousel-caption`.

## Catatan
- Proyek ini tidak menggunakan `node_modules` atau `npm`. Bootstrap dipanggil lewat CDN pada `<head>`.
- Hindari komentar `// ...` di HTML. Gunakan `<!-- ... -->`.

## Lisensi
Untuk keperluan pembelajaran.