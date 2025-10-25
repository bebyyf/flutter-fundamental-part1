(div align="center")

# 🌸✨ HELLO WORLD FLUTTER ✨🌸  
_Selamat datang di proyek Flutter pertamaku!_

(/div)

---

## 🖼️ Tampilan Awal
Aplikasi sederhana dengan teks **"Hello World"** menggunakan nama lengkap saya 💖  

![Screenshot Hello World](images/(01.png))

---

## 🧁 Flutter Demo: MyTextWidget

### 🎀 Deskripsi
Proyek ini menampilkan **custom widget** bernama `MyTextWidget` yang memiliki gaya:
- 🎨 Warna teks: **Merah**
- 🔠 Ukuran font: **14**
- 🧭 Rata tengah  
- ➕ Dilengkapi tombol **Floating Action Button (FAB)** untuk menambah counter

![Screenshot MyTextWidget](images/(02.png))

---

(div align="center")

# 💼 JOBSHEET 4 — Laporan Praktikum  
📱 *Pemrograman Mobile* 📱

(/div)

**Nama:** My Babby Findia R.S  
**Kelas:** SIB – 3D  
**No. Absen:** 15  
**GitHub:** [flutter-fundamental-part/bebyyf](https://github.com/bebyyf/flutter-fundamental-part)

---

## 🧩 Praktikum 1 — Membuat Project Flutter Baru

> ✨ Yuk mulai dari awal bikin project pertama kita! ✨  

**Langkah 1:**  
Buka VS Code → `Ctrl + Shift + P` → ketik **Flutter** → pilih **New Application Project**  
![Screenshot Langkah 1](images/(ss1.png))

**Langkah 2:**  
Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in. 😄  
![Screenshot Langkah 2](images/(ss2.png))

**Langkah 3:**  
Beri nama project: `hello_world` seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.
![Screenshot Langkah 3](images/(ss3.png))

**Langkah 4:**  
Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa _“Your Flutter Project is ready!”_ artinya Anda telah berhasil membuat project Flutter baru. 
![Screenshot Langkah 4](images/(ss4.png))

---

## 📱 Praktikum 2 — Menghubungkan Perangkat Android/Emulator

> 📲 Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.

Ikuti panduan di:  
🔗 [Android Codelab - Connect Device](https://developer.android.com/codelabs/basic-android-kotlin-compose-connect-device?hl=id#0)  


---

## 🌐 Praktikum 3 — Membuat Repository GitHub dan Laporan Praktikum

> 💡 Simpan dan bagikan project-mu ke dunia dengan GitHub!

**Langkah 1:**  
Login ke akun GitHub Anda, lalu buat repository baru dengan nama **flutter-fundamental-part1**  
![Screenshot Langkah 1](images/(ss5.png))

**Langkah 2:**  
Klik **Create repository** seperti gambar berikut.
![Screenshot Langkah 2](images/(ss6.png))

**Langkah 3:**  
Kembali ke VS code, project flutter hello_world, buka terminal pada menu `Terminal ) New Terminal`. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.
![Screenshot Langkah 3](images/(ss7.png))

**Langkah 4:**  
Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.
![Screenshot Langkah 4](images/(ss8.png))

**Langkah 5:** 
Beri pesan commit "tambah gitignore" lalu klik Commit (✔)
![Screenshot Langkah 5](images/(ss9.png))

**Langkah 6:** 
Lakukan push dengan klik bagian menu `titik tiga ) Push`
![Screenshot Langkah 6](images/(ss10.png))

**Langkah 7:** 
Di pojok kanan bawah akan tampil seperti gambar berikut. `Klik "Add Remote"`
![Screenshot Langkah 7](images/(ss11.png))

**Langkah 8:** 
Salin tautan repository Anda dari browser ke bagian ini, lalu klik `Add remote`
![Screenshot Langkah 8](images/(ss12.png))

Setelah berhasil, tulis remote name dengan `"origin"`
![Screenshot Langkah 8](images/(ss13.png))

**Langkah 9:** 
Lakukan hal yang sama pada file `README.md` mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.
![Screenshot Langkah 9](images/(ss14.png))

**Langkah 10:** 
Lakukan push juga untuk semua file lainnya dengan pilih `Stage All Changes`. Beri pesan commit `"project hello_world"`. Maka akan tampil di repository GitHub Anda seperti berikut.
![Screenshot Langkah 10](images/(ss15.png))

**Langkah 11:**  
Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan `tekan F5 atau Run ) Start Debugging`. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.
![Screenshot Langkah 11](images/(ss16.png))

**Langkah 12:**  
Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.
![Screenshot Langkah 12](images/(ss17.png))
![Screenshot Langkah 12](images/(ss18.png))

---

## 🧱 Praktikum 4 — Menerapkan Widget Dasar

### 💬 Langkah 1: Text Widget
Buat folder baru `basic_widgets` di dalam folder lib. Kemudian buat file baru di dalam `basic_widgets` dengan nama `text_widget.dart.` Ketik atau salin kode program berikut ke project `hello_world` Anda pada file `text_widget.dart`.
![Screenshot Text Widget](images/(ss19.png))

Lakukan import file `text_widget.dart` ke `main.dart`, lalu ganti bagian `text widget` dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file `README.md`.
![Screenshot Text Widget](images/(ss20.png))

---

### 🖼️ Langkah 2: Image Widget
Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut
![Screenshot Image Widget](images/(ss21.png))

Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.
![Screenshot Image Widget](images/(ss22.png))

Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.
![Screenshot Image Widget](images/(ss23.png))
---

## 🎨 Praktikum 5 — Material Design & Cupertino Widgets

### 🍎 Langkah 1: Cupertino Button dan Loading Bar
Buat file di basic_widgets ) loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.  
![Screenshot Cupertino](images/(ss24.png))

---

### 💫 Langkah 2: Floating Action Button (FAB)
Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.
Buat file di `basic_widgets ) fab_widget.dart`. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.😍  
![Screenshot FAB](images/(ss25.png))

---

### 🏗️ Langkah 3: Scaffold Widget
`Scaffold widget` digunakan untuk mengatur tata letak sesuai dengan material design.
Ubah isi kode main.dart seperti berikut.  
![Screenshot Scaffold](images/(ss26.png))

---

### 💬 Langkah 4: Dialog Widget
Dialog widget pada flutter memiliki dua jenis dialog yaitu `AlertDialog` dan `SimpleDialog`.
Ubah isi kode main.dart seperti berikut.
![Screenshot Dialog](images/(ss27.png))

---

### 🧩 Langkah 5: Input & Selection Widget
Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.
Contoh penggunaan TextField widget adalah sebagai berikut:
  
![Screenshot Input Selection](images/(ss28.png))

---

### ⏰ Langkah 6: Date and Time Pickers
Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers. 
![Screenshot DateTime](images/(ss29.png))

---

(div align="center")

## 🌟✨ Hasil Output Akhir ✨🌟  
Semua widget tampil dengan cantik dan berfungsi sesuai harapan 💖  

![Screenshot Output Akhir](images/(ss30.png))

---

🦋 _"Learning Flutter is like painting with pixels — fun, colorful, and creative!"_ 🎨

(/div)
