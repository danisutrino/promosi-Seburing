# Portofolio Promosi Desa Seburing

Website statis promosi Desa Seburing (Kec. Semparuk, Kab. Sambas, Kalimantan Barat), siap di-hosting via GitHub Pages.

## Cara publikasi ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `desa-seburing`.
2. Upload file `index.html` ini ke root repository (lewat web GitHub: Add file → Upload files).
3. Buka **Settings → Pages** di repository.
4. Pada "Branch", pilih `main` dan folder `/ (root)`, lalu klik **Save**.
5. Tunggu 1-2 menit, situs akan aktif di `https://<username>.github.io/desa-seburing/`.

## Foto

Foto asli sudah terpasang di halaman ini (sungai, jembatan gantung, gotong royong, sawah, masjid, anak-anak). File-nya ada di folder `images/` — pastikan folder ini ikut di-upload ke GitHub bersama `index.html`, dengan struktur:

```
desa-seburing/
├── index.html
├── README.md
└── images/
    ├── sungai-seburing.jpg
    ├── jembatan-gantung.jpg
    ├── gotong-royong.jpg
    ├── sawah.jpg
    ├── masjid.jpg
    └── anak-anak.jpg
```

## Yang masih perlu kamu lengkapi

- Ganti link "Hubungi Kantor Desa" dan "Lihat lokasi di peta" dengan link/nomor kontak asli (WhatsApp, Google Maps, dll).
- Sesuaikan kutipan testimoni warga dengan kutipan asli jika ada.
- Tambah foto lain kapan saja dengan menyalin file ke folder `images/` lalu menambahkan tag `<img src="images/nama-file.jpg">` di bagian galeri.

Semua data dasar (jumlah penduduk, luas wilayah, nama dusun, sejarah 1949) diambil dari sumber publik desa dan bisa kamu perbarui sesuai data terbaru dari Kantor Desa Seburing.
