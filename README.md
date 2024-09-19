# SPAM SMS INDONESIA USING GRU & LSTM

### WordCloud SPAM SMS
![image](https://github.com/user-attachments/assets/270aebc3-bdaa-4ea1-85e6-4db99258396f)


### Result
![image](https://github.com/user-attachments/assets/b1c828eb-b6a2-4728-8e15-1bc44957b4ad)

Tabel di atas merupakan tabel perbandingan performa seluruh model yang digunakan dalam penelitian ini. Model LSTM yang memiliki nilai metrik evaluasi terbaik adalah model dengan  metode text representation TF-IDF. Nilai accuracy, precision, recall, dan f1-score yang diperoleh berkisar di angka 97%. Model Bi-LSTM yang memiliki nilai metrik evaluasi terbaik adalah model  dengan metode text representation TF-IDF. Nilai accuracy, precision, recall, dan f1-score yang diperoleh berkisar di angka 97%. Model GRU yang memiliki nilai metrics evaluasi terbaik adalah model dengan metode text representation TF-IDF. Nilai accuracy, precision, recall, dan f1-score yang diperoleh berkisar di angka 98%. Model Bi-GRU yang memiliki nilai metrics evaluasi terbaik adalah model dengan metode text representation TF-IDF. Nilai accuracy, precision, recall, dan f1-score yang diperoleh berkisar di angka 97%. Menganalisis dari hasil keempat metrik tersebut, dapat ditarik kesimpulan bahwa TF-IDF lebih unggul dan cocok untuk kasus klasifikasi kategori SMS 
spam ini dibandingkan dengan Doc2Vec. TF-IDF merepresentasikan teks dengan mempertimbangkan frekuensi kemunculan kata sehingga cocok untuk dataset dengan distribusi kata yang relevan untuk klasifikasi, dimana data SMS spam ini memiliki beberapa term tertentu yang memang mengindikasikan suatu pesan sebagai spam. Sebaliknya, Doc2Vec mengubah dokumen menjadi vektor melalui proses pelatihan neural networkyang mencoba memprediksi kata berdasarkan konteks. Maka dari itu, Doc2Vec dapat menjadi kurang optimal apabila dihadapkan pada dataset dengan variasi konteks yang tinggi atau kalimat-kalimat yang tidak konsisten. Doc2Vec sulit menangkap informasi dengan baik karena dataset SMS spam ini banyak menggunakan kata-kata yang tidak baku dan penuh singkatan.Ada pula, TF-IDF dinilai lebih efektif dan stabil untuk dataset kecil. Sedangkan Doc2Vec  memerlukan dataset yang lebih besar untuk membangun vektor representasi yang akurat. Dalam  hal ini, data yang digunakan cenderung kecil karena hanya berkisar di angka 1000. Oleh karena itu, metode representasi yang menghasilkan performa lebih baik untuk dataset klasifikasi SMS spam ini adalah TF-IDF.

Terakhir, model dengan metode text representation TF-IDF yang memiliki nilai metrics evaluasi terbaik adalah model GRU yang menggunakan input layer 128 unit, satu hidden layer 64 unit, dan fungsi aktivasi sigmoid untuk memprediksi output. Nilai accuracy, precision, recall, dan f1-score yang diperoleh berkisar di angka 98%.

![image](https://github.com/user-attachments/assets/d4b4dbaa-1319-4f60-89a2-6bd7e639bd9d)
