# PABWE 2026 - Praktikum 2 (CSS & CSS Frameworks)

Repositori ini berisi solusi lengkap untuk **Praktikum 2 PABWE** (Pengembangan Aplikasi Berbasis Web), Institut Teknologi Del.

- **Nama**: Yogi Tri M
- **NIM**: 11S24023
- **Username / Akun Lab**: `ifs24023` (`yogitm`)
- **Program Studi**: S1 Informatika
- **Tema Proyek**: Perusahaan Jasa Artificial Intelligence (**AIsoISE Studio**)
- **Live Demo**: [https://ifs24023-p2.yogitrim.my.id](https://ifs24023-p2.yogitrim.my.id)
- **Auto-Deploy**: ✅ Active (Auto-synced with `dell-server`)

---

## 📁 Struktur Repositori

```text
ifs24023-pabwe-p2/
├── index.html          # Studi Kasus 3.1: Landing Page Perusahaan Jasa AI (Pure CSS + Modals + Dark Mode)
├── blog.html           # Studi Kasus 3.2.1: Daftar Blog AI (Bootstrap 5 + Icons + Dark Mode)
├── blog-detail.html    # Studi Kasus 3.2.2: Detail Blog AI (Bootstrap 5 + Icons + Dark Mode)
├── cv.html             # Studi Kasus 3.3: Curriculum Vitae Digital (Tailwind CSS 4 + Dark Mode)
├── bootstrap5.html     # Latihan 2.2: Eksperimen Bootstrap 5
├── tailwind4.html      # Latihan 2.3: Eksperimen Tailwind CSS 4
├── assets/
│   ├── css/
│   │   └── style.css   # Custom CSS & Design System (Variables, Modals, Light/Dark Theme, WCAG AA Contrast)
│   └── img/
│       ├── logo.png    # Aset Logo AIsoISE
│       └── yogi.png    # Foto Asli Yogi Tri M
└── README.md           # Dokumentasi repositori
```

---

## ♿ Standar Aksesibilitas Web (WCAG 2.1 AA & Axe-Core)
Semua halaman telah diaudit dan memenuhi kepatuhan aksesibilitas penuh:
1. **Button Name (`button-name`)**: Semua tombol interaktif (theme toggle, dropdown switcher, social share buttons, modal triggers/close, formulir komentar) memiliki nama yang jelas menggunakan teks semantik dan/atau `aria-label`.
2. **Heading Order (`heading-order`)**: Struktur heading bersarang secara logis dan berurutan (`h1` &rarr; `h2` &rarr; `h3` &rarr; `h4`) tanpa melompat level.
3. **HTML5 Landmarks (`region`)**: Seluruh konten halaman termuat rapi di dalam landmark HTML5 (`<header>`, `<nav>`, `<main>`, `<footer>`), termasuk modal popup dan elemen navigasi kembali ke atas.
4. **Color Contrast (`color-contrast`)**: Rasio kontras teks terhadap latar belakang diuji &ge; 4.5:1 untuk teks biasa dan &ge; 3:1 untuk teks besar pada mode terang (Light Mode) maupun mode gelap (Dark Mode).
