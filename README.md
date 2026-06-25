# LOVEE JENI Heels — Landing Page v2
> Rebuild final · Data real · Siap upload GitHub

---

## 📁 Struktur Folder (Upload PERSIS seperti ini)

```
lovee-landing/              ← nama folder bebas
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/
    ├── hero.webp
    ├── hero.jpg
    ├── product-cream.webp
    ├── product-cream.jpg
    ├── product-biscuit.webp
    ├── product-biscuit.jpg
    ├── product-black.webp
    ├── product-black.jpg
    ├── heel-detail.webp
    └── heel-detail.jpg
```

---

## 🚀 Cara Upload ke GitHub Pages (Step by Step)

### STEP 1 — Buat Repository

1. Login ke [github.com](https://github.com)
2. Klik **"+"** → **"New repository"**
3. Isi:
   - **Repository name:** `lovee-jeni` (atau apapun, ingat namanya)
   - Pilih **Public**
   - **Jangan** centang "Add README" (biarkan kosong)
4. Klik **"Create repository"**

---

### STEP 2 — Upload File

1. Di halaman repository yang baru dibuat, klik **"uploading an existing file"**
   *(atau klik "Add file" → "Upload files")*
2. Extract ZIP yang didownload
3. **Drag & drop** isi folder `lovee-landing/` ke halaman upload
   - Pastikan `index.html` ada di ROOT (bukan di dalam subfolder lagi)
   - Folder `css/`, `js/`, `assets/` juga langsung di root
4. Scroll ke bawah → isi commit message: `"Launch LOVEE landing page"`
5. Klik **"Commit changes"**

> ⚠️ **Penting:** Kalau upload lewat drag & drop tidak bisa menjaga struktur folder,
> upload manual: buat folder `css` dulu, upload `style.css` ke dalamnya, dst.

---

### STEP 3 — Aktifkan GitHub Pages

1. Di repository → klik tab **"Settings"**
2. Sidebar kiri → klik **"Pages"**
3. Di bagian **"Branch"**:
   - Pilih branch: **`main`**
   - Folder: **`/ (root)`**
4. Klik **"Save"**
5. **Tunggu 2–5 menit**

---

### STEP 4 — URL Landing Page

```
https://[username-github-kamu].github.io/lovee-jeni/
```

Contoh: jika username GitHub `wawa` dan repo `lovee-jeni`:
```
https://wawa.github.io/lovee-jeni/
```

Pasang URL ini sebagai **destination URL di Meta Ads**.

---

## ✅ Data yang Sudah Terpasang

| Item | Value |
|---|---|
| Harga Jual | Rp 105.000 |
| Harga Normal (coret) | Rp 135.000 |
| Meta Pixel ID | 1311289140538439 |
| WA Bisnis | 08161318281 |
| BCA | 6822029325 a.n. Muhammad Kurniawan SE |
| BSI | 7332718511 a.n. Musdalifah Lestari |
| GoPay | 0816-1318-281 a.n. Muhammad Kurniawan |
| Shopee | vee.ofc.store |
| Instagram | @loveeofficial.id |
| TikTok | @lovee.store |

---

## ⚙️ Tidak Perlu Ubah Apa-Apa

Semua data di atas sudah hardcoded di file. Langsung upload & live.

Satu-satunya yang perlu diubah setelah live:
- **OG URL** di `index.html` baris `<meta property="og:url" ...>` → ganti dengan URL GitHub Pages kamu

---

## 📣 Setup Meta Ads

### Pixel Events yang Sudah Terpasang:
| Event | Kapan Trigger |
|---|---|
| `PageView` | Setiap halaman dibuka |
| `Lead` | Klik "Pesan Sekarang" navbar |
| `InitiateCheckout` | Klik CTA hero |
| `Purchase` | Submit form → buka WhatsApp |

### Campaign Settings yang Disarankan:
- **Objective:** Conversions → Event: Purchase
- **Destination URL:** URL GitHub Pages kamu
- **Audience:** Wanita, 20–38 tahun, Indonesia
- **Minat:** Fashion wanita, Heels, Sepatu, Online Shopping, Shopee
- **Placement:** Mobile-first (Stories + Reels + Feed)

---

## ⚡ Performa

| Metrik | Value |
|---|---|
| Total gambar (WebP) | ~205 KB |
| Total gambar (JPG fallback) | ~310 KB |
| CSS | ~8 KB |
| JS | ~5 KB |
| **Estimasi Page Weight** | **< 350 KB** |
| Fonts | Google Fonts (lazy load, non-blocking) |
| Meta Pixel | Deferred 1.5s setelah load |
| JS | `defer` — tidak blocking render |
| LCP image | `fetchpriority="high"` + preloaded |

---

© 2025 LOVEE Official Store
