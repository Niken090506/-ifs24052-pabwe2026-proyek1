# ifs24052-pabwe2026-proyek1

Frontend **NIXBAY** (Proyek 1 PABWE) — **VueJS** + Vite + Pinia + Tailwind.
Backend ada di repo terpisah: `ifs24052-pabwe2026-proyek1-be` (Express.js + SQLite).

## Menjalankan di komputer lokal

1. Jalankan backend dulu (lihat README repo backend) di `http://localhost:8000`.
2. Lalu:

```bash
git clone https://github.com/Niken090506/ifs24052-pabwe2026-proyek1.git
cd ifs24052-pabwe2026-proyek1
cp .env.example .env
npm install                 # atau: bun install
npm run dev                 # http://localhost:3000
```

## Build, test, dan deployment

```bash
npm test
npm run build               # hasil di dist/
```

Untuk deployment, set `VITE_DELCOM_BASEURL` ke URL backend publik (contoh: `https://<url-backend>/api/v1`) **sebelum** build, karena nilainya ditanam saat build.
