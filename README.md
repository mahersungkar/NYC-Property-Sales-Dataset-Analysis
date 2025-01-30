🏙️ NYC Property Sales Dataset Analysis
📌 Overview
Dataset ini berisi informasi tentang properti yang terjual di New York City, mencakup lokasi, tipe properti, harga jual, dan tanggal transaksi. Data ini dapat digunakan untuk menganalisis tren pasar real estate, pola harga properti, dan faktor-faktor yang mempengaruhi nilai jual.

📂 Dataset lengkap dapat diakses di sini: NYC Property Sales Dataset

📁 Dataset Information
Dataset ini mencakup berbagai fitur, di antaranya:

BOROUGH → Kode wilayah properti berada:
Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), Staten Island (5).
BLOCK & LOT → Kombinasi Borough, Block, dan Lot (BBL) sebagai identifikasi unik properti di NYC.
BUILDING CLASS AT PRESENT & AT TIME OF SALE → Klasifikasi properti berdasarkan jenis bangunan pada saat itu.
SALE PRICE & SALE DATE → Harga dan tanggal transaksi penjualan properti.
📌 Catatan:

Beberapa transaksi memiliki harga $0, yang biasanya terjadi pada transfer kepemilikan (misalnya, orang tua menghibahkan rumah kepada anak).
Properti yang dimiliki secara individu dalam bentuk kondominium akan memiliki transaksi berdasarkan unit, sedangkan properti yang dimiliki satu entitas dapat dijual dalam bentuk gedung utuh.
🛠 Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
Jupyter Notebook
Data Visualization (Matplotlib, Seaborn)
Machine Learning (Regression Models, Clustering)
📊 Exploratory Data Analysis (EDA)
Dalam tahap eksplorasi data, dilakukan:
✅ Analisis distribusi harga jual properti per borough.
✅ Visualisasi tren harga properti dari tahun ke tahun.
✅ Identifikasi outlier dan transaksi anomali.

🚀 Predictive Modeling
Model yang digunakan untuk menganalisis harga properti:
✅ Linear Regression – Untuk memahami hubungan antara fitur dan harga properti.
✅ Random Forest & Decision Tree – Untuk memprediksi harga properti berdasarkan atribut properti.
✅ K-Means Clustering – Untuk mengelompokkan properti berdasarkan harga dan lokasi.

📌 Evaluasi Model:

R² Score, Mean Squared Error (MSE), Mean Absolute Error (MAE) untuk regresi.
Silhouette Score untuk clustering.
📜 How to Use
Clone repository ini:
bash
Salin
Edit
git clone https://github.com/username/nyc-property-sales-analysis.git
Install dependencies:
bash
Salin
Edit
pip install -r requirements.txt
Jalankan analisis di Jupyter Notebook:
bash
Salin
Edit
jupyter notebook
🤝 Contributing
Jika Anda ingin berkontribusi, silakan fork repository ini, buat branch baru, dan ajukan pull request! 🚀

📩 Contact
📧 Email: sungkarmaher6@gmail.com
🔗 LinkedIn: Maher Ismail Sungkar
