# Ery Shandy
# 312010201

# # PENGGUNAAN GIT 


### APA ITU GIT ?
* Git adalah salah satu sistem pengontrol versi (Version ControlSystem) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
* Pengontrol versi bertugas mencatat setiap perubahan pada fileproyek yang dikerjakan oleh banyak orang maupun sendiri.
* Git dikenal juga dengan distributed revision control (VCS terdistribusi),artinya penyimpanan database Git tidak hanya berada dalam satutempat saja.


### INSTALASI GIT
* Download **Git**, buka website resminya Git `(git-scm.com)`.
* Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
* Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka **CMD** atau **PowerShell**, kemudian ketik perintah

``git --version``

![Untitled](https://user-images.githubusercontent.com/72916851/96330021-fd45f280-1006-11eb-95e9-5ccdde27ca86.png)

### Menambahkan Global Config
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi ``user.name dan user.email``
* konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.

* apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah `git commit`

* Config Global Repository

`$ git config --global user.name “nama_user"`

`$ git config --global user.email “nama_user”`

![Untitled 2](https://user-images.githubusercontent.com/72916851/96330363-4eef7c80-1009-11eb-8e18-d1fe4113ee57.png)

### Perintah Dasar Git

* `git init`, perintah untuk membuat repository local
* `git add`, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
* `git commit`, perintah untuk menyimpan perubahan kedalam database git.
* `git push -u origin master`, perintah untuk mengirim perubahan pada repository local menuju server repository.
* `git clone [url]`, perintah untuk membuat working directory yang diambil dari repositry sever.
* `git remote add origin [url]`, perintah untuk menambahkan remote server/reopsitory server pada local repositry ``(working directory)``
* `git pull`, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository


### Membuat Repository Local

* Buka direktory aktif, misal: **d:\labs_pemrograman1** (buka menggunakan Windows Explorer)
* klik kanan pada direktory aktif tersebut, dan pilih menu **Git Bash**, sehingga muncul git bash commad
* Buat direktory project praktikum pertama dengan nama **latihan1**
``$ mkdir latihan1
$ cd latihan1``
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah **cd** ``(change directory)``
* direktory aktif menjadi: **d:\labs_pemrograman1\latihan1


### Membuat Reposiory Local

* Jalankan perintah **git init**, untuk membuat repository local.
`$ git init`
* Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .**git**
* Pada direktori tersebut, semua perubahan pada `working directory` akan disimpan.


### Menambahkan File baru pada repository

* Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
* disini kita akan coba buat satu file bernama README.md (text file)
`$ echo “# Latihan 1” >> README.md`
* File **README.md** berhasil dibuat.


### Menambahkan File baru pada repository

* Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
`$ git add README.md`
* File **README.md** berhasil ditambahkan.

![ss 1](https://user-images.githubusercontent.com/72916851/96360211-d1427400-10cf-11eb-85bc-e7f4a44b12bc.png)


### `Commit` (Menyimpan perubahan ke database)

* Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
`$ git commit -m “File pertama saya”`
* Perubahan berhasil disimpan.

![ss 2](https://user-images.githubusercontent.com/72916851/96360241-1b2b5a00-10d0-11eb-9ee8-56a48e3f8eaf.png)


* Server reopsitory yang akan kita gunakan adalah (http://github.com)
* Anda harus membuat akun terlebih dahulu.
* Pada laman github, klik tombol start a project, atau
* Dari menu (icon +) klik New Repository

![Screenshot (1)](https://user-images.githubusercontent.com/72916851/96107073-cf3ea200-0e90-11eb-8622-43700ff53aa9.png)


### Membuat repository server

* Isi nama repositorynya, misal: labpy1.
* lalu klik tombol Create repository


### Menambahkan Remote Repository

* Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
* Untuk menambahkan remote repository server, gunakan perintah **git remote add origin [url]**
`$ git remote add origin https://github.com/rizkyy/LatihanVCS.git`


### Push (Mengirim perubahan ke server)

* Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
`$ git push -u origin master`
* Perintah ini akan meminta memasukkan username dan password pada akun github.com

![ss 1](https://user-images.githubusercontent.com/72916851/96360211-d1427400-10cf-11eb-85bc-e7f4a44b12bc.png)


### Melihat hasilnya pada server repository

* Buka laman github.com, arahkan pada repositorinya.
* Maka perubahan akan terlihat pada laman tersebut.

![Screenshot (2)](https://user-images.githubusercontent.com/72916851/96107438-47a56300-0e91-11eb-8c41-a9ab0ad95eb4.png)


### Clone Repository

* Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
* Untuk melakukan cloning, gunakan perintah `git clone [url]`

![ss 3](https://user-images.githubusercontent.com/72916851/96360292-b1f81680-10d0-11eb-839d-469a16f01ce5.png)

### Kegunaan file README.md

* Apabila kita menggunakan github, untuk memberikan penjelasan awal pada project yang kita buat, maka dapat menggunakan sebuah file yang bernama README.md
* Pada file tersebut kita dapat membuat dokumentasi awal dari setiap project yang kita buat untuk memberikan penjelasan atau sekedar cara penggunaan dari aplikasi yang kita kembangkan.
* Penulisan file README.md berbasis teks, dan untuk pemformatannya menggunakan Markdown format.
* untuk lebih jelasnya, dapat anda pelajari cara penggunaan markdown pada url berikut: https://guides.github.com/features/mastering-markdown/



#### Made In By Ery Shandy

