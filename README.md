# Computer-Vision
Task 1 (Digital Image Processing using OpenCV2)
Melakukan untuk menggabungkan beberapa piksel yang berdekatan menjadi satu piksel, menggunakan operasi Max Pooling. Dalam hal ini, tugas Anda untuk mereplikasi konsep tersebut (mencerahkan foto dengan warna gelap), lalu membandingkan hasilnya dengan pendekatan lain, yaitu Contrast Limited Adaptive Histogram Equation (CLAHE).

Task 2 (Transfer Learning using Torchvision Pre-trained CNN Models)
(MNIST) berisi 10 digit tulisan tangan. Semuanya berada dalam skala grayscale (1 channel). Torchvision, sub-library dari PyTorch, memiliki lusinan model terlatih yang dapat Anda pilih dengan mudah. Semua model ini awalnya dilatih pada kumpulan data ImageNet, yang berisi jutaan gambar RGB (3 channel) dan 1.000 kelas. Untuk mempermudah, pilihlah ResNet18, DenseNet121, atau Vision Transformer (ViT) sebagai model dasar (namun canggih) untuk menguji performa klasifikasi gambar. Dalam tugas tersebut diantaranya :
1. Pilih DenseNet sebagai model pertama untuk bereksperimen, lalu ubah jumlah neuron di lapisan pertama dan terakhir.
2. Buatlah plot performa model, baik untuk hasil pelatihan maupun validasi.
3. Kemudian lakukan percobaan untuk bekukan (freeze, tidak dilatih) beberapa bagian layer: (1) "denseblock1", (2)
"denseblock1" dan "denseblock2".
4. Latih kembali setiap model, visualisasikan performanya, dan lihatlah perbedaannya.
5. Lakukan hal yang sama pada model yang lainnya.
