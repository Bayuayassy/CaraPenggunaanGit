**Hallo nama saya Bayu Maulana Ayassy. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah**  *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan **GIT**.
## Cara penginstalan GIT

  - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .
  
  ![Screenshot (17)](https://user-images.githubusercontent.com/115677959/195978004-f83ef297-525c-4675-8d1e-61391bcb8a78.png) *Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal*
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah **git --version.**  Saya memakai versi 2.38.0.windows.1

  ![2022-10-14](https://user-images.githubusercontent.com/115678251/196099524-5070c9e0-241d-4a75-a454-bdcc6cfe0474.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### _Cara membuat akun git_
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut *http://github.com*

![2022-10-17 (1)](https://user-images.githubusercontent.com/115678251/196099586-9031f90c-b7e7-49bc-9bae-a7f7614994e7.png)


- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### _Membuat repositori baru_

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git
![2022-10-17](https://user-images.githubusercontent.com/115678251/196100057-114397ce-5bcf-48af-8039-93713e9934db.png)


- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

 ![2022-10-17 (3)](https://user-images.githubusercontent.com/115678251/196100274-22e1ce62-e186-4423-9217-f8ca28367cc9.png)


-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
![2022-10-17 (4)](https://user-images.githubusercontent.com/115678251/196100470-b109db46-403a-42db-9b0b-3fc36c2ac10b.png)


### _Membuat Repository Local_

- Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih **Git Bash here** .
![2022-10-17 (5)](https://user-images.githubusercontent.com/115678251/196100698-7de8bd79-37b2-4f58-ade1-5061bb66c9d7.png)



- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      **$ git config --global user.email “nama_user”**
      **$ git config --global user.name “nama_user”**
![2022-10-14 (2)](https://user-images.githubusercontent.com/115678251/196101093-2c28c068-f757-4eeb-951b-aab19cd7ab56.png)

 


- Buatlah direktori baru dengan menggunakan perintah *" mkdir lab_pemrograman1 "*  LALU *" cd lab_pemrograman1 ![2022-10-14](https://user-images.githubusercontent.com/115678251/196101264-8b6704b3-b27e-405b-96d4-6e5e86422ef1.png)

 "*.

 ##### _Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local_ 

- Lalu jalankan perintah *git init* untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
  ![2022-10-14](https://user-images.githubusercontent.com/115678251/196101644-235961cc-c076-49f5-aa79-f06a5d5d8305.png)



-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

   ![2022-10-14 (5)](https://user-images.githubusercontent.com/115678251/196101778-83f6c99f-7947-4bd9-bf51-f4862a0f5fdf.png)

 ##### _Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah *git add*. Dengan perintah _$ git add README.md_. Kalau ingin melihat infonya ketik perintah _git status_.
- ![2022-10-14 (1)](https://user-images.githubusercontent.com/115678251/196102261-03151e0a-ba0b-482d-b17d-de468cdeb00a.png)



- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah _git commit -m “komentar commit"_
  ![2022-10-14 (3)](https://user-images.githubusercontent.com/115678251/196102526-dfb9dc7a-6893-4d01-bd04-3e6c778e81be.png)


##### **File berhasil tersimpan**

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### _Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)_

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/Bayuayassy/tugas3.git
   ![2022-10-14 (3)](https://user-images.githubusercontent.com/115678251/196102737-7035178b-4097-4747-aa60-4fa69af7ceb3.png)



 ##### _Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository_

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
   ![2022-10-14 (5)](https://user-images.githubusercontent.com/115678251/196102932-b5896579-9ae1-4681-ada3-80cc08033e9b.png)


 ##### _Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever._

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/Bayuayassy/tugas3.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah _“ls -1"_
  ![2022-10-14 (5)](https://user-images.githubusercontent.com/115678251/196103050-010f3b4f-923f-4a44-bfd2-682bfa93b820.png)



-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  
#### **FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas**.
#Terimakasih#

 
