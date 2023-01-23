# 24 Puzzel : Card Game
> Tugas Kecil 1 IF2211 Strategi Algoritma Semester II tahun 2022/2023
> Penyelesaian Permainan Kartu 24 dengan Algoritma Brute Force

## Table of Contents
* [Description](#Description)
* [Technologies Used](#Technologies-Used)
* [Setup](#Setup)
* [How to Run](#How-to-Run)
* [Author](#contributors)
<!-- * [Acknowledgements](#acknowledgements) -->

<!-- Adreas Bara Timur -->
## Description
### 24CardGame
Permainan Kartu 24 adalah sebuah permainan teka-teki yang bertujuan untuk menghasilkan angka 24 dari 4 buah angka acak (pada Program ini menggunakan rentang angka kartu remi) dengan aritmatika sederhana.

Pemain Kartu 24 harus menemukan cara untuk untuk menemukan 24 hanya dengan aritmatika tambah, kurang, kali, bagi ("+, -, x, /") dan dapat menggunakan tanda kurung "()"
### Brute Force Algorithm
Alur program ini adalah
1.	Pilih 4 kartu, misal a b c d 
2.	Sesuai angka, tentukan bentuk atau peletakan tanda kurung  
3.	Sesuai tanda kurung tersebut, lakukan permutasi dari 4 buah operasi, ”+-*/”, pilih 3 buah untuk diletakan diantara a b c d.
4.	Lakuukan operasi sesuai permutasi yang telah terbentuk. Jika membentuk angkaa 24 maka menjadi hasil. (opsional) simpan urutan angka pada sebuah larik
5.	Ulangi langkah 2-4 dengan melakukan permutasi pada susunan angka a b c d. (opsional) lakukan pengecekkan apakah  urutan empat angka sudah terjadi atau belum; jika belum maka lanjut, jika sudah maka cari urutan lain

## Technologies Used
- C++17
### Library c++ used
1.	iostream
2.	vector
3.	sstream
4.	istream
5.	fstream
6.	cstdlib
7.	chrono

## Setup
### Prerequisite
- Compiler g++ atau yang sejenis
### Instalation
Pada Powershell / termninal, tentukan folder yang akan ditempati
```PowerShell
git clone https://github.com/akmaldika/Tucil1_IF2211_24CardGame.git
```
## How to Run
1. Buka terminal
2. pastika folder sedang berada di dalam Tucil1_IF2211_24CardGame (jika belum di rename)
3. Ketikkan
```PowerShell
./Game24Card.bat
```

## Author
13521050 [Akmal Mahardika Nurwahyu Pratama](https://github.com/akmaldika)