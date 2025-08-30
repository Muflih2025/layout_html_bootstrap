
# Layout HTML Bootstrap

Proyek halaman web sederhana menggunakan Bootstrap 5 via CDN, berisi:
- Landing page (index.html) dengan tombol Login dan Register
- Halaman Login dan Register di folder `auth/`
- Dashboard di folder `page/` dengan sidebar, carousel, breadcrumbs, dan tabel

## Teknologi
- HTML5
- Bootstrap 5.3 CDN (CSS + JS)

## Cara Menjalankan
1. Buka file `app/index.html` langsung di browser
2. Atau gunakan ekstensi “Live Server” di VS Code pada file `app/index.html`

Koneksi internet diperlukan untuk memuat Bootstrap dan gambar dari CDN.

## Struktur Folder
```
layout_html_bootstrap/
├─ README.md
└─ app/
  ├─ index.html
  ├─ auth/
  │   ├─ Masuk.html
  │   └─ Register.html
  └─ page/
    └─ dashboard.html
```

## Navigasi
- Tombol Login di landing page menuju `auth/Masuk.html`
- Tombol Register di landing page dan login menuju `auth/Register.html`
- Tombol Login di halaman login menuju `page/dashboard.html`
- Tombol Logout di dashboard menuju `index.html`

## Fitur
- Navbar sticky di atas
- Carousel gambar + caption
- Breadcrumb
- Sidebar di kiri, konten utama di kanan
- Tabel (placeholder)

## Kustomisasi
- Warna navbar: `bg-dark`, `bg-primary`, `bg-light`
- Sidebar lebar: ubah grid Bootstrap
- Tinggi sidebar: `min-vh-25`, `min-vh-50`, dst
- Gambar carousel: atur lebar dengan `w-75`, `mx-auto`

## Catatan
- Bootstrap dipanggil lewat CDN pada `<head>`
- Tidak menggunakan npm atau node_modules
- Komentar HTML gunakan `<!-- ... -->`

## Lisensi
Untuk keperluan pembelajaran.