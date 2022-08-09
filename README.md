###### Nama    : Aditiya Wirayudha
###### Kelas   : XI RPL 1
###### No.Abs  : 06

# Modul 6

## INTERAKSI DATABASE DENGAN QUERY BUILDER

Kegiatan Praktikum 1 Menampilkan Data dengan Query Builder

1.Database yang digunakan adalah databse penjualan.Kemudian pada file BarangController.php masukkan script seperti ini

![image](https://user-images.githubusercontent.com/109930265/183567490-43fe31a6-537e-442e-9d81-d454a0d37ba0.png)

2.Setelah menambahkan Script diaatas lanjut ke `view/barang/index.blade.php` dan tulis code seperti di bawah

![image](https://user-images.githubusercontent.com/109930265/183567915-00efe875-5298-41b8-acb5-f71270ad2525.png)
 
Sebelum menjalankan file periksa file routes dan pastikan apakah route ``Route::get('/barang', [BarangController::class, 'index']);`` ada.

Sekarang coba jalankan filenya

![image](https://user-images.githubusercontent.com/109930265/183568542-dfacedc3-2b44-4d27-8971-1f37480adaf5.png)

## Menambah Data Dengan Query Builder

1.Menambahkan Data

Pertama tambahkan script seperti dibwah pada file `BarangController.php`
