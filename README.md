Nama : Frans Putra Sianga
Nim  : 312210046
Kelas: TI.22.A
## Cara penginstalan GIT

  - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di *git-scm.com* .
  ![Screenshot (3)](https://user-images.githubusercontent.com/115677839/196096657-25f9b66a-089d-4231-9f4e-9083a9cbd9f6.png)

  Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah *git --version.*  Saya memakai versi 2.38.0.windows.1

![Screenshot (4)](https://user-images.githubusercontent.com/115677839/196096776-1921280c-fae1-42e1-ac2a-7dddf6bcfadb.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Cara membuat akun git
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut http://github.com

![Screenshot (5)](https://user-images.githubusercontent.com/115677839/196096958-4a97f262-8a06-4ed4-a686-df302ec39bd4.png)


- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### Membuat repositori baru

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![Screenshot (7)](https://user-images.githubusercontent.com/115677839/196097223-0a8398c1-b49f-4633-8a51-6c85c18804ca.png)


- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

![Screenshot (8)](https://user-images.githubusercontent.com/115677839/196097537-cd438618-cf8b-48f4-8095-b8c6deed1447.png)


-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

![Screenshot (9)](https://user-images.githubusercontent.com/115677839/196098443-2e52b51e-6689-4396-b913-2e51c24b5af9.png)


### Membuat Reposiory Local

- Lalu kita buka file explorer pilih dilocal downloads (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih *Git Bash here* .
![Screenshot (10)](https://user-images.githubusercontent.com/115677839/196099545-1e2829a1-f59b-447c-90a7-fec521725d26.png)



- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      *$ git config --global user.email “nama_user”*
      *$ git config --global user.name “nama_user”*

  ![Screenshot (11)](https://user-images.githubusercontent.com/115677839/196100175-af4cc83f-2831-49ff-90e2-7b934b967862.png)



- Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 "  LALU *" cd lab_pemrograman1!![Screenshot (13)](https://user-images.githubusercontent.com/115677839/196101974-c223ad3a-aa76-4791-b25a-a047f1eaea3f.png)

 "*.

 ##### Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local 

- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
  ![Screenshot (14)](https://user-images.githubusercontent.com/115677839/196102152-d98e5c7f-6b7b-452f-94fd-5d158f14e172.png)



-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

   ![Screenshot (15)](https://user-images.githubusercontent.com/115677839/196102564-1af9d46b-9ffb-434b-8898-b3c1a6e1aa9b.png)


 ##### Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.
 ![Screenshot (16)](https://user-images.githubusercontent.com/115677839/196103191-bf0a864c-ddfd-411e-8e11-aec17febe18e.png)



- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit"
  ![67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3](https://user-images.githubusercontent.com/115677959/195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75.png)

##### *File berhasil tersimpan*

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/namasayafrans/Latihan1.git
   ![WhatsApp Image 2022-10-17 at 13 25 55](https://user-images.githubusercontent.com/115677839/196104407-f40dd858-de75-4dd7-bbbd-72daac3ab291.jpeg)


 ##### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
  ![WhatsApp Image 2022-10-17 at 13 25 55](https://user-images.githubusercontent.com/115677839/196104531-4dcc5107-6a9d-4659-b49a-6181ede56206.jpeg)


 ##### Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/namasayafrans/Latihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1"
  ![WhatsApp Image 2022-10-17 at 13 25 55](https://user-images.githubusercontent.com/115677839/196104674-6df80109-4469-4773-8f11-6ebd721ba54b.jpeg)


-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  
#### *FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas*.

