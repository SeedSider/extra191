# Badak Basic Guide
Pada bagian ini, kalian akan belajar mengenai perintah-perintah dasar yang bisa kalian coba ketika sudah masuk ke badak dan cara meng-*copy* file dari badak.

## Perintah shell *basic*
- Untuk ‘membersihkan’ tampilan shell seperti tampilan awal ketika baru masuk badak, tekan ```ctrl + l```
- Untuk menggunakan fitur auto completion (contoh: ingin masuk folder dengan nama yang sangat panjang), cukup ketik beberapa karakter awal folder tersebut, lalu klik ```Tab```
- Untuk menampilkan semua file dan folder yang tidak *hidden*, ketik ```ls```
- Untuk pindah direktori/masuk ke folder lain, ketik perintah ```cd nama_folder```
- Untuk kembali ke Home, ketik perintah ```cd```
- Untuk ‘naik’ satu folder/masuk ke folder *parent*, ketik ``cd ..``
- Untuk ‘naik’ dua folder/masuk ke folder *grandparent*, ketik ``cd ../../``
- Untuk membuat folder, ketik perintah ```mkdir nama_folder```
- Untuk membuat file, ketik perintah ```touch nama_file```
- Untuk membuka file *text based*, gunakan ```nano nama_file```, jika telah terbiasa menggunakan ``vi``/``vim``, silahkan menggunakannya
- Untuk menyimpan perubahan di program ```nano```, tekan ``ctrl + o,`` tekan ``Enter``
- Untuk keluar dari ``nano,`` tekan ``ctrl + x``
- Untuk membaca isi file, gunakan perintah ``less nama_file``, untuk keluar dari mode baca file less, tekan ``q``
- Untuk menjalankan script bash (biasanya filenya tidak berekstensi/line pertama dari file berisi ``#!/usr/bin/env`` bash atau ``#!/bin/sh``), ketik ``bash nama_file``
- Untuk menjalankan *file* dengan ekstensi .c, compile terlebih dahulu dengan menjalankan perintah make, lalu jalankan dengan perintah ``./nama_file``
- Untuk keluar ‘paksa’ dari suatu program, ketik ``ctrl + c``

## meng-*copy* folder demos dari /extras/
Ketika kalian sudah bisa mengakses badak, kalian akan melihat bahwa di dalam badak ada banyak sekali bahan-bahan belajar yang sangat berguna bagi kalian. Nah, bagi kalian yang ingin mengcopy file-file tersebut ke folder local kalian, ikuti langkah-langkah berikut ini:
- Masuk ke kawung jika tidak terkoneksi ke jaringan UI
- Masuk ke badak
- Copy folder extra ke direktori home masing-masing dengan memasukkan perintah ```cd```, lalu ``cp -r /home/extra extra/``
- *Compress* foldernya dengan perintah ``tar -cvzf extra.tar.gz extra``
- Pindahkan *file* yang telah di*compress* ke *local* dengan perintah ``scp extra.tar.gz [extra]@kawung.cs.ui.ac.id:~/extra.tar.gz`` (masih di badak)
- Keluar dari badak dan kawung
- Di *local*, masukkan perintah ``scp [user]@kawung.cs.ui.ac.id:~/extra.tar.gz extra.tar.gz``