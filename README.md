# final-project-mlops-dicoding

# Submission: Fake News Classification

Nama: William Hilmy Susatyo

Username Dicoding: williamhilmysusatyo


| | Deskripsi |
| ----------- | ----------- |
| Dataset | Dataset yang digunakan dalam proyek ini dapat diakses pada [tautan](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) berikut ini|
| Masalah | Dalam era saat ini, prevalensi berita yang tidak akurat dan tidak sesuai dengan realitas meningkat, menyebabkan munculnya opini negatif. Masyarakat yang terpapar oleh berita palsu (hoax) cenderung mengalami kesulitan dalam membedakan antara informasi faktual dan informasi yang tidak benar. Perlu adanya kesadaran akan pentingnya literasi informasi dan kritis dalam menilai kebenaran suatu berita untuk mengatasi dampak negatif yang dapat timbul akibat penyebaran informasi yang tidak akurat. |
| Solusi machine learning | Oleh karena itu, diperlukan suatu sistem pembelajaran mesin yang mampu mengidentifikasi keaslian suatu berita. Sistem ini bertujuan untuk secara otomatis membedakan antara berita yang benar dan berita yang tidak benar, sehingga dapat membantu meningkatkan kredibilitas informasi yang diterima oleh pengguna. |
| Metode pengolahan | Dalam proyek ini, pengolahan data menggunakan metode tokenisasi pada fitur input, yaitu teks dari suatu berita. Proses ini melibatkan transformasi teks menjadi urutan angka, yang kemudian menjadi representasi numerik dari teks tersebut. Tujuan dari langkah ini adalah agar model dapat lebih efektif memahami dan memproses informasi yang terkandung dalam teks. |
| Arsitektur model | Dalam struktur model ini, digunakan lapisan TextVectorization sebagai elemen yang akan mengubah string input menjadi representasi numerik. Selanjutnya, lapisan Embedding bertanggung jawab dalam memahami kedekatan atau kemiripan antar kata, yang menjadi kunci untuk menentukan apakah suatu kata bersifat negatif atau positif. Selain itu, model ini terdiri dari dua lapisan tersembunyi (hidden layer) dan satu lapisan output. |
| Metrik evaluasi | Pada model ini, digunakan metrik seperti Accuracy, Recall, Precision, dan F1 Score untuk menilai kinerja model dalam mengklasifikasikan data. Metrik-metrik tersebut membantu dalam mengukur keakuratan dan keefektifan model dalam membedakan antara kelas-kelas yang diinginkan, memberikan gambaran yang lebih komprehensif terkait evaluasi performa.|
| Performa model | Model yang telah dikembangkan berhasil mencapai kinerja yang sangat memuaskan dalam menghasilkan prediksi untuk teks berita yang diinputkan. Melalui serangkaian pelatihan yang telah dilakukan, model berhasil mencapai tingkat keakuratan biner (binary accuracy) dan tingkat keakuratan validasi (val_binary accuracy) sekitar 98%. Tingkat keakuratan yang tinggi tersebut menunjukkan kemampuan model untuk dengan tepat mengklasifikasikan berita, memberikan kepercayaan bahwa model dapat memberikan prediksi yang dapat diandalkan dalam konteks ini.|

loss: 0.0822 - binary_accuracy: 0.9715 - val_loss: 0.0828 - val_binary_accuracy: 0.9717
