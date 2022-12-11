
# notes-app-backend

Repository ini dibuat untuk membangun sebuah _web server_ _RESTful API_ sebagai 
implementasi dari sisi _Back-End_ dari sebuah aplikasi web _Front-End_, yaitu sebuah 
[aplikasi notes sederhana](http://notesapp-v1.dicodingacademy.com/) yang telah disediakan oleh [Dicoding](https://www.dicoding.com/)


## Fungsionalitas

Aplikasi _Back-End_ ini berfungsi untuk menyimpan data (create), membaca data (read), mengubah data (update), 
dan menghapus data (delete) catatan. Fungsionalitas ini dikenal sebagai operasi CRUD.


## Tech

Berikut adalah teknologi yang digunakan untuk membangun aplikasi web server ini :
* [Node.js](https://nodejs.org)
* [Hapi](https://hapi.dev/)
* [ESLint](https://eslint.org/)
* [Nodemon](https://nodemon.io/)


## Menjalankan Web Server

Untuk menjalankan web server ini, maka jalankan perintah berikut terlebih dahulu pada terminal :

```bash
  npm run start
```



Lalu, akses aplikasi sisi client nya [disini](http://notesapp-v1.dicodingacademy.com/).


Kemudian pada bagian header website tersebut, klik *change url*.

![change-url](https://user-images.githubusercontent.com/26517220/206914776-a2170e31-3ccd-4b72-812e-acc3caa3e138.png)



Akan muncul input text untuk menampung host beserta port dari web server yang kita buat. Di project ini, saya menetapkannya pada *localhost:5000*

![insert-url-web-server](https://user-images.githubusercontent.com/26517220/206915045-75ad5c82-d18f-4d0e-97ad-5de6d4a34396.png)



Maka web server dan aplikasi client sudah terhubung.

![result-url-web-server](https://user-images.githubusercontent.com/26517220/206915145-4cc43abb-5204-430c-865a-b4bf28c9cf4e.png)
