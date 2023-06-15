# database Data Barang

## Menjalankan Aplikasi
1. Pastikan telah menjalankan MySQL Server.
2. Compile dan jalankan kelas App.java untuk memulai aplikasi.
3. Pada menu utama, terdapat beberapa opsi yang tersedia:
   - Pilih opsi 1 untuk membaca informasi produk dari basis data.
   - Pilih opsi 2 untuk menambahkan informasi produk baru ke dalam basis data.
   - Pilih opsi 3 untuk mengubah informasi produk yang sudah ada dalam basis data.
   - Pilih opsi 4 untuk menghapus informasi produk dari basis data.
   - Pilih opsi 0 untuk keluar dari aplikasi.

## com
- Folder com.config berisi kelas DbConnect yang bertanggung jawab mengatur koneksi ke basis data.
- Folder com.controller berisi kelas DBController yang digunakan untuk mengontrol data produk dalam basis data.
- Folder com.layout berisi berbagai kelas yang mengatur tampilan dan interaksi dengan pengguna.
- Folder com.models berisi kelas Produk yang merepresentasikan model data produk.

## com.layout
- Menu: Berfungsi sebagai menu utama aplikasi. Metode showMenu() digunakan untuk menampilkan opsi-opsi menu kepada pengguna    dan mengarahkan pengguna ke opsi yang dipilih.
- ReadData: Digunakan untuk membaca dan menampilkan informasi produk dari basis data kepada pengguna. Metode getDatabase() digunakan untuk mengambil data dari basis data dan menampilkannya di layar.
- InsertData: Digunakan untuk menambahkan informasi produk baru ke dalam basis data. Metode insertData() meminta pengguna memasukkan detail produk baru seperti nama, harga, dan jumlah, kemudian data tersebut akan disimpan dalam basis data.
- EditData: Digunakan untuk mengubah jumlah produk yang ada dalam basis data. Metode editData() meminta pengguna memasukkan ID produk yang ingin diubah dan jumlah baru, kemudian data akan diperbarui dalam basis data.
- DeleteData: Digunakan untuk menghapus informasi produk dari basis data. Metode deleteData() meminta pengguna memasukkan ID produk yang ingin dihapus, kemudian data tersebut akan dihapus dari basis data.

## com.models
Kelas Produk.java digunakan untuk merepresentasikan produk dalam basis data. Setiap objek Produk memiliki ID, nama, harga, dan jumlah stok yang berkaitan dengan produk tersebut. Kelas ini menyediakan metode untuk mengakses dan mengambil informasi atribut-atribut produk.




