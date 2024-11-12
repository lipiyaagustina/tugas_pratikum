# master_plan

PRAKTIKUM 1

1. ![gif](assets/images/1.gif)

Penjelasan: Membuat todolist sesuai langkah pada praktikum

2. - Menyederhanakan Proses Impor
   - Meningkatkan Skalabilitas
   - Meningkatkan Kebersihan dan konsisten kode
   - Mendukung Konvensi dan Praktik terbaik

3. Variabel plan biasanya merupakan sebuah objek yang merepresentasikan data todo list, seperti judul tugas, tanggal jatuh tempo, status, dll. Dengan menyimpan data todo list dalam sebuah variabel, kita dapat dengan mudah mengakses dan memodifikasi data tersebut di seluruh aplikasi.

Deklarasi const untuk digunakan kalau data awal plan bersifat tetap dan tidak diubah, memberikan keamanan, efisiensi memori, dan performa lebih baik. Namun, jika data perlu diubah (seperti menambah tugas), kata kunci const harus dihapus agar objek bisa diubah.

PRAkTIKUM 2

2. InheritedNotifier hanya akan membangun ulang widget-widget yang benar-benar bergantung pada data yang berubah, sehingga meningkatkan kinerja aplikasi. Dengan menggunakan Notifier, kita dapat mengelola negara secara default dan memperbarui UI secara otomatis ketika negara berubah.
