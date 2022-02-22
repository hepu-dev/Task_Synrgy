
# Autentikasi

Folder `script` berisi script yang saya gunakan pada saat mengajar materi, folder `app` adalah contoh sederhana yang dibuat untuk materi ini.

Setiap kode saya berikan komentar untuk mempermudah membacanya.

## Syarat Proyek

- Database, saya menggunakan postgres
- Node.js & NPM

## Menjalankan

```bash
$ npm install 
$ node app/index.js
```

## Tutorial

Kali ini saya akan menjelaskan tentang bagaimana cara program bekerja. Sebelum ke kode ada baiknya kita mengetahui fungsionalitas program terlebih dahulu, sebaik - baiknya program adalah kejelasan tetang penggunaannya.

1. Halaman Login, untuk login
2. Dapat login dengan 2 akun yaitu, email dan password :

```
admin@binar.com - password123
student@binar.com - 123123
```

3. Login dengan akun admin, akan menuju ke halaman admin `/admin` dan juga bisa membuka halaman `/student`
4. Login degan akun student, akan menuju ke halaman student `/student` tapi student tidak bisa menuju ke halaman admin, jika mengakses halaman admin maka akan di munculkan tulisan bahwa akses tidak dibuka