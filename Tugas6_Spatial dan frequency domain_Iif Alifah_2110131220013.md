Nama: Iif Alifah

NIM: 2110131220013

---

<p align = "center"><b>Spatial dan Frequency Domain</b></p>
<p align = "justify">
Berdasarkan ranah operasinya, metode untuk perbaikan kualitas citra dapat dikelompokkan menjadi dua kategori:

1. Image enhancement dalam ranah spasial
<p align = "justify">
Metode-metode image enhancement dalam ranah spasial dilakukan
dengan memanipulasi secara langsung pixel-pixel di dalam citra.

<p align = "justify">
Metode pemrosesan citra dalam ranah spasial dinyatakan sebagai:

g(x,y) = T [ f(x,y) ]

<p align = "justify">
T bisa beroperasi pada satu pixel, sekelompok pixel bertetangga, atau keseluruhan pixel di dalam citra.
Jadi, metode dalam ranah spasial dapat dilakukan pada aras titik (pixel), aras lokal, dan aras global. 

<p align = "center"><img src = "img/img10.png">

2. Image enhancement dalam ranah frekuensi
<p align = "justify">
Metode-metode image enhancement dalam ranah frekuensi
dilakukan dengan mengubah citra terlebih dahulu dari ranah spasial ke ranah frekuensi, baru kemudian memanipulasi nilai-nilai frekuensi tersebut.

<p align = "center"><img src = "img/img11.png">

---
<p align = "center"><b>Metode-Metode Spatial</b></p>

<p align = "justify">
Peningkatan mutu citra pada domain spatial terbagi menjadi:

1. Point Processing
<p align = "justify">
Cara paling mudah untuk melakukan peningkatan mutu pada domain spatial adalah dengan melakukan pemoresan yang hanya melibatkan satu piksel saja.

- Citra Negatif
<p align = "justify">
Untuk mengubah nilai grey level piksel input dengan:

Gbaru = 255 - Glama

Akan menghasilkan gambar seperti klise foto.
<p align = "center"><img src = "img/img12.png">

- Contrast Streching
<p align = "justify">
Untuk mengubah kontras dari suatu image dengan cara mengubah grey level piksel-piksel pada citra menurut fungsi s = T(r) tertentu 
<p align = "center"><img src = "img/img13.png">
<p align = "center"><img src = "img/img14.png">
<p align = "center"><img src = "img/img15.png">

- Histogram Equalization
<p align = "justify">
HIstogram processing mengubah bentuk histogram agar pemetaan gray level pada citra juga berubah
<p align = "center"><img src = "img/img16.png">
<p align = "center"><img src = "img/img19.png">

- Image Substraction
<p align = "justify">
Dilakukan jika kita ingin mengambil bagian tertentu saja dari citra.

<p align = "center"><img src = "img/img17.png">

- Image Averaging
<p align = "justify">
Dilakukan jika kita memiliki beberapa citra yang bergambar sama, namun semua citra memiliki noise(gangguan). Noise satu citra berbeda dengan citra lainnya atau tidak berkolerasi. Adapun cara memperbaikinya adalah dengan melakukan operasi rata- rata terhadap semua citra tersebut.
<p align = "center"><img src = "img/img18.png">

2. Mask Processing
<p align = "justify">
Jika pada point processing kita hanya melakukan operasi terhadap masing-masing piksel, maka pada mask processing kita melakukan operasi terhadap suatu jendela ketetanggan pada citra. Kemudia kita menerapkan suatu mask terhadap jendela tersebut. Mask sering juga disebut filter.

Contoh:
<p align= "justify">
Jendela ketetanggan 3 x 3, nilai piksel pada posisi x dipengaruhi oleh nilai 8 tetangganya.
<p align = "center"><img src = "img/img20.png">





