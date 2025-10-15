# Pertemuan-03-Lab
# 📊 Analisis Data Smartphone
Analisis data dan pembersihan dataset smartphone. Notebook ini menunjukkan proses dasar eksplorasi data (EDA), pembersihan data, dan persiapan dataset agar siap digunakan untuk analisis atau pemodelan.
## 🧰 Library yang Digunakan
Notebook ini memanfaatkan beberapa library utama Python:
- **NumPy** — operasi numerik dasar  
- **Pandas** — manipulasi dan analisis data tabular  
- **Matplotlib & Seaborn** — visualisasi data  
- **Scikit-learn** — preprocessing dan evaluasi data  
- **Joblib** — menyimpan model/objek 
## 📂 Alur Kerja Notebook

1. **Import Library**  
   Mengimpor semua library yang dibutuhkan untuk analisis data.

2. **Load Dataset**  
   Membaca file CSV (`data-smartphone.csv`) menggunakan `pandas.read_csv()`.

3. **Eksplorasi Awal (EDA)**  
   - Melihat dimensi data (`shape`)  
   - Mengecek tipe data dan nilai hilang (`info()`, `isnull().sum()`)  
   - Mendeteksi dan menghapus duplikasi (`drop_duplicates()`)

4. **Pembersihan Data**  
   - Menghapus karakter seperti `$`, `,`, dan `GB` dari kolom harga dan penyimpanan  
   - Mengonversi tipe data kolom ke numerik (`astype('int64')`)  
   - Menstandarkan format nilai agar konsisten

5. **Analisis Sederhana & Visualisasi (opsional)**  
   Menampilkan ringkasan data, statistik deskriptif, dan visualisasi untuk memahami distribusi data.

6. **Kesimpulan Sementara**  
   Dataset sudah bersih dan siap digunakan untuk analisis lebih lanjut atau pemodelan.

## 📈 Hasil Utama
- Dataset smartphone berhasil dibersihkan dari duplikasi dan nilai tidak valid.  
- Kolom harga dan storage berhasil dikonversi menjadi numerik.  
- Data siap untuk analisis lanjutan seperti regresi harga atau clustering spesifikasi.
