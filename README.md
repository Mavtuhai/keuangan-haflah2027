# Frontend PWA Keuangan Haflah 2027

1. Selesaikan pemasangan backend (`../backend/supabase/README.md`).
2. Buka `index.html`, isi `CFG.url` dan `CFG.anon` (Supabase → Project Settings → API; kunci *anon* memang publik).
3. Unggah seluruh isi folder ini ke hosting HTTPS (Cloudflare Pages / Netlify / GitHub Pages — semuanya gratis).
4. Buka di HP → menu browser → "Add to Home Screen". Aplikasi tetap terbuka saat offline; transaksi yang dicatat saat offline masuk antrean dan terkirim otomatis.

Berkas: `index.html` (aplikasi), `manifest.webmanifest`, `sw.js` (cache offline), `icon-192.png`, `icon-512.png`.
Untuk APK, bungkus alamat hosting dengan Bubblewrap (TWA).
