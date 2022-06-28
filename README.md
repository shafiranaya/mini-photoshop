# mini-photoshop

## Latar Belakang
Saat ini, terdapat berbagai macam aplikasi yang dapat digunakan untuk melakukan photo editing. Beberapa contoh aplikasi yang mungkin kamu ketahui adalah Adobe Photoshop, Adobe Lightroom, Picsart, Snapseed, VSCO, dan lain lain. Apakah kamu tahu bahwa beberapa fitur editing yang ada apa aplikasi tersebut dapat dilakukan dengan melakukan pemrosesan matriks seperti yang sudah kamu pelajari pada mata kuliah Aljabar Linier dan Geometri?

![Latar Belakang](./images/ms0.png)

## Spesifikasi Wajib
### Umum
1. Aplikasi dibuat dalam bentuk website dan dibebaskan untuk menggunakan bahasa apapun. Framework yang digunakan untuk mengembangkan Frontend dan Backend dibebaskan, namun harus dilakukan pemisahan antara Frontend dengan Backend.
2. Pemrosesan gambar harus dilakukan dalam format matriks, tidak diperbolehkan dalam format gambar.
3. Diperbolehkan menggunakan library eksternal untuk utilitas operasi matriks, operasi matematika, serta backend/frontend, namun algoritma pengolahan citra harus dibuat from scratch.

### Cara Kerja Aplikasi
1. User dapat mengunggah sebuah gambar dan gambar tersebut akan ditampilkan pada layar
2. User dapat memilih berbagai operasi editing yang akan dilakukan pada gambar dari sidebar website. Menu-menu editing tersebut berbentuk icon seperti pada aplikasi Photoshop.
3. Apabila terdapat banyak operasi editing yang dilakukan pada gambar, maka gambar tersebut akan berubah sesuai operasi apa saja yang sudah diberikan
4. User dapat mengunduh hasil editing dari website
5. User dapat melakukan reset terhadap operasi editing yang sudah dilakukan pada gambar sehingga gambar dapat kembali seperti semula (sebelum diedit sama sekali)

## Milestone 1: Menu-menu Dasar (900 poin)

1. Membuat citra negatif
<p float="left">
  <img src="./images/ms1-1-1.png" width="25%" />
  <img src="./images/ms1-1-2.png" width="25%" />
</p>

2. Mengubah citra berwarna menjadi citra grayscale
<p float="left">
  <img src="./images/ms1-2-1.png" width="25%" />
  <img src="./images/ms1-2-2.png" width="25%" />
</p>

3. Operasi komplemen pada citra
<p float="left">
  <img src="./images/ms1-3-1.png" width="25%" />
  <img src="./images/ms1-3-2.png" width="25%" />
</p>

4. Operasi geometri (rotasi, flipping, zooming)

Fitur rotasi, flipping, dan zooming terbatas seperti pada aplikasi image processing biasanya
<p float="left">
  <img src="./images/ms1-4-1.png" width="25%" />
  <img src="./images/ms1-4-2.jpg" width="25%" />
  <img src="./images/ms1-4-3.jpg" width="25%" />
</p>

<p float="left">
  <img src="./images/ms1-4-1.png" width="25%" />
  <img src="./images/ms1-4-5.jpg" width="25%" />
  <img src="./images/ms1-4-6.jpg" width="25%" />
</p>

<p float="left">
  <img src="./images/ms1-4-1.png" width="25%" />
  <img src="./images/ms1-4-8.jpg" width="25%" />
</p>

Ekspektasi fungsionalitas untuk fitur ini adalah berdasarkan icon-icon di bawah ini:

Icon untuk melakukan rotasi:
<p float="left">
  <img src="./images/ms1-4-rotasi-1.png" width="2%" />
  <img src="./images/ms1-4-rotasi-2.png" width="2%" />
</p>

Icon untuk melakukan flipping:  
<p float="left">
  <img src="./images/ms1-4-flip1.png" width="2%" />
  <img src="./images/ms1-4-flip-2.png" width="2%" />
</p>

Icon untuk melakukan zooming: 
<p float="left">
  <img src="./images/ms1-4-zoom-1.png" width="2%" />
  <img src="./images/ms1-4-zoom-2.png" width="2%" />
</p>

## Milestone 2: Image Enhancement (1400 poin)

1. Image brightening
<p float="left">
  <img src="./images/ms2-1-1.png" width="25%" />
  <img src="./images/ms2-1-2.png" width="25%" />
</p>

2. Contrast stretching 
<p float="left">
  <img src="./images/ms2-2-1.png" width="25%" />
  <img src="./images/ms2-2-2.png" width="25%" />
</p>

3. Tranformasi log dan transformasi pangkat
<p float="left">
  <img src="./images/ms2-3.png" width="50%" />
</p>

## Milestone 3 (1800 poin)
1. Image blurring dengan teknik Gaussian Filter
<p float="left">
  <img src="./images/ms3-1-1.png" width="25%" />
  <img src="./images/ms3-1-2.png" width="25%" />
</p>

2. Penajaman citra (image sharpening) dengan Gaussian Highpass Filter
<p float="left">
  <img src="./images/ms3-2-1.png" width="25%" />
  <img src="./images/ms3-2-2.png" width="25%" />
</p>

3. Membuat efek noisy/grainy dengan Gaussian noise
<p float="left">
  <img src="./images/ms3-3.png" width="50%" />
</p>

## Bonus (500 poin)
Menambahkan fungsionalitas berikut pada website:
- User dapat melakukan undo/redo terhadap operasi editing yang sudah dilakukan.

## Readme (400 poin)
Readme minimal berisi:
- Cara penggunaan program
- Penjelasan singkat mengenai cara kerja setiap fitur.
- Referensi, framework, dan library yang membantu kalian dalam mengerjakan tugas ini beserta alasan penggunaannya.

## Pengerjaan dan Pengumpulan
- Buat repository pada Github kalian masing-masing dan invite rahmahkn dan shafiranaya ke dalam repository tersebut.
- Struktur repository terdiri atas:
  - folder frontend
  - folder backend
  - folder test, yaitu folder yang berisi contoh masukan dan keluaran gambar yang digunakan saat demo. Gambar disimpan dengan format penamaan: <No. Milestone_No. Fitur_Before/After>.
- Repository tersebut juga wajib dilengkapi readme sesuai ketentuan yang telah disebutkan di atas.
- Penilaian Tugas dilakukan dengan melakukan demo secara langsung menggunakan Google Meet dengan terlebih dahulu menghubungi salah satu asisten untuk penjadwalan demo (line: shafr atau rahmakhrs).
- Bila ada pertanyaan, silakan bertanya langsung ke asisten via LINE Group GAPADAT-K agar dapat dicermati oleh seluruh calon asisten.

## Tips
Berikut referensi yang dapat digunakan untuk pembuatan tugas ini

https://informatika.stei.itb.ac.id/~rinaldi.munir/Citra/2021-2022/citra21-22.htm 
