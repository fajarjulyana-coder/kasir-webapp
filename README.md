# kasir-webapp
A Flask POS (kasir) — clean code, no production data, migrations only

Aplikasi kasir berbasis **Flask** untuk mengelola barang, transaksi, dan stok.
Dilengkapi dengan fitur **login admin/kasir**, **keranjang belanja**, dan **pencetakan struk**.
Database SQLite digunakan untuk pengembangan dan bisa digenerate ulang via script migrasi.

## ✨ Fitur Utama

* **Manajemen Barang**: Tambah, edit, hapus item.
* **Keranjang Belanja**: Pilih barang dan simpan transaksi.
* **Cetak Struk**: Print struk langsung dari aplikasi.
* **Sistem Login**: Admin dan Kasir dengan hak akses berbeda.

## 🛠️ Instalasi

1. **Clone repository**

   ```bash
   git clone https://github.com/fajarjulyana-coder/kasir-webapp.git
   cd kasir-webapp
   ```

2. **Buat virtual environment & aktifkan**

   ```bash
   python -m venv venv
   source venv/bin/activate      # Linux / Mac
   venv\Scripts\activate         # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Jalankan aplikasi**

   ```bash
   flask run
   ```

   Buka browser: `http://127.0.0.1:4001`

## 📂 Struktur Folder

```
aplikasi-kasir/
│── app.py
│── templates/
│── static/
│── migrations/        # Skrip migrasi DB
│── requirements.txt
│── README.md
```

> ⚠️ Database SQLite (`database.db`) **tidak disertakan** di repo. Gunakan skrip migrasi untuk membuat database baru.

## 📜 Lisensi

[MIT License](LICENSE)
