# 🎬 AI vs Original Video Forensic Dashboard

Aplikasi berbasis web (*dashboard*) interaktif yang memanfaatkan teknik *Computer Vision* dan pemrosesan video untuk mendeteksi serta menganalisis keaslian berkas video dari manipulasi Generative AI (seperti Deepfake, Sora, Runway, dll.).

Proyek ini dibangun menggunakan **Streamlit** untuk antarmuka pengguna dan **OpenCV** untuk analisis ekstraksi fitur spasial serta temporal.

---

## 🚀 Fitur Utama
* **Video Upload & Preview:** Mengunggah dan memutar berkas video (.mp4/.avi) secara langsung di peramban.
* **Spatial Feature Extraction:** Menganalisis kerapatan tekstur dan konsistensi ketajaman objek per frame menggunakan *Laplacian Variance Mapping*.
* **Temporal Consistency Analysis:** Mendeteksi anomali atau *flicker* spasial antar waktu guna mengidentifikasi cacat visual (*artifacts*) bawaan generator AI.
* **Forensic Metrics:** Menampilkan skor persentase probabilitas apakah video merupakan hasil kecerdasan buatan atau rekaman asli kamera ponsel (*original kameraphone*).

---

## 🛠️ Prasyarat & Instalasi

Untuk menjalankan proyek ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

1. **Klon repositori ini:**
   ```bash
   git clone [https://github.com/username-anda/ai-video-detector.git](https://github.com/username-anda/ai-video-detector.git)
   cd ai-video-detector
