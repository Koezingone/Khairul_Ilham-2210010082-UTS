# Aplikasi Resep Masakan

**Aplikasi Resep Masakan** adalah aplikasi Java sederhana yang memungkinkan pengguna untuk mengelola daftar resep masakan. Dengan aplikasi ini, pengguna dapat menambahkan resep baru, mengedit resep yang ada, mencari resep tertentu, serta mengimpor dan mengekspor daftar resep.

## Fitur Aplikasi

- Menambahkan resep baru ke dalam daftar resep.
- Mengedit resep yang sudah ada.
- Menghapus resep dari daftar.
- Mencari resep berdasarkan nama masakan.
- Menampilkan semua resep dalam daftar.
- Mengekspor daftar resep ke dalam file.
- Mengimpor daftar resep dari file.
- Antarmuka pengguna yang sederhana dan mudah digunakan.

## Komponen Utama

- **JFrame, JPanel, JTextArea, JTextField, JList, JButton** untuk membangun antarmuka pengguna.
- **ActionListener** untuk menangani interaksi pengguna dengan tombol.
- **HashMap** untuk menyimpan data resep secara efisien.
- Penanganan **IOException** untuk membaca/menulis file saat ekspor dan impor data.

## Cara Menggunakan

1. Masukkan nama masakan pada kolom pencarian dan klik tombol **CARI** untuk mencari resep berdasarkan nama.
2. Klik tombol **TAMBAH** untuk menambahkan resep baru ke daftar. Anda akan diminta memasukkan nama masakan dan detail resepnya.
3. Pilih masakan dari daftar, lalu klik tombol **EDIT** untuk mengubah detail resep.
4. Pilih masakan dari daftar, lalu klik tombol **HAPUS** untuk menghapus masakan tersebut.
5. Klik tombol **EKSPOR** untuk menyimpan semua data resep ke dalam file.
6. Klik tombol **IMPOR** untuk menambahkan resep dari file ke dalam daftar.
7. Klik tombol **KELUAR** untuk menutup aplikasi.

## Authors

- **KHAIRUL ILHAM** - 2210010082 - 5C REG BJM

## Screenshots

![App Screenshot](https://github.com/Koezingone/Khairul_Ilham-2210010082-UTS/blob/main/img/Screen%20Recording%202024-11-22%20154627.gif)

## Catatan

- Pastikan file yang digunakan untuk impor memiliki format yang sesuai dengan aplikasi ini.
- Saat menambahkan atau mengedit resep, periksa kembali nama masakan agar tidak terjadi duplikasi.
- Simpan file ekspor di lokasi yang mudah diakses agar dapat diimpor kembali dengan mudah.
