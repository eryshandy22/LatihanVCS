# LatihanVCS
**Nama	: Ery Shandy**

**Nim	: 312010201**

**Kelas	: TI.20.A2**
 
1. Langkah pertama membuat folder **latihan1** , saya membuat folder nya di desktop
2. Klik kanan pada Folder yang sudah di buat tadi lalu klik terminal lalu akan muncul seperti gambar di bawah ini:


3. Kemudian buatlah folder dengan mengetik di terminal dengan perintah `mkdir latihan1`
<img width="320" alt="ss 1" src="https://user-images.githubusercontent.com/73053784/96430920-00222c80-122d-11eb-8059-f49fd3821c41.png">


dan nantinya di folder **latihan1** dan didalam nya akan ada folder baru dengan tulisan seperti yang tadi kita ketik di terminal yaitu **latihan1**

4.  Langkah selanjut nya masuk kedalam folder **latihan1** dengan mengetik `cd latihan1`

<img width="322" alt="ss 2" src="https://user-images.githubusercontent.com/73053784/96431062-352e7f00-122d-11eb-8b76-7df25d26d05c.png">
5. Dan buatlah Folder tersebut menjadi repo (repository) dengan cara **git init** jika benar akan seperti gambar di bawah ini:
<img width="479" alt="ss 3" src="https://user-images.githubusercontent.com/73053784/96431165-54c5a780-122d-11eb-9f8f-2fa6db641ace.png">

jika sudah seperti ini artinya folder sudah menjadi repo.

6. Setelah itu buat file README.md dengan mengetik `echo "latihan 1" >> README.md`

<img width="458" alt="ss 4" src="https://user-images.githubusercontent.com/73053784/96431292-80e12880-122d-11eb-8550-745665362e4a.png">

7. Sekarang kita ketik perintah `ls -l` dan penampilan akan seperti ini
<img width="448" alt="ss 5" src="https://user-images.githubusercontent.com/73053784/96431356-97877f80-122d-11eb-98cf-3e4b7ee22c79.png">

8. di lanjutkan dengan mengetik `git add README.md`

<img width="448" alt="ss 6" src="https://user-images.githubusercontent.com/73053784/96431490-c6055a80-122d-11eb-8d3a-9c126278a145.png">

9. Cara mengecek file tersebut ketik `git status` maka akan muncul sebagai berikut.

<img width="382" alt="ss 7" src="https://user-images.githubusercontent.com/73053784/96431921-68bdd900-122e-11eb-9e1c-41868e93f74e.png">

10. Langkah selanjutnya commit file tersebut `git commit -m “pesan”`

<img width="401" alt="ss 8" src="https://user-images.githubusercontent.com/73053784/96432034-88ed9800-122e-11eb-894a-3684b7e4781b.png">

jika tidak ada masalah maka akan seperti gambar di atas.

11. langkah selanjutnya buat lah akun di github (http://github.com)
12. Jika sudah memiliki akun buat lah repository baru **New Repository**
![Screenshot (3)](https://user-images.githubusercontent.com/73053784/96432191-bdf9ea80-122e-11eb-917c-5a24a25bb65e.png)

13. Langkah selanjutnya mengisi repository nya

![SS  (2)](https://user-images.githubusercontent.com/73053784/96432349-f39ed380-122e-11eb-9f70-a38ec5d5fc64.png)

- **isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesui keperluan.**

- **untuk description / pesan buat lah sejelas mungkin.**

- **pilih lah public**

- **lalu create repository**

14. Maka akan muncul seperti gambar berikut

![Screenshot (5)](https://user-images.githubusercontent.com/73053784/96432721-36f94200-122f-11eb-8eba-0a4b125fd58e.png)

copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/ laptot.

15. Lalu buka lah **terminal** Cara menghubungkan nya dengan mengetik git remote add origin <link> 
<img width="436" alt="ss 9" src="https://user-images.githubusercontent.com/73053784/96433515-6ad46780-122f-11eb-80f0-d99ebe48fa00.png">

15. Langkah selanjutnya ketik `git push -u origin master` lalu masukan username GITHUB dan password 

<img width="438" alt="ss 10" src="https://user-images.githubusercontent.com/73053784/96434533-ab33e580-122f-11eb-8fa0-e9d8a6bb568c.png">

16. Bila tidak ada kesalahan akan seperti gambar di bawah ini

<img width="519" alt="ss 11" src="https://user-images.githubusercontent.com/73053784/96435387-e33b2880-122f-11eb-8ad6-9b48692b3671.png">

# pengertian

- `mkdir <nama file>` untuk membuat file baru

- `git init` untuk membuat depository local

- `git add` untuk menambah kan file baru

- `git status` untuk mengecek apakah ada perubahan di dalam file

- `git commit` untuk menyimpan perubahan kedalam database git.

- `git remote` untuk menghubungka file ke github

- `git push` untuk meng upload file ke github
