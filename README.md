# Sistem Madrasah Al Falahiyah (versi web)

Seragam, absensi, nilai, E-Rapor, dan SPP dalam satu file HTML. Data tersimpan di browser perangkat (tanpa server, bisa offline).

## Cara memasang di GitHub Pages
1. Buat repository baru di GitHub, lalu unggah semua isi folder ini (bukan zip-nya).
2. Buka **Settings > Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu **Save**.
3. Tunggu 1-2 menit. Alamat aplikasi: `https://NAMA-AKUN.github.io/NAMA-REPO/`.
4. Buka alamat itu di Chrome/Safari, lalu pilih **Pasang sebagai aplikasi** / **Tambahkan ke layar utama**.

## Catatan
- Data tersimpan per perangkat dan per alamat. Unduh cadangan (.json) di tab DATA secara berkala.
- Setelah mengganti `index.html`, ubah `VERSI` di `sw.js` (misalnya `madrasah-v3`) supaya perangkat mengambil versi baru.
