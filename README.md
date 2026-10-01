# E-Surat & SPPD — GitHub Static Preview

Versi ini TANPA DATABASE. Tidak memakai Apps Script, Spreadsheet, Cloudflare Worker, atau D1.

## Perilaku
- Semua data surat hanya diproses di browser.
- Preview dan cetak tetap dapat digunakan.
- Refresh/reload menghilangkan data yang sedang diisi.
- Default identitas sekolah: **SMKS Budi Mulya**.
- Identitas sekolah dapat diedit dari menu Setting selama halaman terbuka.
- Perubahan setting tidak disimpan permanen; refresh mengembalikan default.

## Upload GitHub Pages
1. Buat repository baru.
2. Upload `index.html` dan `config.js`.
3. Commit ke branch `main`.
4. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
5. Buka URL GitHub Pages.

Tidak perlu Node.js/Wrangler/D1/Apps Script.

## Catatan
Versi ini dimaksudkan untuk penggunaan preview/cetak ringan. Jika nanti ingin menyimpan arsip surat, gunakan versi database Cloudflare D1.
