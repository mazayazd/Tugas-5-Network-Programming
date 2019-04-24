## **Tugas-5-Network-Programming-Kelompok**

### **Anggota:**
        
        Fadillah Rizky R                1301164493
        Mazaya Z D                      1301154508
        Renaning Karutami Susilo        1301154466
        
### **HTML**

HTML (HyperText Markup Language) adalah bahasa pemrograman standar yang digunakan untuk membuat sebuah halaman web, yang kemudian dapat diakses untuk menampilkan berbagai informasi di dalam sebuah penjelajah web Internet (Browser).
Fungsi html yang pertama adalah untuk membuat suatu halaman website yang dapat dibaca dan dipahami oleh pengguna dengan lebih mudah. Lalu, menandai teks pada suatu laman.

### **HTTP**

HTTP (Hypertext Transfer Protocol) merupakan istilah yang diberikan pada sebuah protokol dan dipergunakan untuk mengirimkan dokumen dari WWW (World Wide Web). HTTP dapat pula diartikan sebagai protokol jaringan untuk pendistribusian sistem informasi hypermedia secara kolaboratif. Fungsi utama dari protokol HTTP sebenarnya cukup sederhana, yaitu untuk mengkomunikasikan satu komputer dengan lainnya.Selain itu, HTTP juga berfungsi untuk menentukan bagaimana sebuah data atau pesan dapat ditransmisikan maupun diformat menjadi bentuk yang dapat merespon browser untuk menampilkan data-data tersebut.

Cara Kerja HTTP:
1. Pertama-tama, komputer klien (HTTP klien) membuat sambungan, lalu mengirimkan permintaan dokumen ke web server.
2. HTTP server kemudian memproses permintaan klien, sementara itu, HTTP klien menunggu respon dari server (berupa HTML) tersebut.
3. Web server merespon permintaan dengan kode status data, lalu barulah menutup sambungan ketika telah selesai memproses    permintaan.           

**Soal 1**

Buatlah perancangan aplikasi Web Server yang digunakan untuk melakukan serve terhadap file HTML dan CSS menggunakan diagram FSM serta jelaskan cara kerjanya!

**Jawaban:**

![FSM No 1](https://user-images.githubusercontent.com/33456025/56653403-d2037100-66b7-11e9-9eea-3d7c8f8fda7e.jpg)

**Soal 2**

Implementasikan aplikasi web server dari design yang sudah anda buat, aplikasi harus mempunyai config file untuk melakukan konfigurasi aplikasi!

**Jawaban:**
![run server](https://user-images.githubusercontent.com/33456025/56653887-edbb4700-66b8-11e9-9154-92a5f31878ca.PNG)

Running Main.go

![simple server new](https://user-images.githubusercontent.com/33456025/56653602-29a1dc80-66b8-11e9-87d4-135c57158397.PNG)

Ketika Server listening, lalu buka localhost:8383 pada browser. Ini adalah tampilan awal pada simple web server

![server new 2](https://user-images.githubusercontent.com/33456025/56653673-59e97b00-66b8-11e9-8ad4-7e949dae268a.PNG)

Pada halaman awal terdapat tombol adder, netpro dan text. Ini adalah isi pada halaman teks

![server new 3](https://user-images.githubusercontent.com/33456025/56653730-843b3880-66b8-11e9-9a3e-8cffea7a49e7.PNG)

Untuk halaman netpro, setelah berhasil menekan tombol netpro maka lokasi akan dipindahkan ke https://github.com/mazayazd/. Maka seperti ini tampilan yang diberikan.

![server error salah IP](https://user-images.githubusercontent.com/33456025/56653769-99b06280-66b8-11e9-87de-a0b732ad8b4b.PNG)

Tampilan akan menjadi error apabila IP atau port yang dimasukkan tidak sesuai. 
