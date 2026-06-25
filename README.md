# Titipku

> **Mau dari mana aja, kita beliin.**

Landing page untuk usaha jasa titip beli (jastip) — domestik & internasional.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## Overview

Titipku adalah landing page single-page untuk bisnis jasa titip beli. Dibangun dengan pendekatan modern, responsive, dan conversion-focused.

### Fitur Utama

- **Hero** — Headline + tagline + dual CTA (WhatsApp & Form)
- **Cara Kerja** — 4 langkah proses jastip
- **Layanan** — Kategori: Luar Negeri, Dalam Negeri, Custom Request
- **Katalog Populer** — 8 produk favorit customer
- **Kenapa Pilih Kami** — Trust points (Original, Transparan, Cepat)
- **Testimoni** — 3 review customer
- **Form Order** — Form titipan langsung di website
- **FAQ** — 5 pertanyaan umum dengan accordion
- **Footer** — Kontak, sosmed, navigasi

### Fitur Tambahan

- Floating WhatsApp button
- Scroll reveal animations
- Mobile responsive (mobile-first design)
- FAQ accordion interaktif
- Sticky navbar dengan blur backdrop

---

## Tech Stack

| Tech | Keterangan |
|------|-----------|
| HTML5 | Semantic markup |
| Tailwind CSS (CDN) | Utility-first styling |
| Plus Jakarta Sans | Google Fonts |
| Vanilla JS | Interaksi (FAQ toggle, mobile menu, scroll reveal) |

---

## Quick Start

1. Clone repo:
   ```bash
   git clone https://github.com/ganoolmovie5th-cell/titipku-superpowers-tasteskills.git
   cd titipku-superpowers-tasteskills
   ```

2. Buka `index.html` di browser — selesai! Tidak perlu build step.

---

## Deploy

Karena ini static HTML, bisa deploy ke:

- **GitHub Pages** — Settings > Pages > Source: main branch
- **Netlify** — Drag & drop folder, atau connect repo
- **Vercel** — Import repo, auto-deploy

---

## Kustomisasi

### Ganti Nomor WhatsApp

Cari semua `6281234567890` di `index.html` dan ganti dengan nomor WA kamu.

### Ganti Warna Brand

Edit bagian `tailwind.config` di `<head>`:
```javascript
brand: {
    500: '#f97316', // Warna utama (orange)
    // Ganti dengan warna brand kamu
}
```

### Ganti Konten

Semua teks ada di `index.html` — edit langsung sesuai kebutuhan bisnis kamu.

---

## Project Structure

```
titipku-superpowers-tasteskills/
├── index.html          # Landing page (single file, self-contained)
├── README.md           # Dokumentasi project
└── .kiro/
    └── steering/
        └── project.md  # Kiro steering rules
```

---

## Brand Identity

| Elemen | Value |
|--------|-------|
| Nama | Titipku |
| Tagline | "Mau dari mana aja, kita beliin." |
| Font | Plus Jakarta Sans |
| Warna Utama | Orange (#f97316) |
| Tone | Friendly, trustworthy, modern |
| Target | Semua segmen (Gen Z, keluarga, profesional) |

---

## License

MIT
