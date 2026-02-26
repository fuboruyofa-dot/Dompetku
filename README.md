# DompetKu 💰 — Personal Finance App

Aplikasi manajemen keuangan pribadi berbasis web. Data tersimpan di browser (localStorage).

## 🚀 Deploy ke Vercel via GitHub

### Langkah 1 — Buat repository di GitHub
1. Buka [github.com/new](https://github.com/new)
2. Beri nama repo, misalnya `dompetku`
3. Klik **Create repository**

### Langkah 2 — Upload file ke GitHub
Pilih salah satu cara:

**Cara A — Upload langsung di browser:**
1. Di halaman repo yang baru dibuat, klik **uploading an existing file**
2. Drag & drop file `index.html` dan `vercel.json`
3. Klik **Commit changes**

**Cara B — Via Git (terminal):**
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/USERNAME/dompetku.git
git push -u origin main
```

### Langkah 3 — Deploy ke Vercel
1. Buka [vercel.com](https://vercel.com) dan login (bisa pakai akun GitHub)
2. Klik **Add New → Project**
3. Pilih repo `dompetku` dari daftar
4. Klik **Deploy** — biarkan semua setting default
5. Selesai! Vercel akan memberi URL seperti `dompetku.vercel.app`

---

## 📁 Struktur File
```
dompetku/
├── index.html    ← Seluruh aplikasi (HTML + CSS + JS)
├── vercel.json   ← Konfigurasi Vercel
└── README.md     ← Panduan ini
```

## ✨ Fitur
- Dashboard ringkasan keuangan
- Catat pemasukan & pengeluaran
- Kelola akun (Cash, BCA, DANA, dll)
- Atur budget per kategori + notifikasi
- Pantau tabungan
- Filter & cari riwayat transaksi
- Data tersimpan otomatis di browser
