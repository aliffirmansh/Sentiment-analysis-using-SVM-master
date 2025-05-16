File ini adalah notebook yang berisi percobaan klasifikasi teks menggunakan metode SVM (Support Vector Machine). Proyek ini fokus ke analisis sentimen dari data teks.

Di dalam notebook, data teks diolah dulu pakai TextBlob, nltk, dan diubah ke bentuk numerik pakai TfidfVectorizer atau CountVectorizer. Setelah itu, datanya dibagi jadi data latih dan data uji, lalu dilatih pakai model SVM dari sklearn.svm.SVC.

Beberapa library utama yang dipakai:

pandas, numpy untuk data handling

matplotlib dan seaborn buat visualisasi

sklearn buat training dan evaluasi model

nltk dan textblob untuk preprocessing teks