# Accounting Koperasi Plasma

Aplikasi akuntansi sederhana berbasis browser untuk mengelola pembukuan koperasi, khususnya koperasi plasma / koperasi agribisnis. Aplikasi ini dibuat sebagai file tunggal HTML tanpa framework, sehingga mudah dijalankan di komputer lokal tanpa instalasi tambahan.

## Fitur utama

- Manajemen beberapa koperasi dalam satu browser
- Daftar akun / Chart of Accounts (COA)
- Pencatatan transaksi kas masuk dan kas keluar
- Jurnal umum
- Buku besar
- Neraca
- Laporan laba rugi
- Laporan arus kas
- Neraca saldo
- Pencarian transaksi
- Backup dan restore data
- Ekspor data ke format Excel atau JSON

## Teknologi

- HTML
- CSS
- JavaScript vanilla
- IndexedDB browser untuk menyimpan data lokal

## Persyaratan

- Browser modern seperti Chrome atau Edge
- Sistem operasi Windows/macOS/Linux
- Tidak memerlukan server backend atau database eksternal

## Cara menjalankan

1. Buka file `Accounting Koperasi.html` di browser.
2. Jika ingin membuka dari terminal/server lokal, Anda juga bisa menjalankannya dengan server statis ringan, misalnya:

```bash
python -m http.server 8000
```

Lalu buka:

```text
http://localhost:8000/Accounting%20Koperasi.html
```

## Cara penggunaan

### 1. Atur nama koperasi
Pada sisi kiri halaman, masukkan nama koperasi yang aktif. Data koperasi dibuat dan disimpan di browser.

### 2. Kelola akun
Gunakan menu `Daftar akun` untuk menambah, mengubah, atau menghapus akun sesuai kebutuhan. Akun dapat dikelompokkan berdasarkan jenis laporan seperti:

- Aset
- Kewajiban
- Ekuitas
- Pendapatan
- Beban

### 3. Catat transaksi
Masukkan transaksi melalui:

- `Uang masuk/keluar` untuk transaksi kas/bank
- `Jurnal umum` untuk transaksi akuntansi umum

### 4. Lihat laporan
Aplikasi menyediakan laporan yang umum dipakai dalam akuntansi koperasi, termasuk:

- Neraca
- Laba rugi
- Arus kas
- Buku besar
- Neraca saldo

### 5. Backup data
Pada menu `Backup`, Anda dapat:

- memilih folder backup otomatis
- backup data sekarang
- unduh file Excel
- unduh file JSON
- restore data dari file JSON

## Catatan penting

- Data disimpan di browser lokal (IndexedDB), bukan di server online.
- Jika browser atau data browser dihapus, data bisa ikut terhapus.
- Gunakan fitur backup secara berkala agar data aman.

## Struktur file

```text
Accounting-Plasma/
├── Accounting Koperasi.html
├── LICENSE
├── README.md
```

## Lisensi

Proyek ini menggunakan lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail lengkap.

## Penulis

Ridwan Lawson
