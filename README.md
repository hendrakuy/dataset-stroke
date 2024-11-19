# Stroke Dataset

Dataset ini digunakan untuk menganalisis dan mengklasifikasikan penyakit stroke menggunakan berbagai metode pembelajaran mesin. Dataset ini berisi informasi pasien yang dapat membantu memprediksi risiko stroke berdasarkan berbagai faktor kesehatan dan demografi.

---

## **Deskripsi Dataset**

Dataset ini mencakup fitur-fitur berikut:

- **id**: ID unik untuk setiap pasien.
- **gender**: Jenis kelamin pasien (Male, Female, Other).
- **age**: Usia pasien.
- **hypertension**: Apakah pasien memiliki hipertensi (0 = Tidak, 1 = Ya).
- **heart_disease**: Apakah pasien memiliki penyakit jantung (0 = Tidak, 1 = Ya).
- **ever_married**: Status pernikahan pasien (Yes, No).
- **work_type**: Jenis pekerjaan pasien (Private, Self-employed, Govt_job, Children, Never_worked).
- **Residence_type**: Tipe tempat tinggal pasien (Urban, Rural).
- **avg_glucose_level**: Rata-rata kadar glukosa dalam darah.
- **bmi**: Indeks massa tubuh pasien.
- **smoking_status**: Status merokok pasien (formerly smoked, never smoked, smokes, Unknown).
- **stroke**: Apakah pasien mengalami stroke (0 = Tidak, 1 = Ya).

---

## **Tujuan Penggunaan**

Dataset ini digunakan untuk:
1. Mengklasifikasikan pasien yang berisiko terkena stroke.
2. Mengidentifikasi faktor-faktor yang berhubungan dengan risiko stroke.
3. Mengevaluasi kinerja algoritma pembelajaran mesin dalam prediksi stroke.

---

## **Sumber Dataset**

Dataset ini diperoleh dari Kaggle: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset. Data telah diolah untuk keperluan analisis ini.

---

## **Struktur Dataset**

File dataset tersedia dalam format CSV:
- **Nama File**: `healthcare-dataset-stroke-data.csv`
- **Jumlah Data**: 5110 baris
- **Jumlah Fitur**: 12 kolom

---

## **Cara Menggunakan Dataset**

### **1. Clone Repository**
Unduh repository ini menggunakan perintah berikut:
```bash
git clone https://github.com/username/dataset-stroke.git
