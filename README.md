# Tugas Case-Based Reasoning (CBR)

Repositori ini berisi implementasi sistem **Case-Based Reasoning (CBR)** untuk memenuhi tugas mata kuliah. Proyek ini mencakup seluruh siklus CBR, mulai dari persiapan data hingga penarikan kesimpulan berdasarkan basis kasus.

## 📂 Struktur Repositori

Sesuai dengan ketentuan tugas, repositori ini disusun sebagai berikut:

- **/data/**: Berisi file dataset mentah (*raw*) dan data yang telah diproses (*processed*).
- **/notebooks/**: Berisi file Jupyter Notebook (.ipynb) yang disusun secara sistematis per tahap pengerjaan.
- **requirements.txt**: Daftar library Python yang diperlukan untuk menjalankan proyek ini.
- **README.md**: Panduan instalasi dan penggunaan repositori ini.

---

## 🛠️ Panduan Instalasi

Pastikan Anda telah menginstal Python (versi 3.8 atau lebih baru) di perangkat Anda. Ikuti langkah-langkah berikut:

1. **Clone Repositori**
   ```bash
   git clone https://github.com/mahardikaa15/Tugas-Case-based-Reasoning.git
   cd Tugas-Case-based-Reasoning

## Instal Library (Requirements)
Gunakan perintah berikut untuk menginstal semua library yang dibutuhkan:
```text
pip install -r requirements.txt
```

## 🚀 Pipeline End-to-End

Untuk menjalankan proyek ini dari awal hingga akhir, silakan buka folder notebooks/ dan jalankan notebook sesuai urutan nomor:
1. 01_Data_Preprocessing.ipynb
- Melakukan pembersihan data.
- Normalisasi data jika diperlukan.
- Menyimpan data hasil proses ke folder /data/.
  
2. 02_CBR_Implementation.ipynb
- Retrieve: Mencari kasus serupa dalam basis data menggunakan perhitungan kemiripan (similarity).
- Reuse: Menggunakan solusi dari kasus lama untuk kasus baru.
- Revise: Melakukan penyesuaian solusi jika diperlukan.
- Retain: Menyimpan kasus baru ke dalam basis kasus (penambahan pengetahuan).

## 💻 Contoh Perintah Eksekusi

1. Menjalankan Jupyter Notebook
Jika Anda ingin melihat proses tahap demi tahap, jalankan perintah ini di terminal:
jupyter notebook notebooks/01_Data_Preprocessing.ipynb

2. Menjalankan via Skrip (Jika Ada)
Jika sistem telah diintegrasikan ke dalam file python utama:
python main.py

## 🧪 Library Utama yang Digunakan
- pandas: Untuk manipulasi dan analisis data.
- numpy: Untuk perhitungan numerik/vektor similarity.
- scikit-learn: Untuk prapemrosesan atau perhitungan jarak.
- jupyter: Untuk menjalankan notebook interaktif.

### 💡 Hal penting yang harus Anda lakukan sekarang:

1.  **Buat file `requirements.txt`**:
    Pastikan file ini ada di folder utama. Anda bisa mengisinya dengan daftar library yang Anda pakai. Jika bingung, isi saja dengan ini:
    ```text
    pandas
    numpy
    scikit-learn
    notebook
    ```
2.  **Organisir Notebook**:
    Pastikan file di folder `/notebooks/` memiliki nama yang jelas, contoh: `01_Preprocessing.ipynb` dan `02_CBR_System.ipynb`.
3.  **Pastikan Data Ada**:
    Upload file CSV/Excel dataset Anda ke folder `/data/`.
4.  **Ubah ke Public**:
    Pergi ke tab **Settings** di GitHub repositori tersebut, scroll paling bawah ke **Danger Zone**, pastikan statusnya **Public**. Jika masih private, dosen tidak akan bisa menilai.
