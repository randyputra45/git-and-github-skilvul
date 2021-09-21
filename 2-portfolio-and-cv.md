1. Membuat sebuah folder kosong dengan namamu sendiri. 
* **mkdir randy**
2. Membuat sebuah file dengan nama README.md, isi file tersebut dengan kalimat
"Halo perkenalkan aku halaman utama". 
* **echo -e "Halo perkenalkan aku halaman utama" >> README.md**
3. Insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan commit dengan pesan
"Inisialisasi Git Repository". 
* **git init .**
* **git add README.md**
* **git commit -m "Inisialisasi Git Repository"**
4. Buat branch baru dengan nama cv, hal ini berguna agar histori kita tidak tercampur. 
* **git branch cv**
5. Pindah branch kedalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat:
"Ini adalah file CV". 
* **git checkout cv**
* **echo -e "Ini adalah file CV" >> cv.txt**
6. Kemudian dokumentasikan menggunakan commit dengan pesan. 
* **git add .**
* **git commit -m "Inisialisasi CV"**
7. Tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan commit 
* **echo -e "Perusahaan 1: Toyota" >> cv.txt**
* **git add .**
* **git commit -m "Menambahkan perusahaan 1"**
* **echo -e "Perusahaan 2: Honda" >> cv.txt**
* **git add .**
* **git commit -m "Menambahkan perusahaan 1"**
* **echo -e "Perusahaan 3: Kawasaki" >> cv.txt**
* **git add .**
* **git commit -m "Menambahkan perusahaan 3"**
8. Kembali ke branch master 
* **git checkout master**
9. Ubah file README.md menjadi 
Halo perkenalkan aku halaman utama
Ini adalah update pertama pada branch master
jangan lupa untuk mendokumentasikannya menggunakan commit dengan pesan
"update master pertama"
* **echo -e "\nIni adalah update pertama pada branch master" >> README.md**
* **git add .**
* **git commit -m "Update master pertama"**
10. Gabungkan branch cv kedalam branch master menggunakan perintah git merge
* **git merge cv**
* **git log --graph**
11. Gabungkan branch cv kedalam branch master menggunakan perintah git merge
* **git remote add origin https://github.com/randyputra45/portfolio-and-cv.git**
* **git push -u origin master**