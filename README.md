# Deteksi Plat Nomor Kendaraan Mobil

Sebuah program Machine Learning yang dapat mendeteksi plat nomor kendaraan mobil menggunakan Convolutional Neural Networks. Model dilatih menggunakan gambar alfanumerik untuk memprediksi setiap karakter yang terdapat pada plat nomor kendaraan.
<br>
Tahap yang dilakukan pada kode adalah sebagai berikut:
<br>
- Membuat model yang dapat memprediksi karakter alfanumerik dari suatu gambar menggunakan Convolutional Neural Network.
- Mengambil setiap karakter dari plat nomor dari gambar mobil menggunakan Image Processing.
- Setelah mengambil setiap karakter, model akan memprediksi setiap alfanumerik sehingga menghasilkan output string yang sesuai dengan plat nomor dari mobil pada gambar input.

Gambar kendaraan mobil yang akan kita prediksi adalah sebagai berikut:
<br>
![gambar mobil](./assets/images/img1.jpg)
<br>
Gambar akan dilakukan Image Processing sehingga mendapatkan gambar berikut:
<br>
![gambar plat nomor](./assets/images/Car-Plates-Char(Seperated).png)
<br>
Terakhir, akan dilakukan prediksi plat nomor kendaraan sehingga mengeluarkan string sebagai output:
<br>
AD1LZ
