# Bismillahirrahmanirrahim

## Janji
Saya Muhammad Naufal Arbanin dengan NIM 2310850 mengerjakan soal Tugas Praktikum 6 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Penjelasan Alur
### Alur Sistem CRUD Minuman:

#### 1. Tambah Minuman (add):

- User memilih kategori dan supplier dari dropdown yang sudah ada.

- User memasukkan nama dan harga minuman.

- Data minuman disimpan dalam tabel drinks, dengan referensi ke kategori dan supplier.

#### 2. Tampilkan Minuman:

- Pada halaman list.php minuman, aplikasi mengambil data minuman dari database.

- Data ditampilkan dalam bentuk tabel, dengan opsi untuk menambah, mengedit, atau menghapus minuman.

#### 3. Edit Minuman:

- User dapat mengedit nama, harga, kategori, dan supplier minuman yang sudah ada.

- Data yang diedit akan diperbarui dalam tabel drinks berdasarkan ID minuman yang dipilih.

#### 4. Hapus Minuman:

- User dapat menghapus minuman yang ada.

- Sebelum dihapus, akan ada konfirmasi, dan jika sudah yakin, minuman akan dihapus dari database.

### Alur Sistem CRUD Kategori:

#### 1. Tambah Kategori:

- User dapat menambahkan kategori minuman seperti "Teh", "Kopi", "Soda", dll.

- Data kategori disimpan dalam tabel drink_categories.

- Kategori ini akan digunakan saat menambahkan atau mengedit minuman.

#### 2. Tampilkan Kategori:

- Pada halaman list.php kategori, aplikasi mengambil data kategori dari database.

- Data ditampilkan dalam bentuk tabel, dengan opsi untuk menambah, mengedit, atau menghapus kategori.

#### 3. Edit Kategori:

- User dapat mengedit nama kategori yang ada.

- Data yang diedit akan diperbarui dalam tabel drink_categories berdasarkan ID kategori yang dipilih.

#### 4. Hapus Kategori:

- User dapat menghapus kategori yang ada.

- Sebelum dihapus, akan ada konfirmasi, dan jika sudah yakin, kategori akan dihapus dari database.

### Alur Sistem CRUD Supplier:

#### 1. Tambah Supplier:

- User dapat menambahkan informasi supplier seperti nama dan kontak.

- Data supplier disimpan dalam tabel suppliers.

- Supplier ini akan digunakan saat menambahkan atau mengedit minuman.

#### 2. Tampilkan Supplier:

- Pada halaman list.php supplier, aplikasi mengambil data supplier dari database.

- ata supplier ditampilkan dalam bentuk tabel, dengan opsi untuk menambah, mengedit, atau menghapus supplier.

#### 3. Edit Supplier:

- User dapat mengedit informasi supplier seperti nama dan kontak.

- Data yang diedit akan diperbarui dalam tabel suppliers berdasarkan ID supplier yang dipilih.

#### 4. Hapus Supplier:

- User dapat menghapus supplier yang ada.

- Sebelum dihapus, akan ada konfirmasi, dan jika sudah yakin, supplier akan dihapus dari database.

### Relasi Antara Tabel:
Tabel drinks berhubungan dengan tabel drink_categories dan suppliers melalui foreign key:

- category_id pada tabel drinks merujuk ke category_id di tabel drink_categories.

- supplier_id pada tabel drinks merujuk ke supplier_id di tabel suppliers.

Dengan demikian, saat menambahkan atau mengedit minuman, user akan memilih kategori dan supplier dari dropdown yang diisi otomatis dengan data dari tabel drink_categories dan suppliers.

## Dokumentasi Video
https://github.com/user-attachments/assets/e672347b-b8db-426a-bfe2-8d2d2a2bfe7b

