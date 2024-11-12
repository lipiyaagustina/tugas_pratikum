# master_plan

PRAKTIKUM 1

1. ![gif](assets/images/1.gif)

Penjelasan: Membuat todolist sesuai langkah pada praktikum

2. - Menyederhanakan Proses Impor
   - Meningkatkan Skalabilitas
   - Meningkatkan Kebersihan dan konsisten kode
   - Mendukung Konvensi dan Praktik terbaik

3. Variabel plan diperlukan untuk menyimpan dan mengelola data model Plan, yang akan ditampilkan dan dimodifikasi di antarmuka pengguna. Sebagai bagian dari StatefulWidget, variabel ini menghubungkan data dengan UI, memungkinkan perubahan seperti menambah atau menghapus tugas.

Deklarasi const untuk digunakan kalau data awal plan bersifat tetap dan tidak diubah, memberikan keamanan, efisiensi memori, dan performa lebih baik. Namun, jika data perlu dimodifikasi (seperti menambah tugas), kata kunci const harus dihapus agar objek bisa diubah.
