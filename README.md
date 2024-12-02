# Praktikum-7

    Nama: Burhan Isnain Nur Huda
    NIM: 312410226
    Kelas: TI.24.A.2
    Mata Kuliah: Bahasa Pemograman

# Flowchart 


# Tugas Praktikum 
Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah 

class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:

• Method tambah() untuk menambah data

• Method tampilkan() untuk menampilkan data

• Method hapus(nama) untuk menghapus data berdasarkan nama

• Method ubah(nama) untuk mengubah data berdasarkan nama

• Buat diagram class, flowchart dan penjelasan programnya pada 

README.md.

• Commit dan push repository ke github.

# Python Code 
![IMG_20241202_132325](https://github.com/user-attachments/assets/c368720c-fb56-4177-bca5-f15466244c05)
![IMG_20241202_132432](https://github.com/user-attachments/assets/98cdf578-8ba5-4905-a8df-ef598b36244a)


# Penjelasan Program 

1. Class

       `DaftarNilaiMahasiswa`

- Class ini berfungsi untuk menyimpan dan mengelola data mahasiswa, termasuk nama dan nilai mereka.

-Menggunakan dictionary `self.mahasiswa` untuk menyimpan data mahasiswa, di mana nama mahasiswa menjadi key dan nilai menjadi value.

2. Method
 
        __init__

- Merupakan constructor yang menginisialisasi dictionary kosong `self.mahasiswa`.

3. Method tambah

       `(nama, nilai)`

- Menambahkan data mahasiswa ke dalam dictionary. Jika nama mahasiswa sudah ada, nilai yang baru akan menggantikan nilai yang lama.

4. Method

       `tampilkan()`

- Menampilkan semua data mahasiswa. Jika tidak ada data, akan menampilkan pesan bahwa tidak ada data mahasiswa.

5. Method

       `hapus(nama)`

- Menghapus data mahasiswa berdasarkan nama. Jika nama tidak ditemukan, akan menampilkan pesan bahwa data tidak ditemukan.

6. Method ubah

       `(nama, nilai_baru)`

- Mengubah nilai mahasiswa berdasarkan nama. Jika nama tidak ditemukan, akan menampilkan pesan bahwa data tidak ditemukan.

# Contoh Penggunaan

- Program ini dimulai dengan membuat instance dari class `DaftarNilaiMahasiswa`.
- Data mahasiswa ditambahkan, ditampilkan, diubah, dan dihapus sesuai dengan metode yang telah didefinisikan.
# Input & Output 
