# 📊 Aplikasi Analisis Korelasi & Asosiasi (R Shiny)

Aplikasi web interaktif yang dibangun menggunakan **R** dan **Shiny** untuk mempermudah analisis statistik hubungan antar variabel. Aplikasi ini memungkinkan pengguna untuk mengunggah dataset mereka sendiri (CSV atau Excel), melakukan uji statistik, dan mendapatkan hasil berupa visualisasi interaktif, interpretasi, serta laporan yang dapat diunduh.

![![image](https://github.com/user-attachments/assets/4d54ba3b-d878-4f32-bca0-9fc2eb9e9472)
](URL_SCREENSHOT_ANDA_DISINI.png)
*(Sangat disarankan untuk menambahkan screenshot aplikasi Anda)*

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
-   **💡 Interpretasi Otomatis**: Memberikan penjelasan sederhana mengenai hasil statistik (misal: "korelasi kuat yang signifikan") untuk membantu pemahaman pengguna.
-   **📄 Laporan Otomatis**: Kemampuan untuk mengunduh seluruh ringkasan hasil analisis dalam format **Microsoft Word (.docx)**.
-   **🎨 Antarmuka Modern**: UI yang bersih dan responsif dibangun dengan `bslib` dan `shinydashboard` untuk pengalaman pengguna yang lebih baik.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [Lisensi MIT](LICENSE.md).
