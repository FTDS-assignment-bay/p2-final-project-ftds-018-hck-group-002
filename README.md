[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15655224&assignment_repo_type=AssignmentRepo)
# Final-Project
# **Intellagent**

![logo intellagent](https://github.com/FTDS-assignment-bay/p2-final-project-ftds-018-hck-group-002/blob/main/logo-1.png)<br>
<p align="center" width="100%">
    *Kecerdasan di balik setiap keputusan hebat.* <br>
</p>

## Pengenalan
"Intellagent" adalah platform berbasis AI yang menyederhanakan dan mengoptimalkan proses peluncuran produk Anda. Platform ini menggunakan tim agen AI khusus untuk menganalisis masukan pengguna dan memberikan strategi berbasis data untuk keberhasilan peluncuran. Dengan wawasan yang dapat ditindaklanjuti dan rekomendasi yang dipersonalisasi, Intellagent memastikan peluncuran produk Anda berjalan lancar dan berdampak.

Proyek ini didukung oleh kerangka kerja **CrewAI**, yang mengotomatisasi pembuatan laporan dan rencana peluncuran produk secara terperinci. CrewAI mengoordinasikan agen AI otonom, memungkinkan kolaborasi dan pelaksanaan tugas-tugas kompleks dengan efisien.

## Kerangka Kerja
Proyek ini didukung oleh tim agen AI yang berperan, dikoordinasikan melalui CrewAI. Setiap agen diberikan latar belakang, tugas, alat, dan hasil yang diharapkan untuk melaksanakan perannya. Proyek ini terdiri dari lima agen yang masing-masing berfokus pada aspek-aspek berbeda dari peluncuran produk. Mereka menggunakan **Exa Search Tool**, yang memungkinkan mereka mengumpulkan informasi daring untuk dianalisis. Bersama-sama, mereka berkolaborasi untuk memberikan laporan menyeluruh tentang strategi terbaik untuk meluncurkan produk berdasarkan masukan yang diberikan.

## Menjalankan Script
- **Konfigurasi Lingkungan**: Salin `.env.example` dan atur variabel lingkungan untuk OpenAI dan Exa.
- **Instalasi Dependensi**: Jalankan `pip install -r requirements.txt`.
- **Jalankan Script**: Jalankan `streamlit run app.py` dan masukkan ide Anda.

## Detail & Penjelasan
- **Menjalankan Script**: Jalankan `streamlit run app.py` dan masukkan informasi yang diminta saat diminta. Script ini akan memanfaatkan kerangka kerja CrewAI untuk membuat laporan peluncuran produk untuk Anda.
- **Komponen Utama**:
  - `./app.py`: File script utama.
  - `./tasks.py`: File utama berisi prompt tugas.
  - `./agents.py`: File utama berisi pembuatan agen.
  - `./tools.py`: File utama berisi alat untuk agen.
