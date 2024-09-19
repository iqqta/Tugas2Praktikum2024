# Tugas Pertemuan 2

Fork dan clone repository ini, lalu jalankan perintah 
```
flutter pub get
```
Buatlah tampilan form yang berisi nama, nim, dan tahun lahir pada file `ui/form_data.dart`, lalu buatlah tampilan hasil dari input data tersebut pada file `ui/tampil_data.dart`

PENJELASAN

Di dalam halaman FormData, pengguna mengisi data melalui tiga buah TextField, yaitu untuk nama, nim, dan tahun. Setiap input ini dikendalikan oleh TextEditingController, yang menyimpan nilai input dari pengguna. Saat pengguna menekan tombol Simpan, data yang dimasukkan diambil dari controller menggunakan metode .text pada TextEditingController, dan untuk tahun inputnya diubah menjadi tipe integer dengan menggunakan int.parse().
Proses navigasi ke halaman berikutnya dilakukan menggunakan Navigator.of(context).push(), yang membuat transisi halaman baru melalui MaterialPageRoute. Pada saat ini, data yang telah diambil dari form, yaitu nama, nim, dan tahun, dilewatkan sebagai parameter ke halaman tujuan, yaitu halaman TampilData. Data tersebut dikirimkan melalui konstruktor dari kelas TampilData.

Buat tampilan semenarik mungkin untuk dilihat.


Nama : Argo Iqbal Suranata

NIM : H1D022057

Shift Baru: F

## Screenshot
(form.png)
(hasil.png)
