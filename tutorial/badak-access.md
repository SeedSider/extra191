# Cara Akses Badak

Halo, semua. Di bagian ini, kalian akan belajar mengenai cara mengakses badak berdasarkan OS kalian masing-masing.


## **Windows 10 (1804)**

- Catatan: fitur ssh di Windows 10 hanya tersedia untuk Windows 10 dengan *build number* di atas 1804, untuk cek versi Windows 10, cari ‘run’ di *search bar* dan ketik ‘winver’ untuk melihat versi Windows 10 yang telah terinstal.

  ![img](https://lh5.googleusercontent.com/2Baq_iqBUKl4vpH72U296TuSeNghq5HLqQ-e7MZSktW3bV-lj-kroKaVTFTW9wsxb0ZAKUn0kxFj6t_jz_rIbGxMuns2KjvSxrsPq203AqaPsaCg4vGwnAqgkKobGldqMSoSZHRb)

  ![img](https://lh5.googleusercontent.com/rwyoF9QT37_tzw5JUb5fQu7qTPc703WqsQmVvIERjr2KYFAiuOrUp7qoxBko5NYKlrOsnJBkxmrEjnHai0EGc6nvJ79_WrfFwmE7Y1o2FgnBNXbh0JAQ7MkFO2BSPigQX_5nb0jO)

  ![img](https://lh4.googleusercontent.com/Q_snV1YvqDwrxnaWqYGiSE159RxHwTVD3oGB3eSu-5DH4menlFSJMVkeLbTfiG8u2qe13fHVo0cAlmwb6KCQ77YXM2-zk-DkImthtgXX3wIhaiWIWG_S5WVUu7M4H5gEjAFIMFpT)

- Cari ‘Powershell’ atau ‘CMD’ di *search bar*, lalu buka programnya

  ![img](https://lh4.googleusercontent.com/NADFcz5z20mkIazaqoWFfkqLoQOWctwrsnytdso-E_ZyMwG9alQBsEQYyJ8Xgwr27qhXzAuoOJ9cxrQQl9tnR4daXtl8GvrR_JSo76wY9Qq39dCnQNDXWWqH6voxgoQnFDqepgy1)

- Jika tidak terkoneksi dengan HotSpot - UI, maka harus mengakses kawung terlebih dahulu dengan menulis perintah ```ssh [nama_sso]@kawung.cs.ui.ac.id``` (contoh: ```budi71@kawung.cs.ui.ac.id```)

  ![img](https://lh3.googleusercontent.com/zS-twONlnX05bkWdtb5w8p0L0mFMWtEO23G3LcYA3KRMi5WlKtuNUP7un1xszWjdlBD4njq1cleEv5ikULY_pZx7uXFUeYHvz65nH-aAy8BmooBRq3vvx3jVu52JWgBTayDNDdwO)

- Masukkan perintah yes, setelah itu, anda akan diminta untuk memasukkan *password* SSO anda. Jika berhasil, maka tampilan berikut akan muncul:

  ![img](https://lh3.googleusercontent.com/Cbw14ZFPR7C4xuNzPcE1fPpCGio7hq2iNVrYdxmF6P8v06UGYmqOSb5xlbnpaiC3YFFI72cammS01byrgd-U080HAbwrm9l3Ur_vv2a1Z8UzQv88dIgvxK0scmysV-uR_gRGtkY8)

- Di kawung, akses badak dengan perintah ```ssh [nama_sso]@badak.cs.ui.ac.id```, lalu ketik ‘yes’

  ![img](https://lh5.googleusercontent.com/kD5wrY3CvQEQnqS-OZDfaLwUGBzIsh97wPpgExwef8tPm72ejdzQBdQZ6BEGj3Cz4NPqzUbdIBCWJRpTkp2wGR7JERPJTB-sjOUtvaODt3oH3OJFqDLFBJCP1L1jPM4GTElZ9C_6)

- Masukkan *password* SSO, jika berhasil, maka akan muncul tampilan berikut:

  ![img](https://lh6.googleusercontent.com/12SSAfge7ffQqFDPQ0x0mUSuK-tqnypyBP0V-_Qnkh4ZQjNeirsKUrpWJcUPeVB4cAmRKTzfG1ZWv99vIhY0ccXTSmwwMppMjju6RrG9W01avErMvYlDJ7sz-85-aKzpvz8u8ZNd)



## **Windows 7/8/10 (versi di bawah 1804)**

- Perintah ssh belum tersedia untuk Windows 10 di bawah versi 1804. Oleh karena itu, ssh dapat diakses dengan *client* ssh seperti PuTTY, untuk mengunduh PuTTY dapat diakses melalui link berikut:[https://the.earth.li/~sgtatham/putty/latest/w64/putty-64bit-0.71-installer.msi](https://www.google.com/url?q=https://the.earth.li/~sgtatham/putty/latest/w64/putty-64bit-0.71-installer.msi&sa=D&ust=1561650097860000)
- Buka *file* yang telah diunduh, lalu *install* seperti biasa
- Buka program PuTTY yang telah di[*install*](tutorial/putty-install.md)

  ![img](https://lh4.googleusercontent.com/e2V0dMV_QpDjgwOWYK4WCfgH_KOj8xnC_40ISGzeQ9JqfyNSmQOH8_4UnMsEnDyuTMeQdQ0K-n8HiJhUHut1dbciYkeeI2Q97izanFMwLMCEbDCB15p09Dn4DR3Po_zBidEUd24O)

- Jika badak akan diakses melalui jaringan di luar UI (tidak menggunakan HotSpot - UI), maka masukkan perintah ssh [nama_sso]@kawung.cs.ui.ac.id, lalu klik ‘Open’

  ![img](https://lh5.googleusercontent.com/KDZvJU-uyMLgsVr2eVEeY37Ag6-yUwJ_KZTzltzEqtMpYYD5IyNgw4LvlAuAni0H-YFIJu2TuFvOaZ9UBgIS2o3yjMEAT9h7DHJikFZpM3pRgz99bKOqvDrfCmptbZwpadXqpKnA)

- Klik ‘Yes’ jika keluar *warning* seperti berikut:

  ![img](https://lh5.googleusercontent.com/WHlJ1nGmOZmnZ1EPaDgP7RZ4UicJhT5NRsZ-VtX9SwIxfb3SvTJkNNGh9uXHAd4ZPImzw4ooqLUcVVBeKfPiJip-P6Z5Imoq-Itydd9i1qQ9BVSQnDMnPm5ou1ESLhXcT8z1cB44)



- Masukkan password SSO anda.

  ![img](https://lh4.googleusercontent.com/OoAy3zra3RbUzn66J2kkplcDbsqGujSkJ5mWnt0GRajN00xP_SU4yEcW_FrHdQEouA_kVPTadIcMWC8TFIaC1BbWoJLE9Nmvbfl0UcWmG1eyMOTuLO7COi04Un7ugkW5_2f95JL3)

- Jika berhasil, maka akan muncul tampilan berikut:

  ![img](https://lh5.googleusercontent.com/pP0ijHSZH-105l1c6ERZJ7SulZ59VkD-ndyx0y3Xo7oknM4obd5fd_RoftwxeOeZ7blvklWUaX3i8h52Mk-IhQLAidQqYfUOSVHdcsHk1h0hjfMNjO2jfGplqOyITu4o12P0z-HW)

- Di kawung, akses badak dengan perintah ```ssh [nama_sso]@badak.cs.ui.ac.id```, lalu ketik ‘yes’ (contoh: ```budi71@kawung.cs.ui.ac.id```)

  ![img](https://lh5.googleusercontent.com/BqCkwQedEd0omL1FZ1gLza_OrmZix57GmQCm1FLbc_h4CzRni8bgbqjizbI_SegtSJgCsBQCJ5nSIVkz2Bfrt0lZNTffJ8sbM5f-fo7Hz0zQxxfEjrOVoT5RufaJeCXO7roVjJyH)

- Masukkan *password* SSO, jika berhasil, maka akan muncul tampilan berikut:

  ![img](https://lh4.googleusercontent.com/S032tiPO1e7Kuax9YayLaGZqhE9bIy66UOWQ5sj5v2kR0VmwrpsMX6M3VuqVlp7tSyG5xh4yyQBqOYp3Y88DLeRhVXRSXkwKlB1_vKqLqNnqI5lXW0mtHte_LQY06YUkF4YK2PAL)

  

## **macOS/Linux**

- Buka program terminal pilihan
- Jika sedang terkoneksi di luar jaringan UI (HotSpot - UI), akses kawung dahulu dengan mengetik perintah ```ssh [nama_sso]@kawung.cs.ui.ac.id``` di terminal (contoh: ```budi71@kawung.cs.ui.ac.id```)

  ![img](https://lh4.googleusercontent.com/6oyobv8s2hqC4EqXnAfAw6m9LRPY-PAo7_CiKCkVCboZk_gdIwGqv_4pacoKA0qb8pucGvDvvDZZHJq2FJgf6TqBgT1z_2Liof1PpRhwB-OsrJwnNIDvUr9O4MVuxWLbP5vIRHnt)



- Ketik ‘yes’ untuk *confirm* *ECDSA key fingerprint* dan masukkan password SSO anda

  ![img](https://lh3.googleusercontent.com/K_A9pk1ZHk-Ffi6eAN5wrNcvlh-Y-xHRIVhwY9HQjbSW7ohny5NNyMaXsTjnLWIjxoJLC9Ji0s2EoZEQsj0nPncwrabT8TCqVirCcKw1rg4m0zMmmS0drc_kIPwxAD6qYts2I9hY)

- Jika telah muncul tampilan seperti ini, maka telah berhasil mengakses kawung

  ![img](https://lh3.googleusercontent.com/vyDQMZZ9zVMyH9T9HRa7Q5b4tdvEjoV3RytisifszCV3Sfm1uT38916j7fyImUFYKA9oyVr1ieCayFD8yFPXhXhwey0zVAEKGxB0dlR6dFB2qbilDPynLn1Cod-zINED8gGP_PhP)

- Di kawung, akses badak dengan perintah ```ssh [nama_sso]@badak.cs.ui.ac.id```, lalu ketik ‘yes’

  ![img](https://lh4.googleusercontent.com/7r4CaGmm4YNvR2Wbce3cFt0ZeTppauiCm0m7QJXO7LqOxZdy9hX1xRqV1KaZVelu3vc1OgX10M1XQI5eC8xPh_Bmnkb43T9Sam0XQfh1MOaIIAHTsnSf4_KHcyvUlP224e2y7XjO)

- Masukkan *password* SSO, jika berhasil akan muncul tampilan berikut:

  ![img](https://lh6.googleusercontent.com/wF3dPjM-us--6j7di7wb4IUFiWtPyJfr-8CNfJUA4Zp5xvYYJhyum5iEUulAsNY27sn1qyMoSIJuNBx4GX0ctU3fUCdZVExyw_zMiph6PhNxaOMHQvozKGFct41KvWnGiwW6RgkK)

  

Seperti yang telah disebutkan di atas, cara-cara tersebut bisa kalian ikuti apabila kalian terkoneksi di luar jaringan UI. Jika kalian terkoneksi dengan Hotspot UI, maka kalian dapat langsung mengakses badak tanpa melakukan tunelling melalui kawung terlebih dahulu. Kalian hanya perlu menuliskan perintah ```ssh[nama_sso]@badak.cs.ui.ac.id``` (contoh: ```budi71@badak.cs.ui.ac.id```) pada terminal kalian.