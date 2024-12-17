<h1 align="center"> Creating Anime Characters with DCGANs and Keras </h1> <p align="center"> This project utilizes Deep Convolutional Generative Adversarial Networks (DCGANs) built with Keras to generate anime character images from scratch, learning the unique features of anime art.</p> <div align="center"> <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"> <img src="https://img.shields.io/badge/keras-D00000?style=for-the-badge&logo=keras&logoColor=white"> <img src="https://img.shields.io/badge/tensorflow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"> </div>

# Deskripsi Proyek
Proyek ini menggunakan DCGANs untuk menghasilkan gambar karakter anime baru yang realistis dengan mempelajari pola-pola karakteristik dari dataset gambar anime. DCGAN adalah model GAN yang memanfaatkan jaringan konvolusi, membuatnya sangat sesuai untuk tugas-tugas generatif berbasis gambar.

# Fitur
- Generasi Gambar Anime: Menghasilkan karakter anime baru yang realistis dari nol.
- Penyimpanan dan Visualisasi Hasil: Menghasilkan gambar-gambar di setiap epoch untuk memantau kualitas.
- Penyimpanan Model: Simpan model yang telah dilatih untuk digunakan dalam generasi gambar di masa mendatang.

# Teknologi yang Dipakai:
- Deep Convolutional Generative Adversarial Networks (DCGANs): Digunakan untuk membuat model generatif berbasis gambar.
- Keras dengan TensorFlow: Keras adalah framework untuk membangun model deep learning, dengan TensorFlow sebagai backend.
- Matplotlib: Untuk visualisasi hasil generasi gambar selama pelatihan.
- NumPy: Untuk operasi array dan manipulasi data.
- GitHub: Untuk menyimpan kode sumber proyek, model, dan hasil pelatihan.

# Analisis Teknologi yang Dipakai:
- DCGAN adalah model GAN (Generative Adversarial Network) yang telah dimodifikasi dengan menggunakan Convolutional Neural Networks (CNN) di kedua bagian Generator dan Discriminator. CNN cocok untuk tugas pengolahan gambar karena dapat menangkap pola spasial dalam gambar.
Generator bertugas menghasilkan gambar dari noise acak. Discriminator bertugas untuk membedakan antara gambar asli (dari dataset) dan gambar yang dihasilkan oleh generator. Kombinasi keduanya memungkinkan sistem untuk menghasilkan gambar anime yang semakin realistis dari waktu ke waktu.
- Keras dan TensorFlow digunakan sebagai framework untuk membangun dan melatih model deep learning. Keras menyediakan API yang lebih mudah digunakan untuk membangun model berbasis TensorFlow. Keras menawarkan antarmuka yang ramah pengguna untuk menulis dan menjalankan model deep learning. TensorFlow adalah library yang digunakan sebagai backend untuk pengolahan komputasi yang lebih besar dan untuk mempercepat pelatihan menggunakan GPU.
