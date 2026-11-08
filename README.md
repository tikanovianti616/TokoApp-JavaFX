# 🛍️ TokoApp - Aplikasi Pencatatan Produk Toko (JavaFX)

Aplikasi desktop manajemen produk toko berbasis JavaFX dengan antarmuka bertema **Pastel Aesthetic (Cewek Kue)**.

## ⚙️ Cara Kerja Aplikasi
1. **Model & Data (`Produk.java`, `DataProduk.java`)**: Menyimpan data produk dan mengelola `ObservableList` secara terpusat agar sinkron di seluruh halaman.
2. **Navigasi (`Navigator.java`)**: Menangani alih halaman secara dinamis.
3. **Form Input (`FormController.java`)**: Mengambil input produk baru dan memperbarui daftar data.

   <img width="442" height="717" alt="WhatsApp Image 2026-11-08 at 13 29 16" src="https://github.com/user-attachments/assets/7cb5f134-43e7-4c1e-b3c2-00d5b82d84da" />

5. **Daftar Produk (`DaftarController.java`)**: Menampilkan data pada `TableView` dengan fitur pencarian teks dan filter kategori.

    <img width="800" height="841" alt="WhatsApp Image 2026-11-08 at 13 29 32" src="https://github.com/user-attachments/assets/8d475f09-a689-4fc6-91e9-2074c1ea7bf8" />

7. **Detail Produk (`DetailController.java`)**: Menampilkan rincian informasi dan foto produk yang dipilih dari tabel.

   <img width="365" height="691" alt="WhatsApp Image 2026-11-08 at 13 29 48" src="https://github.com/user-attachments/assets/bf6b2c60-9f75-4608-b1f3-724c171c9200" />

## 🚀 Cara Menjalankan Project
1. Download dan ekstrak file **`TokoApp.zip`**.
2. Buka project di **NetBeans IDE**.
3. Jalankan **Clean and Build** (`Shift + F11`).
4. Run `MainApp.java` (`F6`).
