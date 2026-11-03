# Form Pendaftaran Mahasiswa Baru

Halaman web sederhana untuk pendaftaran mahasiswa baru, dibuat dengan HTML, CSS, dan JavaScript murni (tanpa library tambahan).

## Fitur

- Tampilan kartu responsif dengan tata letak dua kolom (satu kolom di layar kecil)
- Validasi form langsung di browser dengan pesan error di bawah setiap kolom
- Tombol **Lihat/Sembunyi** untuk menampilkan password
- Hasil pendaftaran ditampilkan dalam bentuk tabel
- Tanggal lahir diformat dalam bahasa Indonesia, lengkap dengan perhitungan usia
- Kategori nilai otomatis (Sangat Baik, Baik, Cukup, Perlu Peningkatan)
- Tombol **Reset** untuk mengosongkan form dan **Hapus Hasil** untuk menghapus tabel hasil

## Struktur Proyek

```
.
├── index.html   # Struktur halaman dan logika JavaScript
├── style.css    # Seluruh gaya tampilan
└── README.md    # Dokumentasi proyek
```

## Cara Menjalankan

1. Simpan `index.html` dan `style.css` di folder yang sama.
2. Buka `index.html` dengan browser (Chrome, Firefox, Edge, dll).
3. Isi form lalu klik **Daftar**.

Tidak perlu instalasi atau server khusus.

## Aturan Validasi

| Kolom         | Aturan                          |
| ------------- | ------------------------------- |
| Nama Lengkap  | Minimal 3 karakter              |
| Email         | Harus berformat email yang valid |
| Password      | Minimal 6 karakter              |
| Tanggal Lahir | Wajib diisi                     |
| Nilai Seleksi | Angka antara 0 sampai 100       |
| Jurusan       | Wajib dipilih                   |

## Kategori Nilai

| Rentang Nilai | Kategori          |
| ------------- | ----------------- |
| 85 – 100      | Sangat Baik       |
| 70 – 84       | Baik              |
| 55 – 69       | Cukup             |
| 0 – 54        | Perlu Peningkatan |

## Pilihan Jurusan

- Teknik Informatika
- Sistem Informasi
- Manajemen

## Catatan

Data yang diisi hanya ditampilkan di halaman dan tidak dikirim atau disimpan ke server maupun penyimpanan browser.

## Pengembangan Lanjutan

- Memisahkan JavaScript ke file `script.js`
- Menyimpan data pendaftar ke `localStorage` atau database
- Menambahkan tema gelap
