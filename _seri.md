
## Status Bab (CSS), diperbarui 14 Okt 2026
- Bab 18 (`18-performa-render.md`): DITULIS, menunggu persetujuan. Ringkasan satu blok di dalam berkas. Kode di `kode/bab-18/` berisi tiga versi uji: margin (A), transform (B), dan content-visibility (C).
- KLAIM YANG BELUM TERBUKTI DI LINGKUNGAN INI: bab 12 dan 18 menyatakan `transform` tidak memicu layout ulang. Penjelasannya benar secara mekanisme, tetapi TIDAK saya ukur. Verifikasi wajib: rekam versi A dan B di DevTools (tab Performance) dan periksa blok Layout per bingkai. Langkah ada di bab 18, konsep 8.
- Catatan: `will-change` dan `contain: paint` dijelaskan sebagai hal yang harus dipakai hati-hati. Belum diuji efek visualnya.
- Klaim dukungan browser untuk `content-visibility` dan `contain-intrinsic-size` belum dicek ke dokumentasi resmi (bagian audit versi sebelum publikasi).
