# Analisis Kesehatan Mental dan Fisik Pasien Thalassemia Menggunakan ANOVA, MANOVA, dan MANCOVA

## Deskripsi Penelitian

Penelitian ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi kondisi kesehatan mental dan fisik pasien Thalassemia di Bangladesh. Analisis dilakukan menggunakan metode statistik multivariat, yaitu ANOVA, MANOVA, dan MANCOVA untuk melihat pengaruh variabel independen terhadap dua variabel dependen secara simultan maupun individual.

## Tujuan Penelitian

* Mengidentifikasi pengaruh variabel Diagnosis, Frequency of Blood Transfusion, dan Comorbidities Status terhadap:

  * Mental Health Summary
  * Physical Health Summary
* Menganalisis pengaruh variabel kovariat (Vitality) terhadap hubungan tersebut
* Membandingkan hasil analisis univariat (ANOVA) dan multivariat (MANOVA & MANCOVA)

## Dataset

Sumber: https://data.mendeley.com/datasets/7c2zd56mzd/1/files/109097d1-8806-41cb-b323-c415b427c41b
Dataset yang digunakan berisi data pasien Thalassemia di Bangladesh dengan variabel utama:

* Mental_Health_Summary
* Physical_Health_Summary
* Diagnosis
* Frequency_of_Blood_Transfusion
* Comorbidities_Status
* Vitality

## Metode Analisis

1. **Uji Asumsi**

   * Normalitas multivariat
   * Homogenitas varians-kovarians (Box’s M)
   * Homogenitas varians (Levene’s Test)
   * Multikolinearitas (VIF)
   * Homogenitas kemiringan regresi

2. **Analisis Statistik**

   * ANOVA (analisis univariat)
   * MANOVA (analisis multivariat)
   * MANCOVA (dengan kovariat Vitality)

## Hasil Utama

* Variabel **Comorbidities Status** menunjukkan pengaruh paling konsisten terhadap kesehatan mental dan fisik
* Pada analisis MANCOVA, seluruh variabel independen menjadi signifikan setelah mengontrol variabel **Vitality**
* Variabel **Vitality** memiliki pengaruh yang sangat signifikan terhadap kedua variabel dependen

## Insight

Hasil penelitian menunjukkan bahwa kondisi komorbiditas dan tingkat vitalitas pasien memiliki peran penting dalam menentukan kesehatan mental dan fisik pasien Thalassemia.

## Tools & Teknologi

* R Programming
* Statistical Analysis (ANOVA, MANOVA, MANCOVA)

## Cara Menjalankan

1. Load dataset ke dalam R
2. Jalankan script analisis yang tersedia
3. Lihat output hasil uji asumsi dan analisis utama

## Author

Aprilia Safna Anggraeni (24031554003) – Mahasiswa Sains Data
Khairun Nisa' (24031554043) – Mahasiswa Sains Data
Naufal Muzaki (24031554061) – Mahasiswa Sains Data
