Nama: Iif Alifah

NIM : 2110131220013

---
Membuat algoritma deskriptif untuk patterning, dithering, histogram equalization dan bit plane slicing

**1. Algoritma Patterning**
- Menentukan banyak pola pattern, misal menggunakan matriks 3 x 3 maka pola patternnya ada 10.

- Menentukan range tiap pola dengan membagikan tingkat keabuan dengan banyak nya pola.

- Jika sudah akan di cocokan satu persatu nilai matriks dengan range pada pola nya

<br>

**2. Algoritma Dithering**
- Membandingkan tiap nilai matriks dengan nilai matriks yang ada pada threshold.

- Jika nilai matriks lebih besar dari dari threshold maka akan dirubah ke 225, dan jika thesholdnya yang lebih besar maka akan di rubah menjadi 0.

**3. Algoritma Histogram Equalization**
- Menjumlahkan nilai pixel

- Menormalisasikan jumlah pixel tadi dengan melakukan pembagian dengan jumlah keseluruhan pixelnya.

- Mengalikan normalisasi dengan banyaknya greylevel

- Terakhir menjumlahkan pixel yang memiliki greylevel yang sama. 

**4. Algoritma Bit Slicing**
- Menyimpan sebuah matriks

- Merubah nilai desimal pada matriks menjadi biner.

- Setelah itu tentukan bit rendah nya dengan mengambil nilai biner yang berada di sebelah kanan, misal 11101101 maka nilai bit rendah nya 1. Kemudian untuk menentukan bit tertinggi nya dengan mengambil nilai biner yang berada di sebelah kanan, dari contoh biner yang ada  berarti bt tertinggi nya 1