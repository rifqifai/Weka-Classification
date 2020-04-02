# Weka-Classification
## Implementasi Algoritme Klasifikasi Naïve Bayes, Decision Tree J48, dan Multilayer Perceptron Menggunakan Weka

Kegiatan evaluasi dan pengambilan keputusan akan dapat dilakukan dengan baik jika suatu masalah memiliki informasi yang lengkap, cepat, tepat, dan akurat. Penelitian ini mengkaji untuk menguraikan kinerja terbaik dari beberapa algoritme klasifikasi dalam data mining yaitu naïve bayes, decision tree J48, dan multilayer perceptron. Beberapa aspek yang dilihat dalam penelitian adalah dari sisi keakuratan prediksi dan kecepatan/efisiensi. Adapun software yang digunakan untuk mengevaluasi beberapa algoritme klasifikasi tersebut adalah Weka versi 3.8. Hasil pengujian menunjukkan bahwa kinerja model multilayer perceptron memiliki akurasi terbaik sebesar 61.59% dengan menggunakan mode tes precentage split. Namun algoritme naïve bayes memiliki kecepatan yang terbaik untuk semua mode tes yang digunakan dalam penelitian ini.

# Evaluasi
secara keseluruhan nilai akurasi tertinggi diraih pada algoritme multilayer perceptron dengan mode tes precentage split yang mencapai 61,59% pada kolom correctly classified instances. Dalam hal ini, implementasi algoritme multilayer perceptron dengan menggunakan mode tes precentage split yaitu terdiri dari 311 instance yang terklasifikasi benar dari total 505 jumlah data keseluruhan dengan nilai mean absolute error sebesar 0.1013.
Begitu sebaliknya algoritme multilayer perceptron yang menggunakan mode tes percentage split memiliki nilai terendah untuk incorrectly classified instance yaitu 38,41% di mana klasifikasi data salah hanya sebesar 194 instances dari total keseluruhan data sebanyak 505 instances.

1. Hasil perbandingan nilai akurasi klasifikasi data benar
![akurasi data benar](https://github.com/rifqifai/Weka-Classification/blob/master/graph/akurasi_data_benar.jpg)

2. Hasil perbandingan nilai akurasi klasifikasi data salah
![akurasi data salah](https://github.com/rifqifai/Weka-Classification/blob/master/graph/akurasi_data_salah.jpg)
