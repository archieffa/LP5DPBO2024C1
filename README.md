# JANJI

Saya Syifa Azzahra dengan NIM 2207308 mengerjakan soal Latihan 5 dalam mata kuliah
Desain Pemrograman Berorientasi Objek untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah
dispesifikasikan. Aamiin.

# DESKRIPSI TUGAS

1. Ketik ulang code untuk **melengkapi** file **Menu.java**.
2. Tambahkan satu **atribut** baru di class Mahasiswa sekaligus **component** input-nya di form. (Usahakan setiap orang atribut barunya berbeda)
3. Tambah **confirmation prompt** sebelum **delete**.
4. BONUS (+20) Jika component baru yang ditambahkan **bukan JTextField** (Component baru berupa JComboBox, JSlider, JRadioButton, dsb).

# DESAIN KODE PROGRAM

Program ini menggunakan dua kelas yaitu kelas Mahasiswa dan kelas Menu.

1. Kelas Mahasiswa
    
    Kelas ini memiliki empat atribut, yaitu:
    
    - nim: menyimpan nim dalam bentuk string
    - nama: menyimpan nama dalam bentuk string
    - jenisKelamin: menyimpan jenis kelamin dalam bentuk string
    - fakultas: menyimpan fakultas dalam bentuk string
    
    Masing-masing atribut memiliki setter dan getter.
    
2. Kelas Menu
    
    Kelas ini memiliki enam method, yaitu:
    
    - setTable(): mengatur tabel yang ditampilkan (public final DefaultTableModel)
    - insertData(): menambah data mahasiswa (public void)
    - updateData(): mengubah data mahasiswa yang dipilih user (public void)
    - deleteData(): menghapus data mahasiswa yang dipilih user (public void)
    - clearForm(): mengosongkan input pada form setelah melakukan insert/update/delete (public void)
    - populateList(): menampilkan semua data mahasiswa (private void)

# DESAIN GUI
![desain](https://github.com/archieffa/LP5DPBO2024C1/assets/121290445/f41a130d-132f-491b-bff9-f3419d517a3b)


# ALUR PROGRAM

Program ini memiliki component NIM dan Nama berupa JTextField serta component Jenis Kelamin dan Fakultas berupa JComboBox. Selain itu ada empat button yaitu Add, Update, Delete dan Cancel. Alur programnya adalah sebagai berikut:

- User dapat menambahkan data dengan mengisi NIM dan nama serta memilih jenis kelamin dan fakultas, lalu klik Add. Data otomatis masuk ke dalam tabel.
- User dapat mengubah data dengan memilih data yang ingin diubah. Setelah ubah data, klik Update. Data yang dipilih tadi otomatis berubah.
- User dapat menghapus data dengan memilih data yang ingin dihapus, lalu klik Delete. Akan ada tampilan berupa konfirmasi apakah user benar-benar ingin menghapus data tersebut, jika iya maka klik ‘Yes’. Data yang dipilih tadi otomatis terhapus.

# DOKUMENTASI
## ALUR PROGRAM

https://github.com/archieffa/LP5DPBO2024C1/assets/121290445/912f4b1a-c295-4bd5-9bf9-12d4860aac8f


## ADD
![add](https://github.com/archieffa/LP5DPBO2024C1/assets/121290445/60231efe-647d-4be2-934a-e58fed01c30a)

## UPDATE
![update](https://github.com/archieffa/LP5DPBO2024C1/assets/121290445/58093191-3976-431b-9b47-22552078b6f6)

## DELETE
![delete1](https://github.com/archieffa/LP5DPBO2024C1/assets/121290445/37cb8f0d-60ab-4cda-b384-48d1ed5882a3)
![delete2](https://github.com/archieffa/LP5DPBO2024C1/assets/121290445/b31688f4-6e59-4c46-8a63-1cd16d0b92aa)


