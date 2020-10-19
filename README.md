# LatihanVCS
**Nama	: Ery Shandy**

**Nim	: 312010201**

**Kelas	: TI.20.A2**
 
1. Langkah pertama membuat folder **latihan1** , saya membuat folder nya di desktop
2. Klik kanan pada Folder yang sudah di buat tadi lalu klik terminal lalu akan muncul seperti gambar di bawah ini:

![1](https://user-images.githubusercontent.com/69299625/96339603-fcbd6280-10bf-11eb-853b-87fb3e3381be.jpg)

3. Kemudian buatlah folder dengan mengetik di terminal dengan perintah `mkdir latihan1`

![2](https://user-images.githubusercontent.com/69299625/96339747-a8ff4900-10c0-11eb-92f3-00339d5d1d09.png)

dan nantinya di folder **latihan1** dan didalam nya akan ada folder baru dengan tulisan seperti yang tadi kita ketik di terminal yaitu **latihan1**

4.  Langkah selanjut nya masuk kedalam folder **latihan1** dengan mengetik `cd latihan1`

![3](https://user-images.githubusercontent.com/69299625/96339878-7bff6600-10c1-11eb-8c40-87aa8b7d17b4.png)

5. Dan buatlah Folder tersebut menjadi repo (repository) dengan cara **git init** jika benar akan seperti gambar di bawah ini:

![4](https://user-images.githubusercontent.com/69299625/96339933-def0fd00-10c1-11eb-80fe-1a70bbcadbeb.png)

jika sudah seperti ini artinya folder sudah menjadi repo.

6. Setelah itu buat file README.md dengan mengetik `echo "latihan 1" >> README.md`

![5](https://user-images.githubusercontent.com/69299625/96345070-9129c400-10c4-11eb-8ca7-c5c9cf4d97df.png)

7. Sekarang kita ketik perintah `ls -l` dan penampilan akan seperti ini

![6](https://user-images.githubusercontent.com/69299625/96346295-1b722800-10c5-11eb-914c-39dcbd13fd89.png)

8. di lanjutkan dengan mengetik `git add README.md`

![7](https://user-images.githubusercontent.com/69299625/96346478-3729fe00-10c6-11eb-9316-15cf3cf837d1.png)

9. Cara mengecek file tersebut ketik `git status` maka akan muncul sebagai berikut.

![8](https://user-images.githubusercontent.com/69299625/96346638-1615dd00-10c7-11eb-92f4-613003760dfc.png)

10. Langkah selanjutnya commit file tersebut `git commit -m “pesan”`

![9](https://user-images.githubusercontent.com/69299625/96347040-3e9ed680-10c9-11eb-8cbc-3f550ebf960a.png)

jika tidak ada masalah maka akan seperti gambar di atas.

11. langkah selanjutnya buat lah akun di github (http://github.com)
12. Jika sudah memiliki akun buat lah repository baru **New Repository**

![10](https://user-images.githubusercontent.com/69299625/96347130-b40aa700-10c9-11eb-974f-2a7331b922c2.png)

13. Langkah selanjutnya mengisi repository nya

![11](https://user-images.githubusercontent.com/69299625/96347181-36936680-10ca-11eb-92bf-901bea2f23c3.png)

- **isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesui keperluan.**

- **untuk description / pesan buat lah sejelas mungkin.**

- **pilih lah public**

- **lalu create repository**

14. Maka akan muncul seperti gambar berikut

![12](https://user-images.githubusercontent.com/69299625/96354983-00280c80-1107-11eb-8527-a6ca5f944c44.png)

copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/ laptot.

15. Lalu buka lah **terminal** Cara menghubungkan nya dengan mengetik git remote add origin <link> 

![13](https://user-images.githubusercontent.com/69299625/96355079-ecc97100-1107-11eb-9976-b86fefdeca2e.png)

15. Langkah selanjutnya ketik `git push -u origin master` lalu masukan username GITHUB dan password 

![15](https://user-images.githubusercontent.com/69299625/96355122-65c8c880-1108-11eb-9e2c-a487ef432b4b.png)

16. Bila tidak ada kesalahan akan seperti gambar di bawah ini

![16](https://user-images.githubusercontent.com/69299625/96355166-dc65c600-1108-11eb-8aa2-7c5a0bcf1a9d.png)

# pengertia 

- `mkdir <nama file>` untuk membuat file baru

- `git init` untuk membuat depository local

- `git add` untuk menambah kan file baru

- `git status` untuk mengecek apakah ada perubahan di dalam file

- `git commit` untuk menyimpan perubahan kedalam database git.

- `git remote` untuk menghubungka file ke github

- `git push` untuk meng upload file ke github
