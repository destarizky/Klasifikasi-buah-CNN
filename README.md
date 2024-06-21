Fruits 360
Sebuah dataset berisi gambar buah dan sayuran.

Properti Dataset:
Total jumlah gambar: 82,213.
Ukuran set pelatihan: 61,488 gambar (satu buah atau sayuran per gambar).
Ukuran set pengujian: 20,622 gambar (satu buah atau sayuran per gambar).
Ukuran set multi-buah: 103 gambar (lebih dari satu buah atau kelas buah per gambar).
Jumlah kelas: 120 (buah dan sayuran).
Ukuran gambar: 100x100 piksel.
Dataset dapat ditemukan di: Kaggle dan GitHub.

Ini adalah karya dari Horea Muresan dan Mihai Oltean, yang diterbitkan dalam makalah "Fruit recognition from images using deep learning", di Acta Univ. Sapientiae, Informatica Vol. 10, Issue 1, pp. 26-42, 2018.

Makalah tersebut memperkenalkan dataset dan implementasi Jaringan Saraf yang dilatih untuk mengenali buah dalam dataset tersebut.

Cara Menggunakan Ini
Persyaratan
File requirements.txt berisi semua paket yang ada di lingkungan pada saat pelatihan.

Tensorflow 2.0 (Menggunakan Tensorflow-GPU)
Keras 2.3.1
Matplotlib
Numpy
Penggunaan
Gambar-gambar yang akan diprediksi diletakkan di bawah folder fruits/test_images.

Model ini sudah dilatih sebelumnya dan bobotnya adalah file H5py, bernama Fruits_360.h5.

File fruits.py berisi Model Jaringan dan digunakan untuk melatihnya.
