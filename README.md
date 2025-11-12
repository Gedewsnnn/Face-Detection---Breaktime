
<div align="center">
  <img src="./assets/cover.jpg" alt="latar" width="600px"/>
</div>

# Face Detection Breaktime
<div align="justify">

Sistem ini adalah program otomatis berbasis kamera yang berfungsi untuk mendeteksi kehadiran pegawai, memantau waktu kerja dan istirahat, serta memberikan pengaturan siklus kerja secara cerdas dan real-time.
Didesain untuk lingkungan kerja industri, sistem ini mampu mengenali wajah pengguna, mengaburkan latar belakang (background blur), melakukan auto zoom ke wajah, serta menonaktifkan kamera secara otomatis saat waktu istirahat dimulai. [Slide Presentasi ](https://www.canva.com/design/DAG3nFcayl8/fTS7ACN6fCEIP4v0mZF21A/edit)
</div>

`PENGOLAHAN CITRA - PROGRAM STUDI TEKNIK ELEKTRONIKA - POLITEKNIK ELEKTRONIKA NEGERI SURABAYA`

`DOSEN PENGAMPU : Akhmad Hendriawan ST, MT`
`NIP. 197501272002121003`

# Tujuan
1. Mendeteksi kehadiran pegawai melalui kamera dengan akurasi tinggi (Haar Cascade).
2. Mengatur siklus kerja–istirahat otomatis berdasarkan waktu yang dikonfigurasi.
3. Menampilkan status aktivitas secara real-time dengan tampilan GUI interaktif berbasis OpenCV.
4. Mengoptimalkan efisiensi kerja serta mendukung keamanan dan kesehatan pekerja.

# Fitur Utama

| Fitur                                           | Deskripsi                                                                                         |
| :---------------------------------------------- | :------------------------------------------------------------------------------------------------ |
| 👁️ **Face Detection (Haar Cascade)**           | Sistem mengenali wajah pegawai untuk memastikan kehadiran di depan kamera.                        |
| 💡 **State Machine Otomatis**                   | Sistem berpindah otomatis antara mode **KERJA → TRANSISI → ISTIRAHAT → PERSIAPAN** sesuai durasi. |
| 🎥 **Auto Zoom Kamera**                         | Kamera melakukan *zoom-in* otomatis ke wajah pengguna saat terdeteksi, dengan transisi halus.     |
| 🌀 **Background Blur Dinamis**                  | Latar belakang diburamkan secara otomatis, menjaga privasi dan fokus pada wajah pengguna.         |
| 🕒 **Timer Real-Time**                          | Menampilkan waktu kerja, waktu istirahat, dan sisa waktu persiapan langsung di tampilan video.    |
| 🔄 **Kamera Otomatis On/Off**                   | Kamera dimatikan selama istirahat dan otomatis aktif kembali saat sesi kerja dimulai.             |
| 🧾 **Konfigurasi CLI (Command Line Interface)** | Semua parameter dapat diatur melalui argumen terminal seperti durasi, zoom, dan blur.             |



# Teammates
<div align="center">
  <img src="./assets/anggota.jpg" alt="latar" width="600px"/>
</div>
<div align="center">


| No. | Nama                | NRP           | GitHub                                 |
| :--:| :------------------:| :-------------:| :------------------------------------: |
| 1   |  M. Adib Tantowi Jauhari   | 2122600001  | [GitHub](https://github.com/AdibTantowi) |
| 2   | Rizka Sugiharto   | 2122600008    | [GitHub](https://github.com/Rizka-sgh) |
| 3   | Muhammad Lukman Al Khakim        | 2122600010     | [GitHub](https://github.com/lukmanhakim100523-droid) |
| 4   | I Gede Wahyu Satria Nugraha        | 2122600033      | [GitHub](https://github.com/Gedewsnnn) |
| 5   | Bachtiar Arif Nurdiansyah     | 2122600058      | [GitHub](https://github.com/BachtiarArif) |


</div>

# Technologies Used
- Python 3.x — Bahasa utama.
- OpenCV (cv2) — Deteksi wajah, pengolahan citra, dan tampilan GUI video.
- NumPy — Operasi matriks dan manipulasi gambar.
- Argparse — Membaca argumen CLI untuk konfigurasi program.
- Datetime / Time — Manajemen durasi kerja dan waktu istirahat.

# Daftar Isi
- [Diagram Alur](#Diagram-Alur)
- [Output](HASIL%20TES.md)
- [Program](PROGRAM/)

# Diagram Alur
<div align="center">
  <img src="./assets/Flowchart2.png" alt="latar" width="600px"/>
</div>
