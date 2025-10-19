# Penggunaan Git

<img width="1148" height="874" alt="Image" src="https://github.com/user-attachments/assets/f43b8ee3-85e8-4ad5-ad43-a4d3a37f14c9" />

## Git sebagai salah satu DVCS (Distributed Version Control System)
Git digunakan sebagai tempat untuk menyimpan dan merekam history dari program yang telah dibuat. Semua perubahan dapat terlihat ketika menggunakan git. Program tersebut akan di simpan kedalam repository git atau istilah nya adalah commit dimana jika dilakukan perubahan sebanyak apapun versi aslinya tidak akan hilang. 

Tentunya pada mulanya perlu menginstall Git kemudian melakukan konfigurasi antara git dengan akun github yang telah dibuat dengan menulis perintah git config ```git config --global user.name " "``` dan  ```git config --global user.email " "``` dalam Git Bush. Sekarang, ini lah langkah membuat Repository dan mengguggah ke GitHub via Git Bash:
1. ```git -v``` untuk memastikan bahwa Git sudah terpasang.
2. ```cd /``` cd _(change directory)_ untuk menavigasi berkas dan berpindah ke folder membuat project.
3. ```echo "# latihanVCS" >> README.md``` untuk membuat file baru tipe README.md dan menulis teks #latihanVCS ke dalamnya.
4. ```git init``` untuk membuat sebuah direktori bernama .git di dalam project.
5. ```git add .``` untuk menambahkan setiap perubahan pada file masuk ke dalam staging area.
6. ```git commit -M``` untuk menyimpan segala perubahan di dalam local.
7. ```git branch -M main``` untuk mengelola cabang di dalam repositori.
8. ```git remote add origin``` untuk menambahkan remote repositori dan sebagai nama default alamat GitHub.
9. ```git push -u origin main``` untuk mengunggah segala perubahan pada projek local ke repositori server (GitHub) dengan tanda `-u` karena baru pertama kali menguggah project tersebut.

Semua langkah diatas menunjukkan bagaimana Git digunakan untuk membuat repository, mencatat perubahan hingga mengunggahnya ke GitHub. Dengan menguasai alur ini pengeleloaan kode akan menjadi lebih terorganisir.
