# Landing-Page-Kala

Landing page statis untuk brand kopi **Kala**, dibangun dengan HTML dan CSS murni (tanpa JavaScript) dan disesuaikan dengan struktur template **NaikPage**.

## Fitur Utama
- **Hero Full-Bleed:** Foto kebun kopi dataran tinggi dengan header transparan yang berubah solid saat di-scroll (`data-np-sticky`) serta tombol pemilih tema (**Terang**, **Gelap**, **Sistem**) tanpa JavaScript.
- **Daftar Kopi Mingguan (`#origins`):** 3 kartu kopi (*Gayo Pantan Musara*, *Flores Manggarai*, *Gunung Puntang Klasik*) lengkap dengan pop-up modal detail & resep awal menggunakan CSS `:target` tanpa JavaScript.
- **Panduan Rasio Seduh (`#brew-guide`):** Tab interaktif (*V60 Pour Over*, *Aeropress Standar*, *Espresso*) dengan indikator visual botol seduh menggunakan CSS `:has(:checked)` dan hook `data-np-tabs`.
- **Peta Lokasi Interaktif (`#tasting-room`):** Peta vektor Indonesia dengan pin lokasi **Jakarta** yang mengecilkan peta dan menampilkan kartu **Detail Informasi** (alamat, hari, jam cicip, kapasitas, telepon, dan email) tanpa JavaScript.
- **Footer:** Logo transparan, deskripsi singkat, 5 tautan media sosial dengan ikon SVG, kontak & jam buka, serta lengkungan penutup bertema kopi.
- **Responsif:** Teruji rapi di desktop (`1280×800`) maupun mobile (`360×780`) tanpa scroll ke samping.

## Struktur Folder
- `index.html` — Halaman utama dengan elemen langsung `<header>`, `<section>`, dan `<footer>` di dalam `<body>`
- `css/styles.css` — Styling responsif dengan variabel tema NaikPage (`--np-primary`, `--np-accent`, `--np-dark`, `--np-font-heading`, `--np-font-body`)
- `img/` — Aset gambar (`hero-coffee-plantation.jpg`, `indonesia-map.svg`, `kala-logo.png`)
- `template.json` — Konfigurasi `sampleBusiness` untuk NaikPage
