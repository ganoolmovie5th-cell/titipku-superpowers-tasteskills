# Titipku — Project Steering

## Project Context

Titipku adalah landing page untuk usaha jasa titip beli (jastip) yang melayani pembelian barang dari luar negeri dan dalam negeri. Website ini single-page, static HTML, dan conversion-focused.

## Design System

### Typography
- **Font**: Plus Jakarta Sans (Google Fonts)
- **Weights**: 400 (body), 500 (medium), 600 (semibold), 700 (bold), 800 (extrabold untuk heading)
- **Heading scale**: text-3xl sampai text-7xl, selalu `tracking-tight`

### Colors
- **Brand**: Orange palette (#f97316 sebagai primary/500)
- **Surface**: Warm stone tones (surface-50 sampai surface-900)
- **Accent**: Blue (internasional), Green (domestik), Purple (custom), Amber (rating)
- **Background**: Alternating white dan surface-50 antar section

### Spacing & Layout
- **Max width**: 6xl (1152px) untuk content container
- **Section padding**: py-20 md:py-28
- **Border radius**: rounded-2xl untuk cards, rounded-full untuk buttons/badges
- **Transitions**: duration-300 untuk hover effects

### Component Patterns
- **Cards**: bg-white, rounded-3xl, border border-surface-100, hover:shadow-xl
- **Buttons**: rounded-full, font-semibold, hover:scale-[1.02]
- **CTA primary**: bg-brand-500 (orange) atau bg-green-600 (WhatsApp)
- **CTA secondary**: bg-surface-900 (dark)
- **Section headers**: span (uppercase label) + h2 (extrabold title) + p (subtitle)

## Coding Conventions

### HTML
- Bahasa konten: **Bahasa Indonesia**
- Semantic HTML5 dengan section, nav, footer
- Tailwind CSS via CDN (no build step)
- Inline SVG icons (no external icon library)
- Mobile-first responsive design

### JavaScript
- Vanilla JS only (no framework)
- Minimal interactivity: mobile menu toggle, FAQ accordion, scroll reveal
- IntersectionObserver untuk scroll animations

## Channel & Contact

- **WhatsApp**: Primary order channel — semua link WA pakai format `https://wa.me/62XXXXXXXXXX`
- **Form**: Secondary order channel — form di section #order
- **Jam operasional**: 09:00 - 21:00 setiap hari

## Content Tone

- Friendly & approachable (bukan formal/corporate)
- Pakai "kamu" bukan "Anda"
- Campuran Bahasa Indonesia + sedikit English untuk istilah umum
- Trust-building: selalu highlight garansi, transparansi, dan kecepatan

## Do's and Don'ts

### Do
- Maintain single-file architecture (semua di index.html)
- Keep Tailwind via CDN for zero build setup
- Use emoji sparingly untuk katalog items
- Alternate section backgrounds (white/surface-50/dark)
- Keep mobile responsiveness as priority

### Don't
- Jangan tambah build tools (webpack, vite, dll) kecuali diminta
- Jangan pakai framework JS (React, Vue, dll)
- Jangan pakai external CSS file — semua via Tailwind utility classes
- Jangan ubah font dari Plus Jakarta Sans
- Jangan ubah color scheme tanpa izin (brand orange harus tetap)
