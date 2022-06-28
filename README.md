# mini-photoshop

## Latar Belakang
Saat ini, terdapat berbagai macam aplikasi yang dapat digunakan untuk melakukan photo editing. Beberapa contoh aplikasi yang mungkin kamu ketahui adalah Adobe Photoshop, Adobe Lightroom, Picsart, Snapseed, VSCO, dan lain lain. Apakah kamu tahu bahwa beberapa fitur editing yang ada apa aplikasi tersebut dapat dilakukan dengan melakukan pemrosesan matriks seperti yang sudah kamu pelajari pada mata kuliah Aljabar Linier dan Geometri?

## Spesifikasi Wajib
### Umum
Aplikasi dibuat dalam bentuk website dan dibebaskan untuk menggunakan bahasa apapun. Framework yang digunakan untuk mengembangkan Frontend dan Backend dibebaskan, namun harus dilakukan pemisahan antara Frontend dengan Backend.
Pemrosesan gambar harus dilakukan dalam format matriks, tidak diperbolehkan dalam format gambar.
Diperbolehkan menggunakan library eksternal untuk utilitas operasi matriks, operasi matematika, serta backend/frontend, namun algoritma pengolahan citra harus dibuat from scratch.

### Cara Kerja Aplikasi
User dapat mengunggah sebuah gambar dan gambar tersebut akan ditampilkan pada layar
User dapat memilih berbagai operasi editing yang akan dilakukan pada gambar dari sidebar website. Menu-menu editing tersebut berbentuk icon seperti pada aplikasi Photoshop.
Apabila terdapat banyak operasi editing yang dilakukan pada gambar, maka gambar tersebut akan berubah sesuai operasi apa saja yang sudah diberikan
User dapat mengunduh hasil editing dari website
User dapat melakukan reset terhadap operasi editing yang sudah dilakukan pada gambar sehingga gambar dapat kembali seperti semula (sebelum diedit sama sekali)

## Milestone 1: Menu-menu Dasar (900 poin)

1. Membuat citra negatif
![Citra Negatif - Before](http://url/to/img.png)
![Citra Negatif - After](http://url/to/img.png)

2. Mengubah citra berwarna menjadi citra grayscale
![Citra Grayscale - Before](http://url/to/img.png)
![Citra Grayscale - After](http://url/to/img.png)

3. Operasi komplemen pada citra
![Operasi Komplemen - Before](http://url/to/img.png)
![Operasi Komplemen - After](http://url/to/img.png)

4. Operasi geometri (rotasi, flipping, zooming)
Fitur rotasi, flipping, dan zooming terbatas seperti pada aplikasi image processing biasanya
![Rotasi - Before](http://url/to/img.png)
![Rotasi 1 - After](http://url/to/img.png)
![Rotasi 2 - After](http://url/to/img.png)
![Flipping - Before](http://url/to/img.png)
![Flipping 1 - After](http://url/to/img.png)
![Flipping 2 - After](http://url/to/img.png)
![Zooming - Before](http://url/to/img.png)
![Zooming - After](http://url/to/img.png)

Ekspektasi fungsionalitas untuk fitur ini adalah berdasarkan icon-icon di bawah ini:
Icon untuk melakukan rotasi:
![Rotasi 1 - After](http://url/to/img.png)
![Rotasi 2 - After](http://url/to/img.png)

Icon untuk melakukan flipping:  
![Rotasi 1 - After](http://url/to/img.png)
![Rotasi 2 - After](http://url/to/img.png)

Icon untuk melakukan zooming:  
![Rotasi 1 - After](http://url/to/img.png)
![Rotasi 2 - After](http://url/to/img.png)

## Milestone 2: Image Enhancement (1400 poin)

1. Image brightening
![Image Brightening - Before](http://url/to/img.png)
![Image Brightening - After](http://url/to/img.png)

2. Contrast stretching 
![Contrast - Before](http://url/to/img.png)
![Contrast - After](http://url/to/img.png)

3. Tranformasi log dan transformasi pangkat
![Transformasi Log dan Transformasi Pangkat](http://url/to/img.png)

## Milestone 3 (1800 poin)
1. Image blurring dengan teknik Gaussian Filter
![Image Blurring](http://url/to/img.png)

2. Penajaman citra (image sharpening) dengan Gaussian Highpass Filter
![Image Sharpening](http://url/to/img.png)

3. Membuat efek noisy/grainy dengan Gaussian noise
![Noisy](http://url/to/img.png)

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
