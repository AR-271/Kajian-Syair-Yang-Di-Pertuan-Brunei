# Shaer Yang Di-Pertuan — Laman Interaktif
Analisis Unsur Diplomasi Hubungan Brunei–British dalam Manuskrip Syair Yang Di-Pertuan
Auza'ie Rusydi bin Suhaili · 25MR1408 · Pusat Kajian Manuskrip Islam, UNISSA

## Dua versi
| Fail | Guna untuk |
|---|---|
| `index.html` | Laman awam — desktop, tablet & telefon (responsif automatik) |
| `kiosk.html` | Skrin sentuh / paparan pameran — satu bahagian satu skrin, butang besar, kembali sendiri ke laman utama selepas 2 minit tiada sentuhan |

Kedua-duanya berkongsi folder `assets/` yang sama.

## Muat naik ke GitHub Pages
1. Buat repositori baharu (cth: `syair-yang-dipertuan`).
2. Muat naik SEMUA fail — kekalkan struktur (`index.html`, `kiosk.html`, folder `assets/`).
3. Settings → Pages → Branch: `main` / `(root)` → Save.
4. Laman: `https://<nama-anda>.github.io/<repo>/`
   Kiosk: `https://<nama-anda>.github.io/<repo>/kiosk.html`

## Tetapan kiosk
Buka `kiosk.html`, cari `IDLE_MS` — 120000 = 2 minit. Tukar jika mahu tempoh lain.
Di skrin pameran, buka `kiosk.html` dalam pelayar mod skrin penuh (F11).

## Menambah PDF untuk dibaca pengunjung
1. Letak PDF dalam `assets/` (cth: `assets/manuskrip.pdf`).
2. Dalam `index.html` DAN `kiosk.html`, cari `const DOCS` lalu isi:
       pdf:"assets/manuskrip.pdf"
       pdf:"assets/terbitan-1979.pdf"
