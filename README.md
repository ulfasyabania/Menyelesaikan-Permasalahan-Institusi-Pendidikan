---

```markdown
# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

---

## Business Understanding

**Latar Belakang Bisnis**

Pendidikan merupakan salah satu pilar penting dalam pembangunan sumber daya manusia. Namun, banyak institusi pendidikan menghadapi permasalahan serius terkait penurunan angka kelulusan dan tingginya angka dropout. Hal ini tidak hanya berdampak pada kualitas sumber daya manusia, tetapi juga menurunkan reputasi dan kinerja institusi pendidikan.  
Dalam konteks ini, Jaya Jaya Institut ingin memahami faktor-faktor yang mempengaruhi keberhasilan akademik mahasiswa serta mengidentifikasi risiko dropout sejak dini, sehingga dapat dilakukan intervensi tepat waktu untuk meningkatkan retensi dan kinerja akademik.

---

## Permasalahan Bisnis

- **Dropout Mahasiswa:** Tingginya angka mahasiswa yang berhenti studi sebelum menyelesaikan program.
- **Kurangnya Prediksi Kinerja Akademik:** Sulitnya mengidentifikasi mahasiswa yang berpotensi gagal dalam proses perkuliahan.
- **Pengelolaan SDM yang Tidak Efisien:** Tanpa adanya sistem prediksi yang akurat, institusi akan kesulitan untuk merancang program intervensi dan pendampingan bagi mahasiswa berisiko.
- **Optimasi Sumber Daya:** Ketidaktahuan akan tren dan faktor risiko menyebabkan pemborosan sumber daya dalam mendukung mahasiswa yang membutuhkan bantuan khusus.

---

## Cakupan Proyek

Proyek ini mencakup seluruh tahapan utama dalam siklus data science, yaitu:

1. **Business Understanding:** Menjabarkan permasalahan bisnis dan tujuan akhir proyek.
2. **Data Collection & Sumber Data:** Pengambilan data terkait dropout dan keberhasilan akademik mahasiswa.
3. **Data Understanding & Preparation (Preprocessing):** Pembersihan data, penanganan missing values, duplikat, outlier serta feature engineering.
4. **Exploratory Data Analysis (EDA) & Visualisasi:** Pembuatan visualisasi untuk memahami distribusi data dan insight penting melalui grafik (misalnya, histogram, ROC Curve, Precision-Recall Curve).
5. **Modeling & Evaluation:** Pembangunan model machine learning (Logistic Regression, Random Forest, XGBoost) dan evaluasi mendalam (ROC, AUC, threshold optimal, cost-sensitive analysis).
6. **Deployment:** Pembuatan Dashboard bisnis dan prototype sistem machine learning berbasis UI interaktif menggunakan Streamlit.
7. **Action Items:** Rekomendasi strategis untuk institusi dalam mengoptimalkan performa dan intervensi bagi mahasiswa.

---

## Persiapan

- **Sumber Data:**
  - Data asli diperoleh dari UCI Machine Learning Repository:  
    [Predict Students Dropout and Academic Success](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
  - Data yang digunakan dalam proyek ini disimpan di repositori Github:  
    [Data CSV](https://raw.githubusercontent.com/ulfasyabania/Menyelesaikan-Permasalahan-Institusi-Pendidikan/refs/heads/main/data.csv)

- **Setup Environment:**
  - **Bahasa Pemrograman:** Python
  - **Library Utama:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
  - **Tools Prototyping UI:** Streamlit untuk membangun sistem interaktif
  - **Dashboard:** (Jika menggunakan Metabase, Tableau Public, atau Looker Studio)

---

## Business Dashboard

**Deskripsi Dashboard:**

Dashboard yang telah dibuat bertujuan untuk memberikan insight real-time mengenai performa akademik mahasiswa dan potensi dropout. Dashboard ini dilengkapi dengan visualisasi interaktif seperti grafik tren, heatmap korelasi, dan breakdown per faktor risiko.  
Dashboard menampilkan informasi penting seperti:
- Distribusi nilai akademik
- Peta statistik kehadiran dan keterlibatan mahasiswa
- Indikator performa berdasarkan output model prediktif

**Akses Dashboard:**

Jika menggunakan Metabase:  
- **Email:** root@mail.com  
- **Password:** root123

*(Jika menggunakan Tableau Public atau Looker Studio, sertakan link akses di sini.)*

---

## Menjalankan Sistem Machine Learning

**Prototype Sistem Machine Learning:**

Solusi machine learning telah dikemas dalam sebuah prototype berbasis **Streamlit** yang siap digunakan oleh user. Prototype ini memiliki antarmuka yang mudah digunakan dan menyediakan berbagai fitur, seperti:
- **Input Parameter:** Pengguna dapat memasukkan variabel seperti nilai admission grade, previous qualification, dan total approved units.
- **Output Prediksi:** Menampilkan hasil prediksi status mahasiswa (Graduate vs. Dropout) secara real-time.
- **Visualisasi Evaluasi:** Tampilan grafik evaluasi model seperti ROC Curve dan Precision-Recall Curve.

**Cara Menjalankan Prototype:**

1. Clone repository ini ke lokal Anda.
2. Pastikan lingkungan sudah terinstall Streamlit dan dependency lain (install menggunakan `pip install -r requirements.txt` jika ada).
3. Jalankan prototype dengan perintah:
   ```bash
   streamlit run app.py
   ```
4. Prototype telah diluncurkan dan dihosting di **Streamlit Community Cloud**.  
   **Akses Prototype:** [Link Prototype Machine Learning](#) *(Sertakan link aktual jika sudah di-deploy)*

---

## Conclusion

Dalam proyek ini, kami berhasil:

- Mengidentifikasi faktor-faktor yang berpengaruh terhadap dropout mahasiswa dan kinerja akademik melalui analisis mendalam.
- Mengembangkan beberapa model prediktif (Logistic Regression, Random Forest, XGBoost) yang dapat mengantisipasi risiko dropout dengan akurasi yang tinggi.
- Melakukan evaluasi mendalam, termasuk analisis ROC, AUC, Precision-Recall, serta cost-sensitive analysis untuk menentukan threshold optimal.
- Membuat dashboard interaktif yang membantu pihak institusi dalam memonitor performa mahasiswa secara real-time.
- Menyusun prototype sistem machine learning yang siap digunakan oleh user dengan antarmuka yang intuitif.

Kesimpulannya, solusi yang diusulkan mampu mendukung Jaya Jaya Institut dalam mengoptimalkan intervensi dan mendukung mahasiswa yang berisiko dropout, sehingga secara keseluruhan meningkatkan retensi dan kinerja akademik.

---

## Rekomendasi Action Items

Berdasarkan hasil analisis dan evaluasi proyek, berikut adalah rekomendasi action items yang dapat diterapkan oleh Jaya Jaya Institut:

- **Action Item 1:**  
  *Implementasikan sistem notifikasi intervensi dini!*  
  Gunakan output model prediktif untuk mengidentifikasi mahasiswa berisiko dropout dan segera lakukan pendekatan proaktif, seperti program mentoring atau konseling akademik.

- **Action Item 2:**  
  *Optimalkan penggunaan dashboard bisnis!*  
  Manfaatkan dashboard interaktif untuk memantau performa mahasiswa secara real-time dan menginformasikan pihak pengajar serta manajemen terkait tren dan pola yang muncul, sehingga dapat merencanakan tindakan pendukung secara terencana.

- **Action Item 3:**  
  *Evaluasi ulang kebijakan akademik secara periodik!*  
  Berdasarkan insight dari model prediksi, lakukan analisis mendalam pada program studi dan kurikulum untuk mengidentifikasi area perbaikan, sehingga institusi dapat meningkatkan kualitas pengajaran dan dukungan mahasiswa.

---

*Dokumentasi ini disusun agar reviewer dapat dengan mudah memahami seluruh tahapan proyek, mulai dari akuisisi data, preprocessing, modeling, evaluasi mendalam, hingga deployment solusi dan rekomendasi strategis untuk perusahaan.*

```

---
