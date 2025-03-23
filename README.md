# Clustering dan Classification Pelanggan E-Commerce

![Image](https://github.com/user-attachments/assets/2c0fecaf-34b6-4eff-b9ce-52db039c9af3)

## 📌 Deskripsi
Proyek ini bertujuan untuk melakukan analisis pelanggan pada platform e-commerce dengan menggunakan teknik *clustering* dan *classification*. Dengan memanfaatkan dataset pelanggan, proyek ini mengelompokkan pelanggan ke dalam segmen tertentu dan membangun model klasifikasi untuk memahami perilaku mereka.

## 📊 Dataset
Dataset yang digunakan dalam proyek ini berasal dari sumber data publik dan berisi informasi pelanggan, termasuk:
- **Demografi** (Usia, Gender, Lokasi, dll.)
- **Riwayat Pembelian** (Jumlah transaksi, Total Pengeluaran, Frekuensi Pembelian, dll.)
- **Interaksi Online** (Kunjungan situs, Produk yang sering dilihat, dll.)

## 🚀 Teknologi yang Digunakan
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Streamlit (untuk dashboard interaktif, opsional)

## ⚡ Tahapan Proyek
1. **Data Preprocessing**
   - Mengatasi missing values dan outliers
   - Normalisasi dan encoding data jika diperlukan

2. **Clustering**
   - Menggunakan algoritma K-Means dan DBSCAN
   - Menentukan jumlah cluster optimal dengan metode Elbow dan Silhouette Score
   - Visualisasi hasil clustering

3. **Classification**
   - Membangun model klasifikasi menggunakan Logistic Regression, Random Forest, dan SVM
   - Evaluasi model menggunakan Confusion Matrix, Precision, Recall, dan F1-Score
   - Hyperparameter tuning dengan GridSearchCV

4. **Deployment (Opsional)**
   - Membangun dashboard interaktif dengan Streamlit untuk eksplorasi data dan hasil model

## 📈 Hasil Analisis
- **Clustering:** Ditemukan beberapa segmen pelanggan berdasarkan kebiasaan belanja.
- **Classification:** Model terbaik yang digunakan memiliki akurasi **XX%** dengan evaluasi metrik yang seimbang.
- **Insight Bisnis:** Model ini dapat membantu bisnis memahami pelanggan mereka lebih baik dan menyesuaikan strategi pemasaran.

## 📂 Struktur Repository
```
📦 Clustering-dan-Classification-Pelanggan-Ecommerce
│── 📄 [Clustering] Submission Akhir BMLP_Nama.ipynb
│── 📄 [Klasifikasi] Submission Akhir BMLP_Nama.ipynb
│── 📄 Dataset_clustering.csv
│── 📄 Dataset_inisiasi.csv

```

## 🛠 Instalasi dan Penggunaan
### 1️⃣ Clone Repository
```bash
git clone https://github.com/username/Clustering-dan-Classification-Pelanggan-Ecommerce.git
cd Clustering-dan-Classification-Pelanggan-Ecommerce
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Jalankan Notebook
Gunakan Jupyter Notebook atau Google Colab untuk menjalankan analisis:
```bash
jupyter notebook
```

### 4️⃣ Jalankan Dashboard (Opsional)
Jika menggunakan Streamlit untuk visualisasi hasil, jalankan perintah berikut:
```bash
streamlit run app.py
```

## 🤝 Kontribusi
Kontribusi sangat diterima! Jika Anda ingin berkontribusi, silakan buat *issue* atau *pull request* di repository ini.

## 📜 Lisensi
Proyek ini dirilis di bawah lisensi MIT - lihat [LICENSE](LICENSE) untuk detail lebih lanjut.

---
📧 **Kontak & Diskusi**
Jika ada pertanyaan atau ingin berdiskusi, silakan hubungi saya di [jhodywiraputra@gmail.com](mailto:jhodywiraputra@gmail.com) atau buka *issue* di repository ini.

✨ Jangan lupa *star* repo ini jika bermanfaat! 🚀

