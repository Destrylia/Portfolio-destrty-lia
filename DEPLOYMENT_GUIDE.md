# Quick Start - Deploy Portfolio Website in 10 Minutes

Untuk Destry. Tidak perlu coding. Cukup ikuti langkah ini.

## OPSI A — GitHub Pages (Free, Permanent URL)

### Persiapan (2 menit)
1. Buka https://github.com
2. Klik "Sign up" pojok kanan atas, daftar pakai email Destry
3. Pilih username yang profesional. Rekomendasi: `destrylias` (matching LinkedIn). Username ini akan jadi URL portfolio: `https://destrylias.github.io`

### Buat Repository (3 menit)
1. Setelah login, klik tombol hijau "New" di kiri (atau buka https://github.com/new)
2. Repository name: **harus persis sama dengan username + `.github.io`**. Contoh: `destrylias.github.io`
3. Set ke **Public**
4. Centang "Add a README file"
5. Klik "Create repository"

### Upload Files (3 menit)
1. Di repository yang baru dibuat, klik "Add file" → "Upload files"
2. Drag-and-drop dua file ini dari folder yang Hazel kirim:
   - `index.html`
   - `README.md` (overwrite README yang sudah ada)
3. Scroll ke bawah, isi commit message: "Initial portfolio"
4. Klik "Commit changes"

### Aktifkan GitHub Pages (2 menit)
1. Klik tab "Settings" di repository
2. Di sidebar kiri, klik "Pages"
3. Di "Source", pilih "Deploy from a branch", branch `main`, folder `/ (root)`
4. Klik "Save"
5. Tunggu 1-3 menit

### Cek Hasil
Buka `https://destrylias.github.io` (atau username yang dipakai). Site sudah live.

### Update Konten di Masa Depan
1. Buka repository di GitHub
2. Klik file `index.html`
3. Klik ikon pensil (Edit) di kanan atas
4. Edit teks yang ingin diubah
5. Scroll ke bawah, klik "Commit changes"
6. Tunggu 1 menit, site terupdate

---

## OPSI B — Netlify (Free, Lebih Mudah, Drag & Drop)

Kalau GitHub terasa rumit, pakai ini:

1. Buka https://app.netlify.com/drop
2. Drag folder yang berisi `index.html` ke kotak "Drag and drop your site folder here"
3. Netlify auto-generate URL seperti `https://glittering-cassata-12345.netlify.app`
4. Klik "Site settings" → "Change site name" untuk ubah jadi `destrylias-portfolio` atau nama yang lebih profesional
5. Site live di `https://destrylias-portfolio.netlify.app`

Untuk update: drag folder yang sudah diedit ke dashboard Netlify lagi.

---

## OPSI C — Vercel (Free Alternative)

1. Buka https://vercel.com/signup, daftar pakai GitHub atau email
2. Klik "Add New..." → "Project"
3. Import dari folder lokal, atau dari GitHub repo
4. Deploy otomatis

---

## Customisasi Sebelum Submit ke BTN

Sebelum submit aplikasi ke BTN, edit `index.html` untuk:

### Wajib Update
- [ ] **LinkedIn URL** — Search untuk `linkedin.com/in/destrylias` di file. Ganti dengan URL LinkedIn Destry yang asli. Update di 2 tempat: nav contact dan hero meta.
- [ ] **Email** — Konfirmasi `destrylia650@gmail.com` benar. Jika ada email lain yang lebih profesional, ganti.
- [ ] **Phone** — Konfirmasi nomor `+62 857-7056-2694` benar.
- [ ] **Portfolio URL di CV** — Setelah portfolio live, update CV agar URL match (saat ini CV menulis `destrylias.github.io`)

### Opsional (Nice to Have)
- [ ] Tambah foto profesional di hero section (foto formal, background netral, dress code business)
- [ ] Tambah link ke certificate verification dari Google/IBM/UCI
- [ ] Tambah link ke project repository di GitHub jika ada (e.g. SME Credit Readiness Dashboard repo)
- [ ] Buat halaman terpisah untuk masing-masing project case study (tidak wajib untuk submit awal)

### Kosmetik (Setelah Ada Waktu)
- [ ] Custom domain (opsional, biaya ~150rb/tahun): beli domain seperti `destrylia.com` di Namecheap, lalu setup di GitHub Pages
- [ ] Favicon (icon kecil di tab browser): generate di favicon.io, upload sebagai `favicon.ico`
- [ ] Google Analytics untuk track berapa orang yang lihat portfolio

---

## Checklist Sebelum Submit Aplikasi BTN

- [ ] Portfolio sudah live dan bisa diakses dari device lain (test di HP)
- [ ] Semua link di portfolio working (email, LinkedIn)
- [ ] CV PDF sudah final, tidak ada typo
- [ ] CV mention URL portfolio yang sudah live
- [ ] LinkedIn profile sudah dioptimisasi (lihat panduan LinkedIn Optimization di chat terpisah)
- [ ] LinkedIn mention link portfolio di Featured section dan About
- [ ] File name CV: `Destry_Lia_Sulistyowati_CV_ODP_Business_Banking_BTN.pdf`
- [ ] Print test CV — pastikan terlihat profesional di kertas (recruiter kadang print untuk shortlist)
- [ ] Mock interview minimal 1x dengan Hazel pakai 8 pertanyaan interview yang sudah disiapkan

---

## Troubleshooting

**Site tidak muncul setelah 5 menit di GitHub Pages**
- Cek di Settings → Pages, pastikan "Your site is live at..." sudah muncul
- Cek nama repository persis `<username>.github.io`, bukan typo
- Coba clear browser cache atau buka di incognito

**Font tidak muncul (terlihat default)**
- Pastikan ada koneksi internet — font Fraunces & Manrope di-load dari Google Fonts
- Cek browser console (F12) untuk error

**Mobile terlihat aneh**
- Site sudah responsive. Coba di Chrome DevTools mode mobile untuk debug
- Jika ada masalah spesifik, beri tahu Hazel screen size yang bermasalah

---

Selesai. Total waktu deployment estimasi 10-15 menit untuk pemula.

Good luck dengan aplikasi BTN.
