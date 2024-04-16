# 21081107010033_Pertemuan_11_ANN
## Tugas 3 SVM VS ANN

Nama : Aulia Muzhaffar
NPM : 2108107010033

Dataset : 
- Regresi https://www.kaggle.com/datasets/yasserh/student-marks-dataset

Atribut :
* number_courses : jumlah Course yang diambil
* time_study : jumlah waktu belajar

Label :
* Marks : nilai yang didapat siswa

- clasification https://data.mendeley.com/datasets/tsy6rbc5d4/1

Atribut :
* subject ID
* MRI ID
* Visit
* MR Delay
* Hand
* Age
* EDUC
* SES
* MSE
* CDR
* eTIV
* nWBV
* ASF
desc dataset : 
 Analisis longitudinal dilakukan pada kumpulan data OASIS - MRI [21], yang terdiri dari subjek berusia 60 hingga 96 tahun dengan tipe tangan kanan (R), yang mengalami demensia dan tidak mengalami demensia. Ukuran sampel terdiri dari 150 subjek, termasuk pria dan wanita, yang telah mengikuti lebih dari dua sesi pemindaian selama kunjungan yang terpisah setidaknya satu tahun, menghasilkan total 373 sesi MRI. Data pelatihan sampel (lihat Tabel 1) mencakup ID Subjek, ID MRI, Kelompok, Kunjungan, Penundaan MR, Jenis Kelamin, Usia, Status Ekonomi Sosial (SES), Tingkat Pendidikan (EDUC), MMSE [22], Rasio Demensia Klinis (CDR) [23], estimasi Volume Intrakranial Total (e-TIV), Volume Otak Utuh yang dinormalisasi (n-WBV), dan Faktor Penskalaan Atlas (ASF).

 Selain itu, Gambar 3 menggambarkan kategorisasi sesi MRI saat ini berdasarkan skor CDR (0-2) saat ini dan total sesi yang tidak mengalami demensia (190), mengalami demensia (146), dan mengalami konversi (37) dievaluasi. Dalam kategori konversi, terdapat subjek yang awalnya didiagnosis dengan demensia namun berubah menjadi tidak mengalami demensia. Penilaian CDR yang sama dengan nol menandakan bahwa subjek sebagian besar tidak mengalami demensia, sementara nilai CDR≥1 menunjukkan kecenderungan mengalami demensia pada subjek tersebut.

Label :
* Group : menunjukkan apakah pasien mengindap dementia atau tidak

# Hasil SVM dan ANN
## Regresi 
- SVM akurasi : 83 %
- ANN akurasi : 94,27 %

## Klasifikasi 
- SVM akurasi : 74,1 % %
- ANN akurasi : 89,33 %

## Tutor menjalankan Code
### Setup environment
```
conda create --name main-ds python=3.10
conda activate main-ds
pip install -r requirements.txt
```
### run code
- untuk menjalankan model regression masuk ke dalam folder regression dan pilih file format .ipyb kemudian jalankan
- untuk menjalankan model clasification masuk ke dalam folder clasification dan pilih file format .ipyb kemudian jalankan

