# README

## Deskripsi Proyek

Proyek ini merupakan aplikasi web sederhana yang menampilkan kategori makanan dan detailnya menggunakan API. Terdapat tiga halaman utama:

1. **Halaman Kategori**: Menampilkan daftar kategori makanan.
2. **Halaman Detail Kategori**: Menampilkan daftar makanan berdasarkan kategori yang dipilih.
3. **Halaman Detail Makanan** (Opsional): Menampilkan detail dari makanan yang dipilih.

## Teknologi yang Digunakan

- HTML
- CSS (Bootstrap / Tailwind)
- JavaScript (jQuery)
- API (AJAX / Axios)

## Fitur

### 1. Halaman Kategori
- Menampilkan daftar kategori makanan yang diambil dari endpoint "List of Categories".
- Setiap kategori dilengkapi dengan gambar.
- Ketika kategori dipilih, pengguna akan diarahkan ke halaman Detail Kategori.

### 2. Halaman Detail Kategori
- Menerima parameter `nama kategori` untuk menampilkan makanan berdasarkan kategori.
- Menampilkan daftar makanan lengkap dengan gambar.
- Ketika makanan dipilih, pengguna akan diarahkan ke halaman Detail Makanan.

### 3. Halaman Detail Makanan (Opsional)
- Menerima parameter `id`.
- Menampilkan detail makanan yang dipilih, termasuk gambar, judul, deskripsi/tutorial, resep, dan video YouTube embedded.

## Struktur Folder
```bash
/project-root
│
├── index.html               # Halaman Kategori
├── category-detail.html     # Halaman Detail Kategori
└── meal-detail.html         # Halaman Detail Makanan

```

## Cara Menggunakan

1. **Clone Repository**
   ```bash
   git clone [url repo]
   cd -cmlabs-frontend-internship-test
   file index berada di index.html. jadi mulai dengan membuka index.html terlebih dahulu
