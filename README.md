# Sentiment Analysis Hotel Based on Review with Comparing Naive Bayes and SVM

Proyek Natural Language Processing: Sentiment Analysis Hotel Based on Review with Comparing Naive Bayes and SVM

1.1	Latar Belakang

Hotel merupakan bangunan yang memiliki kamar dalam jumlah banyak yang memang sengaja dibangun untuk dijadikan tempat istirahat atau penginapan sementara bagi para pengunjung. Hotel menyediakan jasa layanan penginapan, makanan dan minuman dengan harga yang bervariasi. Semakin berkembangnya perubahan gaya hidup, hotel saat ini tidak hanya berfungsi sebagai tempat menginap, tetapi juga dimanfaatkan orang untuk rapat, seminar, bahkan sampai pertunjukan dan pameran. Dengan begitu banyak fungsinya semakin banyak hotel yang dibangun maka semakin bingung juga untuk memilih ingin menginap atau menyewa hotel yang lebih baik dan sesuai dengan keinginan. Baik wisatawan maupun orang yang memiliki kepentingan dan mengharuskan menginap atau menyewa hotel seringkali mengalami kesulitan untuk memilih hotel. Mungkin ada beberapa aplikasi yang membantu dalam masalah ini dengan beberapa fitur andalannya seperti fitur komentar. Tetapi banyaknya komentar juga membuat calon pengunjung hotel bingung dan butuh waktu lama untuk memilih hotel mana yang sesuai dengan keinginan. Berdasarkan permasalahan tersebut, maka dibutuhkan adanya sistem analisis sentimen yang mampu mengolah komentar-komentar tersebut, sehingga data yang diperoleh dapat diubah menjadi informasi yang sangat bermanfaat. Sistem tersebut dibangun dengan tujuan membuat model sentiment review hotel.

Abdul Muhaimin Rahat, Abdul Kahir, Abu Kaisar Mohammad Masum [1] melakukan penelitian untuk membandingkan  Algoritma Naive Bayes dan SVM pada sentimen analisis berdasarkan komentar. Pada penelitian ini mereka menggunakan dataset komentar pelanggan di twitter tentang penerbangan. Penelitian ini dilakukan untuk mendapatkan tindakan evaluasi atas komentar yang diberikan oleh para penumpang. hasil dari komentar tersebut digunakan untuk meningkatkan kualitas maskapai penerbangan kedepannya. Setiap komentar dianalisis apakah masuk ke dalam golongan positif atau negatif. Pada penelitian ini dihasilkan tingkat akurasi pada SVM sebesar 83% dan Naive Bayes 77%.
Dany Pratmanto, Husni Faqih, Warjiyono [2] melakukan penelitian mengenai review analysis sentiment pada hotel kelas dunia menggunakan metode Naive Bayes Classifier dan Particle Swarm Optimization. pada penelitian ini menggunakan komentar di media sosial dengan mengambil 200 data review. Pengujian model yang dilakukan dengan menggunakan Naive bayes menghasilkan tingkat akurasi 66,67% sementara pengujian menggabungkan Naive Bayes dengan Particle Swarm Optimization menghasilkan nilai terbaik dengan 85% tingkat akurasinya. Penelitian ini menarik kesimpulan bahwa Naive Bayes akan memberikan hasil terbaik jika digabungkan dengan Particle Swarm Optimization.

Berdasarkan penelitian terdahulu, pada proyek ini penulis akan melakukan penelitian mengenai sentiment analysis hotel based on review dengan membandingkan dua metode yakni algoritma Naïve Bayes untuk melakukan klasifikasi dan Support Vector Machine untuk menentukan opini berdasarkan hasil analisis sentimen. Pada penelitian ini, akan dilakukan perbandingan hasil model sentiment melalui kedua metode tersebut untuk menemukan hasil atau cara yang lebih baik dalam analisis sentimen yang akan mengacu pada emosi atau perasaan. Dengan banyaknya komentar-komentar maka akan meningkatkan data tekstual yang perlu dianalisis. Analisis sentimen ini ditujukan untuk menentukan apakah polaritas korpus tekstual tersebut cenderung positif, negatif dan netral. Penelitian ini juga memberikan manfaat bagi para calon pengunjung hotel untuk dijadikan sebagai acuan untuk memilih hotel, juga dapat bermanfaat untuk manajemen hotel dalam perbaikan atau peningkatan kualitas pelayanan maupun fasilitas.

1.2	Rumusan Masalah

Beberapa rumusan masalah dalam proyek ini adalah:
1.	Bagaimana Naïve Bayes dan SVM dapat memberikan sentimen analisis terhadap hotel berdasarkan komentar?
2.	Bagaimana perbandingan hasil metode Naïve Bayes dan SVM pada sentiment analysis?
1.3	Tujuan

Yang menjadi tujuan dalam proyek ini adalah:
1.	Mengetahui cara Naïve Bayes dan SVM dalam membangun model sentiment analysis berdasarkan komentar.
2.	Mengetahui hasil perbandingan metode antara Naïve Bayes dan SVM dalam menemukan model sentiment analysis.

1.4	Ruang Lingkup Proyek
Adapun yang menjadi ruang lingkup penelitian ini adalah:
1.	Penelitian ini menggunakan dataset dari komentar wisatawan dan pengunjung terhadap sebuah hotel.
2.	Algoritma yang digunakan pada proyek ini adalah Naïve Bayes Classification dan Support Vector Machine.

