Nama: Meisy Nadia Nababan
<br>NIM: 2341760031
<br>Kelas: SIB 3F
<br>Mata Kuliah: Pemrograman Mobile

Praktikum 1: Membuat Project Flutter Baru
1. Proses pembuatan project baru selesai.
![Screenshot hello_world](images/02.png)

Praktikum 2: Menghubungkan Perangkat Android atau Emulator
Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.

https://developer.android.com/codelabs/basic-android-kotlin-compose-connect-device?hl=id#0


Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum
1. Buat repository baru dengan nama "flutter-fundamental-part1"
![Screenshot hello_world](images/03.png)
2. Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project.
![Screenshot hello_world](images/04.png)
3. Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.
![Screenshot hello_world](images/05.png)
4. Beri pesan commit "tambah gitignore" lalu klik Commit (✔)
<br>![Screenshot hello_world](images/06.png)
5. Lakukan push dengan klik bagian menu titik tiga > Push
<br>![Screenshot hello_world](images/07.png)
6. Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"
<br>![Screenshot hello_world](images/08.png)
7. Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote
<br>![Screenshot hello_world](images/09.png)
8. Setelah berhasil, tulis remote name dengan "origin"
<br>![Screenshot hello_world](images/10.png)
9. Commit juga pada README
<br>![Screenshot hello_world](images/11.png)
10. Setelah itu berhasil tampil kedua file yang di push
<br>![Screenshot hello_world](images/12.png)
11. Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub seperti berikut.
<br>![Screenshot hello_world](images/13.png)
<br>![Screenshot hello_world](images/14.png)
12. Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama akan tampil seperti berikut.
<br>![Screenshot hello_world](images/16.png)
13. Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository. 
<br>![Screenshot hello_world](images/17.png)
<br>![Screenshot hello_world](images/18.png)

Praktikum 4: Menerapkan Widget Dasar
1. Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. 
<br>![Screenshot hello_world](images/19.png)
<br> Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik, lalu dibuat laporan pada file README.md.
<br>![Screenshot hello_world](images/20.png)
2. Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.
<br>![Screenshot hello_world](images/21.png)
<br> Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.
<br>![Screenshot hello_world](images/22.png)

Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino
1. Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
<br>![Screenshot hello_world](images/23.png)
<br>![Screenshot hello_world](images/24.png)
2. Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.
<br>Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
<br>![Screenshot hello_world](images/25.png)
3. Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design. Ubah isi kode main.dart seperti berikut
<br>![Screenshot hello_world](images/26.png)
4. Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.
Ubah isi kode main.dart seperti berikut.
<br>![Screenshot hello_world](images/27.png)
5. Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.<br>Contoh penggunaan TextField widget adalah sebagai berikut:
<br>![Screenshot hello_world](images/28.png)
6. Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.
<br>![Screenshot hello_world](images/29.png)
<br>![Screenshot hello_world](images/30.png)