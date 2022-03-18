# Project-insert-data-table-python
This project about learning insert data to table in python (In Indonesia)

File yang digunakan sama karena ada 2 bagian yang berbeda. Di materi sebelumnya menjelaskan tentang creating database dan tables. Untuk ini akan menjelaskan tentang insert data to table.
Untuk menambahkan data ke sebuah tabel, kita dapat menggunakan perintah insert(). Kemudian untuk menginput nilai ke tabel tersebut kita dapat menggunakan klause column=value.
Inserting One Row:
Sebagai contoh yang pertama, kita akan menambahkan 1 baris data ke sebuah tabel employees sebagai berikut:
Pertama, kita pastikan sudah membuat variabel connection supaya terkoneksi ke database.
Lalu kita import perintah insert() dari SQLAlchemy, dilanjutkan dengan menginput 1 baris baru ke tabel employees dan kita simpan di dalam variabel result.
Untuk melihat jumlah baris baru yang telah kita input tadi ke tabel employees, kita gunakan perintah rowcount.
Inserting Multiple Rows: Menambahkan banyak baris ke sebuah tabel, kita dapat membuatnya menjadi list dictionary terlebih dahulu,
terdapat perbedaan dalam menyimpan data tersebut di variabel results dengan menambahkan list dictionary dari data yang ingin kita input setelah pernyataan stmt.
Untuk melihat hasil inputan dari tabel employees, kita import fungsi select terlebih dahulu
