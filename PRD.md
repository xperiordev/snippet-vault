# PRODUCT REQUIREMENT DOCUMENT (PRD) - SNIPPET VAULT

## 1. Value Proposition Utama

Sistem repositori berbasis web lokal untuk menyimpan, menyaring, dan menyalin potongan kode (_code snippet_) atau prompt AI secara instan (di bawah 1 detik) tanpa membebani memori komputer.

## 2. Spesifikasi Teknologi Terpilih

- Frontend Engine: HTML5 Semantic Element + CSS3 Flexbox/Grid Custom Variables
- Logic Engine: Vanilla JavaScript (ES6+) Native DOM Manipulation
- Data Persistence: Web Storage API (`localStorage`) tanpa server database eksternal
- Icons Base: FontAwesome via CDN Ringan

## 3. Fitur Utama yang Dikunci (Scope IN)

- FORM INPUT: Judul snippet, kategori (Dropdown: Prompt, HTML, CSS, JS, SQL, Other), dan isi teks kode (Textarea).
- SEARCH & FILTER ENGINE: Kolom pencarian real-time yang memfilter judul dan kategori secara langsung (_case-insensitive_).
- ONE-CLICK CLIPBOARD INTERACTION: Tombol aksi untuk menyalin isi teks secara otomatis ke clipboard sistem operasi pengguna tanpa memblok atau menyorot teks manual.

## 4. Fitur yang DILARANG Masuk MVP (Scope OUT)

- Tidak ada sistem login/registrasi pengguna (Satu perangkat, satu penyimpanan lokal).
- Tidak ada library pihak ketiga untuk pewarnaan kode (_syntax highlighting_) seperti Prism.js atau Highlight.js.
- Tidak ada fitur sinkronisasi cloud/database online (Firebase/Supabase dilarang di fase awal ini).
