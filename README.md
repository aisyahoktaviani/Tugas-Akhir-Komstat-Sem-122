# 📊 Aplikasi Analisis Korelasi & Asosiasi (R Shiny)

Aplikasi web interaktif yang dibangun menggunakan **R** **Shiny** untuk mempermudah analisis statistik hubungan antar variabel. Aplikasi ini memungkinkan pengguna untuk mengunggah dataset mereka sendiri (CSV atau Excel), melakukan uji statistik, dan mendapatkan hasil berupa visualisasi interaktif, interpretasi, serta laporan yang dapat diunduh.

![Screenshot (772)](https://github.com/user-attachments/assets/df1ec277-d2c4-49c3-b0b7-6b372a7f38bf)


---

## ✨ Fitur Utama

-   **📤 Upload Data Mudah**: Mendukung unggahan file dalam format `.csv` dan `.xlsx`.
-   **🔬 Analisis Statistik Lengkap**:
    -   **Uji Korelasi Spearman**: Untuk mengukur kekuatan dan arah hubungan antara dua variabel **numerik**.
    -   **Uji Asosiasi Cramér's V**: Untuk mengukur kekuatan asosiasi antara dua variabel **kategorik**.
-   **📈 Visualisasi Interaktif**:
    -   Scatter plot interaktif (dengan Plotly) untuk hasil korelasi Spearman.
    -   Heatmap kontingensi untuk uji Cramér's V.
    -   Heatmap matriks korelasi untuk semua variabel numerik dalam dataset.
-   **💡 Interpretasi Otomatis**: Memberikan penjelasan sederhana mengenai hasil statistik untuk membantu pemahaman pengguna.
-   **📄 Laporan Otomatis**: Kemampuan untuk mengunduh seluruh ringkasan hasil analisis dalam format **Microsoft Word (.docx)**.
-   **🎨 Antarmuka Modern**: UI yang bersih dan responsif dibangun demi pengalaman pengguna yang lebih baik.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [IBAI DKK MIT](LICENSE.md).
