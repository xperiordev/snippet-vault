# 🗺️ SNIPPET VAULT DEVELOPMENT ROADMAP

## [ ] FASE 1: LAYOUT & INTERFACE BOILERPLATE

- [ ] 1.1 Inisialisasi dokumen HTML5 lengkap dengan tema gelap (_Dark Mode CSS Variables_).
- [ ] 1.2 Pembuatan grid layout: Sisi kiri untuk Form Input, Sisi kanan untuk List Snippet dan Search Bar di atasnya.
- [ ] 1.3 Integrasi CDN FontAwesome untuk ikon tombol copy dan hapus.

## [ ] FASE 2: CORE ENGINE ENGINE & PERSISTENSI DATA

- [ ] 2.1 Buat variabel state `snippets` di JavaScript dan fungsi sinkronisasi otomatis ke `localStorage`.
- [ ] 2.2 Implementasi fungsi penangkapan data dari form input (Gunakan `Date.now()` sebagai ID unik).
- [ ] 2.3 Buat fungsi render dinamis yang mengubah data array menjadi komponen kartu (_card_) HTML.

## [ ] FASE 3: FITUR UTAMA & UX POLISHING

- [ ] 3.1 Buat fungsi filter real-time berbasis event `input` di kolom pencarian.
- [ ] 3.2 Implementasi API `navigator.clipboard.writeText` pada tombol copy dengan efek umpan balik visual (_Tooltip/Text Change_).
- [ ] 3.3 Tambahkan fungsi hapus data berbasis ID dengan konfirmasi dialog bawaan browser.

## [ ] FASE 4: DEPLOYMENT & MAINTENANCE PREPARATION

- [ ] 4.1 Pembersihan baris kode mati (_console.log_ tak terpakai) dan pengujian penyimpanan data saat browser di-refresh.
- [ ] 4.2 Inisialisasi repositori Git lokal dan pengunggahan ke GitHub.
- [ ] 4.3 Aktivasi otomatis layanan gratis GitHub Pages.
