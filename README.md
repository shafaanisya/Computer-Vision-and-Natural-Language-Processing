# Computer-Vision-and-Natural-Language-Processing
Assignment 3: Computer Vision &amp; Natural Language Processing Artificial Intelligence Track • Startup Campus, Indonesia

## Soal Nomor 1 (Computer Vision - Digital Image Processing)

Kasus : 
  Per bulan Juli 2023, Apple dan Samsung memimpin industri ponsel pintar (smartphone) di seluruh dunia, dengan angka gabungan 52,61% dari total pangsa pasar (market share). Sebagai fitur utama yang wajib
hadir pada smartphone masa kini, Apple dan Samsung berlomba-lomba menciptakan teknologi kamera agar Anda bisa mengabadikan foto terbaik meski dalam kondisi minim cahaya.

● Pada bulan September 2019, Apple memperkenalkan teknologi Deep Fusion (melalui seri iPhone
11) untuk mengatasi tantangan tersebut. Peningkatannya, yang diberi nama Photonic Engine,
diperkenalkan pada September 2022 melalui seri iPhone 14 terbaru.

● Sementara itu, pada bulan Februari 2023, Samsung memperkenalkan teknologi Adaptive
Tetra-squared Pixel Sensor dengan seri Samsung S23 terbarunya sebagai solusi lain untuk
masalah serupa, menjanjikan hasil foto terang yang luar biasa dari gambar bernuansa gelap.
  Kedua teknologi ini bekerja dengan menggabungkan beberapa piksel yang berdekatan menjadi satu
piksel, menggunakan operasi Max Pooling. Tugas Anda sekarang adalah mereplikasi konsep tersebut (mencerahkan foto bernuansa gelap), lalu membandingkan hasilnya dengan pendekatan Contrast
Limited Adaptive Histogram Equation (CLAHE).


## Soal Nomor 2 (Computer Vision - Transfer Learning with Pre-trained CNN)

Kasus : 
  Sebuah fasilitas robot (robotics facility) baru yang berlokasi di Kalimantan Timur, dekat Titik Nol Ibu Kota Negara (IKN) Indonesia, meminta Anda untuk membuat model Computer Vision untuk produk robot baru mereka. Perusahaan meminta Anda untuk mengajari robot cara membaca rangkaian angka. Anda tiba-tiba menyadari bahwa tahap pertama adalah membiarkan robot mengidentifikasi setiap digit dengan benar (0-9). Namun, karena tanggal pengumuman prototipe dipercepat, deadline Anda sangat ketat: Anda hanya memiliki waktu kurang dari satu minggu untuk menyelesaikan pekerjaan. Sebagai pengembang AI profesional, Anda tetap tenang dan tahu bahwa Anda dapat memanfaatkan metode Transfer Learning untuk menyelesaikan masalah ini secara efisien.
  Database Modified National Institute of Standards and Technology (MNIST) berisi 10 digit
tulisan tangan. Semuanya berada dalam skala grayscale (1 channel). Torchvision, sub-library dari PyTorch, memiliki lusinan model terlatih yang dapat Anda pilih dengan mudah. Semua model ini awalnya dilatih pada kumpulan data ImageNet, yang berisi jutaan gambar RGB (3 channel) dan 1.000 kelas.
  Untuk mempermudah, pilihlah ResNet18, DenseNet121, atau Vision Transformer (ViT) sebagai
model dasar (namun canggih) untuk menguji performa klasifikasi gambar. Sekarang, tugas lengkap Anda adalah sebagai berikut.
1. Pilih DenseNet sebagai model pertama untuk bereksperimen, lalu ubah jumlah neuron di lapisan
pertama dan terakhir (karena ImageNet memiliki 1.000 kelas, sedangkan MNIST hanya memiliki
10 kelas; keduanya juga memiliki ukuran gambar dan channel yang berbeda).
2. Tentukan hyperparameter dan latih modelnya (semua layer dilatih dari awal).
3. Plot performa model, baik untuk hasil pelatihan maupun validasi.
4. Sekarang, coba bekukan (freeze, tidak dilatih) beberapa bagian layer: (1) "denseblock1", (2)
"denseblock1" dan "denseblock2". Ini akan menjadi dua model terpisah.
5. Latih kembali setiap model, visualisasikan performanya, dan periksa perbedaannya.
6. BONUS: Bisakah Anda mereplikasi semua langkah di atas dengan model yang berbeda, misalnya
ResNet dan ViT?


## Soal Nomor 3 (Computer Vision - Real-time Object Detection)

1. Coba tiga URL YouTube yang disediakan untuk menguji akurasi YOLOv5.
2. Jawab [ PERTANYAAN ] langsung di notebook, jika ada.
3. Aktifkan T4 GPU di Google Colab, jika diinstruksikan.


## Soal Nomor 4 (Natural Language Processing - Text Classification)

Kasus :
  Dengan ketersediaan smartphone yang semakin luas, masyarakat dapat melaporkan kejadian darurat
yang mereka saksikan secara real-time melalui platform X (dahulu Twitter). Hal ini membuat berbagai lembaga, seperti organisasi bantuan bencana dan agensi berita, semakin tertarik untuk memantau X secara sistematis.
  Sebagai seorang AI Scientist, Anda ditugaskan untuk mengklasifikasikan disaster tweet, yaitu
apakah teks di platform X merupakan sebuah laporan tidak langsung mengenai bencana tertentu. Model BERT (singkatan dari Bidirectional Encoder Representations for Transformers) dapat digunakan untuk menyelesaikan kasus ini.
  Dengan mengimplementasikan teknik fine-tuning, model yang Anda buat dapat membawa
manfaat kedepan untuk:
- Menganalisis pola komunikasi dan respon masyarakat dalam situasi darurat.
- Mengembangkan sistem peringatan dini berbasis Twitter.
- Membantu organisasi bantuan bencana dalam mengoptimalkan respon terhadap kejadian
darurat.
- Menyelidiki dampak media sosial terhadap persepsi publik terhadap bencana.
