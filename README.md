# Toolkit

Kumpulan tool web statis: Profile Photo Builder, Timeline Builder, dan Presentation Builder.

## Struktur
- `index.html`: homepage, tautan ke tiap tool
- `foto-profil.html`, `timeline.html`, `presentation.html`: satu file per tool, berdiri sendiri

## Memperbarui tool
Ganti file tool yang bersangkutan, lalu commit. Tautan "← Toolkit" di tiap tool menuju `./index.html`, jadi nama file jangan diubah tanpa memperbarui tautan itu.

## Catatan
- Semua pemrosesan terjadi di browser. Tidak ada data yang dikirim ke server.
- Draf autosave tersimpan di browser masing-masing (localStorage), tidak dibagikan antar pengguna.
- Pembuatan PDF memakai jsPDF yang dimuat dari CDN, jadi perlu koneksi internet.

## Lisensi
Hak cipta © 2026 PT. Laju Giat Optimal. Seluruh hak dilindungi. Kode, logo, dan template di repo ini tidak untuk digunakan ulang tanpa izin.
