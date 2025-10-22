# 📱 Laporan Praktikum Pemrograman Mobile  
## **Jobsheet 8: Aplikasi OCR (Optical Character Recognition)**  

### 👩‍💻 **Disusun Oleh:**  
**Queenadhynar Azarine Dwipa A.**  
NIM: 2341760109  
Kelas: SIB 3C  
Jurusan Teknologi Informasi  
Politeknik Negeri Malang  
Tahun Ajaran 2025/2026  

---

## 🧩 **Langkah-langkah Praktikum**

### **Langkah 1: Buat Proyek Baru**
Membuat proyek Flutter baru dengan nama **OCR App**  
📸 **Screenshot:**  
![Langkah 1 - Buat Proyek Baru](assets/1.png)

---

### **Langkah 2: Tambahkan Plugin**
Menambahkan dependensi **Google ML Kit OCR** ke dalam file `pubspec.yaml`:  
📸 **Screenshot:**  
![Langkah 2 - Tambahkan Plugin](assets/2.png)

Kemudian menjalankan perintah pub get:  
📸 **Screenshot:**  
![Langkah 2 - Jalankan Pub Get](assets/3.png)

---

### **Langkah 3: Tambahkan Izin Kamera (Android)**
Buka file `AndroidManifest.xml` dan tambahkan izin kamera.  
📸 **Screenshot:**  
![Langkah 3 - Izin Kamera](assets/4.png)

---

### **Langkah 4: Buat Struktur Folder**
Struktur folder di dalam proyek Flutter:  
📸 **Screenshot:**  
![Langkah 4 - Struktur Folder](assets/5.png)

**File: lib/main.dart**  
📸 **Screenshot:**  
![File main.dart](assets/6.png)

**File: lib/screens/splashscreen.dart**  
📸 **Screenshot:**  
![File splashscreen.dart](assets/7.png)

**File: lib/screens/homescreen.dart**  
📸 **Screenshot:**  
![File homescreen.dart](assets/8.png)

**File: lib/screens/scanscreen.dart**  
📸 **Screenshot:**  
![File scanscreen.dart](assets/9.png)

**File: lib/screens/resultscreen.dart**  
📸 **Screenshot:**  
![File resultscreen.dart](assets/10.png)

---

## 🧠 **Jawaban Tugas Praktikum**

### 1️⃣ Jalankan aplikasi di emulator atau HP.
📸 **Screenshot:**  
![Menjalankan aplikasi](assets/p.png)

---

### 2️⃣ Lakukan scan terhadap teks cetak (misal: buku, koran, atau layar HP).
📸 **Screenshot:**  
![Proses scan teks cetak](assets/prak.png)

---

### 3️⃣ Amati hasil OCR yang muncul.
📸 **Screenshot:**  
![Hasil OCR](assets/prak1.png)

---

### 4️⃣ Analisis Hasil OCR

a. **Apakah semua teks terbaca dengan akurat? Mengapa?**  
📸 **Screenshot:**  
![Analisis Akurasi OCR](assets/tugas_prak_2.png)  
![Analisis Tambahan](assets/prak_2.png)

Tidak semua teks terbaca dengan akurat.  
Tingkat akurasi OCR bergantung pada kualitas gambar, pencahayaan, kontras teks, serta jenis dan ukuran font.  
Jika gambar buram atau teks tidak jelas, hasilnya bisa kurang tepat.

---

b. **Sebutkan 2 contoh aplikasi nyata yang menggunakan OCR:**  
- **Google Lens** → membaca & menerjemahkan teks dari gambar.  
- **Microsoft Office Lens / Adobe Scan** → memindai dokumen dan menyimpannya dalam bentuk PDF editabel.

---

c. **Apa kegunaan fitur OCR dalam kehidupan sehari-hari?**  
OCR digunakan untuk mengubah teks dari gambar menjadi teks digital yang bisa disalin, diterjemahkan, atau disimpan.  
Contohnya digunakan untuk memindai dokumen, kwitansi, atau teks dari foto agar mudah diolah kembali.

---

## 🧾 **Kesimpulan**
Aplikasi OCR berbasis Flutter ini dapat mengenali teks dari gambar menggunakan **Google ML Kit**,  
namun akurasinya bergantung pada kualitas input.  
Fitur ini sangat bermanfaat dalam digitalisasi dokumen dan efisiensi pengolahan data teks.

---
