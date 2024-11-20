# Praktikum5
## Nama : Althaf Afif Faiz
## Nim : 312410404
## Kelas : TI.24.A.3

# Rincian Program :

Buat program sederhana yang akan menampilkan daftar nilai
mahasiswa, dengan ketentuan

• Program dibuat dengan menggunakan Dictionary

• Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data,
Tampilkan Data, Cari Data)

• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
uts: 35%, uas: 35%)

# Tampilan code program 
![code project5](https://github.com/user-attachments/assets/b62b533a-c13c-45b4-ada6-a55a5cee25cc)

# Struktur Program

## Fungsi hitung_nilai_akhir(tugas, uts, uas):
```
Fungsi ini digunakan untuk menghitung nilai akhir mahasiswa berdasarkan komponen nilai yang diberikan: nilai tugas,
UTS (Ujian Tengah Semester), dan UAS (Ujian Akhir Semester).

Bobot nilai untuk masing-masing komponen adalah:

Tugas: 30%

UTS: 35%

UAS: 35%

Fungsi ini mengembalikan nilai akhir yang dihitung.
```
## Fungsi tampilkan_menu():
```
Fungsi ini menampilkan menu pilihan kepada pengguna. Menu ini berisi opsi untuk menambah, mengubah, menghapus, menampilkan, dan mencari data mahasiswa.
Fungsi tambah_data(mahasiswa):

Fungsi ini digunakan untuk menambahkan data mahasiswa baru ke dalam dictionary mahasiswa.

Pengguna diminta untuk memasukkan NIM, nama, dan nilai untuk tugas, UTS, dan UAS.

Jika NIM sudah ada dalam dictionary, program akan memberi tahu pengguna bahwa data sudah ada.

Setelah memasukkan semua data, nilai akhir dihitung menggunakan fungsi hitung_nilai_akhir dan data mahasiswa disimpan dalam dictionary.
```
## Fungsi ubah_data(mahasiswa):
```
Fungsi ini memungkinkan pengguna untuk mengubah data mahasiswa yang sudah ada.

Pengguna diminta untuk memasukkan NIM mahasiswa yang ingin diubah.

Jika NIM ditemukan, pengguna akan diminta untuk memasukkan data baru (nama, nilai tugas, UTS, dan UAS).

Nilai akhir dihitung kembali dan data mahasiswa diperbarui dalam dictionary.
```
## Fungsi hapus_data(mahasiswa):
```
Fungsi ini digunakan untuk menghapus data mahasiswa berdasarkan NIM yang dimasukkan oleh pengguna.

Jika NIM ditemukan dalam dictionary, data tersebut akan dihapus.
```
## Fungsi tampilkan_data(mahasiswa):
```
Fungsi ini menampilkan semua data mahasiswa yang tersimpan dalam dictionary.

Jika tidak ada data, program akan memberi tahu pengguna bahwa tidak ada data mahasiswa.
```
## Fungsi cari_data(mahasiswa):
```
Fungsi ini memungkinkan pengguna untuk mencari data mahasiswa berdasarkan NIM.

Jika NIM ditemukan, data mahasiswa akan ditampilkan. Jika tidak, program akan memberi tahu bahwa data tidak ditemukan.
```
## Fungsi main():
```
Fungsi ini adalah titik awal program.

Sebuah dictionary kosong mahasiswa dibuat untuk menyimpan data mahasiswa.

Program akan terus menampilkan menu dan meminta input dari pengguna sampai pengguna memilih untuk keluar (pilihan 6).

Berdasarkan pilihan pengguna, fungsi yang sesuai akan dipanggil untuk melakukan operasi yang diinginkan.
```
# Hasil dari code program 

## Menahbahkan Data Pada Program
![Tambah data(1)](https://github.com/user-attachments/assets/4bcd9660-6fa9-489a-8038-d018b3c0c640)
![Tambah data(2)](https://github.com/user-attachments/assets/d571d1af-60c6-4db2-85fe-cfdb15f353d6)

### Penjelasan Singkat 
```
Pengguna diminta untuk menambahkan data yang ingin ditambahkan dengan memilih pilihan nomor 1.
Jika pengguna memiliki data lebih dari 1 maka pengguna bisa memilih pilihan nomor 1 juga.
Pengguna dapat mengecek data yang dimasukan dengan memilih pilihan nomor 4 untuk memunculkan data.
```
## Mengubah Data Pada Program
![Ubah data](https://github.com/user-attachments/assets/909f5f3c-81ce-4aa8-b262-b9c9b5dcb5a5)

### Penjelasan Singkat
```
Pengguna juga dapat merubah data yang sudah dimasukan tadi dengan memilih pilihan nomor 2.
```
## Menghapus Data Pada Program
![Hapus data](https://github.com/user-attachments/assets/3858f1a5-7aea-4103-89c3-e21168ce6c8b)

### Penjelasan Singkat
```
Pengguna juga bisa menghapus data yang sudah dimasukan dengan menginput nim yang ingin dihapus datanya.
```
## Mencari Data Pada Program dan Selesai
![Cari data](https://github.com/user-attachments/assets/516aec5a-259b-4dad-9c9a-612a4b4bc057)

### Penjelasan Singkat
```
Pengguna juga bisa mencari data tidak perlu mencari satu persatu dari data yang sudah di masukan tetapi
pengguna hanya memilih pilihan nomor 5 dan masukan nim dari data yang akan dicari.

Jika pengguna sudah selesai dengan program bisa memilih nomor 6 untuk keluar dari program
```

## Flowchart Program





