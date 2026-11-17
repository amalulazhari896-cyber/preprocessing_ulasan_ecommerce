# Preprocessing Teks Ulasan E-Commerce Berbahasa Indonesia

**Nama:** Amalul Azhari
**NIM:** 24146078

## Deskripsi
Tugas preprocessing teks pada dataset ulasan produk e-commerce berbahasa Indonesia
([dipawidia/ecommerce-product-reviews-sentiment](https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment)).

Tahapan: case folding, cleaning (URL, angka, tanda baca, karakter khusus), tokenisasi,
stopword removal, dan stemming (Sastrawi), disertai 10 contoh sebelum/sesudah dan analisis pengaruhnya.

## Isi Repositori
- `preprocessing_ulasan_ecommerce.ipynb` : notebook utama
- `README.md` : file ini

## Cara Menjalankan
1. Buka notebook di Google Colab (Upload, atau File > Open notebook > GitHub).
2. Jalankan semua sel (Runtime > Run all).
3. Library yang dipakai: `datasets`, `pandas`, `matplotlib`, `Sastrawi`.
