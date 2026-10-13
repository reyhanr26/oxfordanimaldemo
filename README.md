=====================================================================
README - PROYEK KLASIFIKASI GAMBAR (DEEP LEARNING)
1. DESKRIPSI PROYEK
Proyek ini berisi eksperimen pembuatan dan pelacakan (tracking) 
model Deep Learning untuk tugas klasifikasi gambar (10 kelas). 
Eksperimen dilakukan secara bertahap, mulai dari model arsitektur 
dasar hingga menggunakan arsitektur pre-trained (EfficientNet-B0), 
serta menguji pengaruh teknik augmentasi data.

2. STRUKTUR NOTEBOOK
Proyek ini dibagi menjadi tiga bagian utama di dalam Jupyter Notebook:
* BAGIAN A: Eksplorasi Data (EDA)
  - Pemuatan (loading) dataset.
  - Pembagian dataset menjadi subset Train, Validation, dan Test.
  - Visualisasi sampel gambar mentah.



* BAGIAN B: Pemodelan & Eksperimen (B1 - B5)
  - B1 - B3: Eksperimen model dasar (baseline) dengan berbagai penyesuaian.
  - B4: Eksperimen model menggunakan teknik Augmentasi Data.
  - B5: Eksperimen menggunakan pre-trained model (EfficientNet-B0) + Augmentasi.
  (Termasuk visualisasi kurva Loss dan Accuracy untuk masing-masing model).



* BAGIAN C: Evaluasi & Analisis (C1 - C3)
  - C1: Log mentah dan tabel konsolidasi performa semua model (B1-B5).
  - C2: Confusion Matrix dan Classification Report (Precision, Recall, F1-Score).
  - C3: Failure Analysis (Analisis kegagalan) untuk melihat di mana model 
        sering melakukan kesalahan prediksi.

3. PERSYARATAN LINGKUNGAN (DEPENDENCIES)
Pastikan environment Python Anda sudah terinstal library berikut:
- PyTorch / TensorFlow (sesuaikan dengan framework yang Anda pakai)
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

4. CARA MENJALANKAN
1. Pastikan dataset sudah berada di direktori yang tepat sesuai dengan path
   yang ada di dalam notebook.
2. Buka file `.ipynb` menggunakan Jupyter Notebook atau Google Colab.
3. Jalankan sel (cell) secara berurutan dari atas ke bawah (Run All).
=====================================================================
