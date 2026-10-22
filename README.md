# Project UTS Pemrograman Web 2 — Kopi Senja

Website statis dua halaman untuk contoh profil UMKM fiktif menggunakan HTML dan CSS.

## Isi project
- `index.html` — halaman profil utama, cerita usaha, ilustrasi, keunggulan, dan navigasi.
- `menu.html` — halaman kedua berisi tabel menu dan harga.
- `style.css` — styling dan layout responsif.
- `assets/` — ilustrasi SVG lokal agar gambar tetap muncul tanpa internet.

## Cara menjalankan di komputer
1. Ekstrak ZIP project ini ke folder yang mudah ditemukan, misalnya `Documents/uts_pemrograman_web2`.
2. Buka folder itu menggunakan Visual Studio Code (`File > Open Folder`).
3. Buka `index.html`. Cara paling sederhana: klik dua kali file tersebut untuk membukanya di browser.
4. Untuk pengalaman lebih nyaman, pasang ekstensi **Live Server** di VS Code, klik kanan `index.html`, lalu pilih **Open with Live Server**.
5. Uji menu navigasi **Beranda**, **Menu & Harga**, dan **Tentang Kami**. Pastikan halaman `menu.html` terbuka dan tabel terlihat.
6. Sesuaikan nama, deskripsi, harga, dan warna dengan idemu sendiri bila diperlukan. Jangan hapus tag navigasi, tabel, elemen semantik, atau CSS karena menjadi bagian kriteria tugas.

## Cara mengambil screenshot
1. Buka halaman beranda dengan ukuran browser yang rapi.
2. Tekan `Win + Shift + S` pada Windows, pilih area halaman, lalu simpan gambar sebagai `screenshot-beranda.png`.
3. Buka `menu.html`, lalu simpan screenshot kedua dengan nama `screenshot-menu.png`.
4. Masukkan dua screenshot ini pada bagian **Tangkapan Layar** di dokumen lembar jawaban.

## Hosting gratis melalui GitHub Pages
1. Buat/login ke akun GitHub.
2. Buat repository baru bernama `uts-pemrograman-web2` dan pilih **Public**.
3. Upload seluruh isi folder ini ke repository (yang di-upload adalah file `index.html`, `menu.html`, `style.css`, dan folder `assets`, bukan hanya file ZIP).
4. Buka **Settings > Pages**.
5. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
7. Tunggu sampai URL website muncul di menu Pages. Bentuk URL umumnya `https://USERNAME.github.io/uts-pemrograman-web2/`, tetapi gunakan URL yang benar-benar ditampilkan GitHub.
8. Buka URL tersebut dan tes kedua halaman. Setelah memastikan berhasil, salin URL itu ke dokumen jawaban.

## Video demonstrasi 5–10 menit
Gunakan OBS Studio atau perekam layar bawaan Windows. Contoh urutan isi video:
- 0:00–1:00 — perkenalan nama, NIM, kelas, dan tujuan website.
- 1:00–3:00 — demonstrasi halaman beranda, profil usaha, dan gambar.
- 3:00–4:30 — buka menu lewat tautan dan jelaskan tabel harga.
- 4:30–6:30 — tunjukkan kode HTML (`header`, `nav`, `main`, `section`, `footer`, `a`, `table`) dan jelaskan fungsinya.
- 6:30–8:00 — tunjukkan `style.css` dan jelaskan warna, layout, jarak, serta responsif.
- 8:00–9:00 — buka versi hosting online dan tes perpindahan halaman.

Simpan video ke Google Drive dengan akses **Anyone with the link / Siapa saja yang memiliki link dapat melihat**, atau upload ke YouTube sebagai **Unlisted / Tidak publik**. Salin link video ke dokumen jawaban.

## Mengisi lembar jawaban UTS
- **Tentang Proyek:** jelaskan bahwa Kopi Senja adalah contoh website statis profil UMKM, dibuat dengan HTML dan CSS serta terdiri dari halaman beranda dan menu.
- **Tangkapan Layar:** masukkan screenshot kedua halaman.
- **Link Website:** masukkan URL GitHub Pages yang sudah berfungsi.
- **Link source code (drive):** opsional bila dosen meminta source code di Drive; bisa pakai tautan repository GitHub jika diterima dosen.
- **Link Video:** masukkan link video demonstrasi yang sudah dapat diakses.

Catatan: harga dan usaha pada contoh ini fiktif. Ganti identitas/isi bila perlu agar sesuai dengan hasil pekerjaanmu sendiri.
