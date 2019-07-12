# Menjalankan dan Membaca Demo Program di Badak
Di dalam Badak, terdapat banyak sekali demo program yang bisa kalian jalankan untuk membantu kalian belajar, terutama bahan-bahan setelah UAS. Berikut ini langkah-langkah yang bisa kalian ikuti untuk menjalan program di Badak.

## Cara Meng-*compile* dan Menjalankan File Demo di Badak

1. Terdapat beberapa cara untuk meng*compile* dan *run* file di badak dan tergantung dari tipe file tersebut.
    Lihat gambar berikut sebagai contoh:
    
    ![Screenshot_256](https://user-images.githubusercontent.com/51958728/60413637-d2604100-9bff-11e9-9a3d-83b5f75058a7.png)

2. Untuk meng*compile* semua file [nama-file].c gunakan command **make** dan akan muncul file hasil *compile* tersebut

    ![Screenshot_257](https://user-images.githubusercontent.com/51958728/60413800-5fa39580-9c00-11e9-90dd-6cb0c79a0ef5.png)

3. Kemudian menjalankan program yang di inginkan dengan command **./[nama-file]** Seperti contohnya

    ![Screenshot_258](https://user-images.githubusercontent.com/51958728/60414032-27e91d80-9c01-11e9-8f6e-c98ed163b94a.png)

4. Apabila ingin membuka atau membaca file dengan type .txt dapat dengan command **cat[space][nama-file]** contohnya

    ![Screenshot_259](https://user-images.githubusercontent.com/51958728/60414389-36840480-9c02-11e9-9b69-abcd1d1d13ed.png)

5. Terakhir menjalan program dengan command **bash[space][nama-file]**

    ![Screenshot_264](https://user-images.githubusercontent.com/51958728/60415007-1f461680-9c04-11e9-9e6a-3e1f67a4d4c9.png)
	
	
## Cara Membaca File Demo di Badak
Ada beberapa cara untuk membaca file demo yang ada di Badak. Berikut ini langkah-langkahnya:
1. Cari file yang ingin kalian baca dengan perintah **ls**
	
	![Screenshot_001](https://user-images.githubusercontent.com/51855753/61125766-e1cf6c00-a4d4-11e9-82ed-7d6f8b9c1c6a.png)

2. Misalnya kita ingin membaca isi file *01-fork.c*, salah satu caranya adalah dengan perintah **cat**. Dengan perintah ini, semua isinya akan di-*load* langsung.
	
	![Screenshot_002](https://user-images.githubusercontent.com/51855753/61126228-20b1f180-a4d6-11e9-97e6-9f507672febf.png)

3. Jika kalian hanya ingin menge-*load* sepanjang ukuran terminal kalian, kalian bisa menggunakan perintah **more**. Jika kalian mau membaca baris selanjutnya, tinggal menekan Enter di keyboard kalian
	
	![Screenshot_003](https://user-images.githubusercontent.com/51855753/61126325-5656da80-a4d6-11e9-9508-ceba50bc9e1e.png)

4. Perintah lainnya yang bisa kalian gunakan adalah perintah **less**. Perintah ini hampir sama dengan **more**, namun dengan perintah **less** kalian bisa melakukan **scrolling** ke atas dan ke bawah dengan bebas tidak seperti perintah **more** yang hanya bisa ke bawah. Kemudian, jika kalian di akhir file, kalian akan mendapatkan kata [END] yang menandakan isi file tersebut sudah berakhir. Untuk kembali ke terminal semula, tekan **Q** pada keyboard kalian. 
	
	![Screenshot_005](https://user-images.githubusercontent.com/51855753/61126579-075d7500-a4d7-11e9-9c4d-9902f5b4b95b.png)