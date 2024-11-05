<div align="center"><h1>Text Sentiment Analysis using Caikit and Hugging Face</h1></div>

## 👨‍🔧 Project Overview:
Projek ini berisi percobaan membuat aplikasi sederhana untuk melakukan
analisis sentimen menggunakan pre-trained model dari HuggingFace yang dikolaborasikan
dengan Caikit dan gRPC untuk membuat sistem yang modular dan cepat.

## 🌏 Environment:
Skills Network Cloud IDE (IBM)

## 🛠 Tech Stack 🛠
<div align="center">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Caikit-1D5F74?style=for-the-badge&logo=undefined&logoColor=white" alt="Caikit" />
    <img src="https://img.shields.io/badge/Hugging_Face-FF6F20?style=for-the-badge&logo=Huggingface&logoColor=white" alt="Hugging Face" />
    <img src="https://img.shields.io/badge/gRPC-7A2D3E?style=for-the-badge&logo=grpc&logoColor=white" alt="gRPC" />
</div>

## ⚙ Installation Instructions:
1. Buka terminal dan buatlah sebuah virtual environment
2. Install seluruh library yang dibutuhkan pada requirements.txt

## 💡 Usage:
1. Setelah semua terinstall, aktifkan virtual environment
2. Jalankan start_runtime.py
3. Buat terminal baru, buka client.py dan sesuaikan teks yang ingin diprediksi
4. Jalankan client.py

## 🕵️‍♀️ Analysis:
Projek ini sangat menarik karena menggabungkan HuggingFace sebagai penyedia pre-trained
serta Caikit sebagai framework untuk mendukung pembuatan kode yang modular, sehingga
akan lebih mudah dalam proses maintenance. Selain itu, protokol komunikasi antara
pengguna dan model menggunakan gRPC, yang memastikan respon aplikasi menjadi lebih cepat
karena komponen protobuf yang digunakan pada gRPC.
