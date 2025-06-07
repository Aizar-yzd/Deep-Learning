# Laporan Proyek Hands-On Machine Learning

Selamat datang di repositori proyek untuk mata kuliah Machine Learning. Repositori ini berisi kumpulan Jupyter Notebook yang mereproduksi kode dan menjelaskan konsep-konsep inti dari setiap bab dalam buku referensi utama kami.

## Tujuan Proyek

Tujuan utama dari proyek ini adalah untuk memperdalam pemahaman dan keterampilan praktis dalam mengimplementasikan konsep-konsep inti Machine Learning. Ini dicapai melalui reproduksi kode secara langsung dan penyusunan penjelasan teoretis yang terstruktur berdasarkan materi dari buku:

**Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition** oleh Aurélien Géron.

## Struktur Repositori

Repositori ini disusun berdasarkan bab dari buku. Setiap folder atau notebook akan sesuai dengan satu bab, berisi:
1.  **Reproduksi Kode:** Implementasi kode Python yang relevan dari bab tersebut.
2.  **Penjelasan Teoretis:** Ringkasan dan penjelasan konsep-konsep kunci yang dibahas.
3.  **Latihan:** Jawaban dan implementasi dari soal-soal latihan di akhir setiap bab.

---

## Panduan Chapter

Berikut adalah panduan singkat untuk konten di setiap chapter.

### Bagian I: Fundamental Machine Learning

#### **Chapter 1: The Machine Learning Landscape**
* **Isi:** Pengenalan fundamental tentang apa itu Machine Learning, mengapa ia berguna, serta berbagai jenis sistem ML (Supervised, Unsupervised, Reinforcement Learning, dll.). Bab ini juga membahas tantangan utama dalam ML seperti *overfitting* dan *underfitting*.
* **Status:** Teoretis, tidak ada kode untuk direproduksi selain latihan.

#### **Chapter 2: End-to-End Machine Learning Project**
* **Isi:** Panduan praktis langkah demi langkah untuk sebuah proyek regresi, mulai dari pengambilan data, eksplorasi, persiapan (termasuk pipeline), hingga pelatihan dan penyempurnaan model.
* **Status:** Praktis, banyak kode yang direproduksi.

#### **Chapter 3: Classification**
* **Isi:** Fokus pada tugas klasifikasi menggunakan dataset MNIST. Membahas metrik kinerja seperti matriks konfusi, presisi, recall, dan kurva ROC. Mencakup klasifikasi biner, multikelas, dan multioutput.
* **Status:** Praktis, implementasi berbagai model klasifikasi.

#### **Chapter 4: Training Models**
* **Isi:** Menyelami algoritma pelatihan untuk model linear. Mencakup Regresi Linear (menggunakan Normal Equation dan Gradient Descent), Regresi Polinomial, kurva pembelajaran, regularisasi (Ridge, Lasso, Elastic Net), dan Regresi Logistik.
* **Status:** Gabungan teori dan implementasi algoritma dari awal.

#### **Chapter 5: Support Vector Machines (SVMs)**
* **Isi:** Penjelasan mendalam tentang SVM, salah satu model ML yang paling kuat. Mencakup klasifikasi margin besar, SVM non-linear menggunakan *kernel trick*, dan regresi SVM.
* **Status:** Implementasi dan visualisasi SVM.

#### **Chapter 6: Decision Trees**
* **Isi:** Membahas cara kerja Decision Trees untuk tugas klasifikasi dan regresi. Mencakup algoritma pelatihan CART, regularisasi *hyperparameter*, dan visualisasi pohon keputusan.
* **Status:** Praktis, melatih dan menyetel Decision Trees.

#### **Chapter 7: Ensemble Learning and Random Forests**
* **Isi:** Menjelaskan kekuatan menggabungkan beberapa model (ensembles) untuk mendapatkan kinerja yang lebih baik. Mencakup metode Bagging, Pasting, Boosting (AdaBoost, Gradient Boosting), Stacking, dan pengenalan Random Forests.
* **Status:** Implementasi berbagai teknik ensemble.

#### **Chapter 8: Dimensionality Reduction**
* **Isi:** Mengatasi masalah "kutukan dimensi" (*curse of dimensionality*). Memperkenalkan teknik reduksi dimensi utama seperti Principal Component Analysis (PCA), Kernel PCA, dan LLE.
* **Status:** Visualisasi dan implementasi teknik reduksi dimensi.

#### **Chapter 9: Unsupervised Learning Techniques**
* **Isi:** Menjelajahi teknik *unsupervised learning* seperti Clustering (K-Means, DBSCAN), Anomaly Detection, dan Density Estimation menggunakan Gaussian Mixture Models.
* **Status:** Implementasi berbagai algoritma unsupervised.

### Bagian II: Jaringan Saraf Tiruan dan Deep Learning

#### **Chapter 10: Introduction to Artificial Neural Networks with Keras**
* **Isi:** Pengenalan Jaringan Saraf Tiruan (ANN), mulai dari Perceptron hingga Multi-Layer Perceptrons (MLP). Menunjukkan cara membangun, melatih, dan mengevaluasi model menggunakan API Keras (Sequential, Functional, dan Subclassing).
* **Status:** Fondasi praktis untuk Deep Learning dengan Keras.

#### **Chapter 11: Training Deep Neural Networks**
* **Isi:** Membahas tantangan dalam melatih jaringan saraf yang dalam, seperti masalah *vanishing/exploding gradients*. Meliputi teknik-teknik penting seperti inisialisasi, fungsi aktivasi, Batch Normalization, *transfer learning*, dan optimizers canggih (Adam, Nadam, dll).
* **Status:** Teknik-teknik canggih untuk meningkatkan pelatihan model.

#### **Chapter 12: Custom Models and Training with TensorFlow**
* **Isi:** Menyelami API TensorFlow tingkat rendah untuk kontrol yang lebih besar. Meliputi pembuatan *loss function*, metrik, layer, model, dan *training loop* kustom. Memperkenalkan TF Functions dan AutoGraph untuk optimalisasi.
* **Status:** Kustomisasi tingkat lanjut di TensorFlow.

#### **Chapter 13: Loading and Preprocessing Data with TensorFlow**
* **Isi:** Penggunaan `tf.data` API untuk membangun pipeline input data yang efisien. Membahas format TFRecord, layer pra-pemrosesan Keras, dan TF Transform untuk pra-pemrosesan data dalam skala besar.
* **Status:** Teknik manajemen data untuk proyek Deep Learning.

#### **Chapter 14: Deep Computer Vision Using Convolutional Neural Networks**
* **Isi:** Pengantar Convolutional Neural Networks (CNN) untuk Computer Vision. Menjelajahi arsitektur CNN (layer konvolusional dan pooling) dan membahas model-model canggih seperti LeNet, AlexNet, GoogLeNet, dan ResNet untuk tugas deteksi objek dan segmentasi.
* **Status:** Implementasi CNN untuk tugas-tugas berbasis gambar.

#### **Chapter 15: Processing Sequences Using RNNs and CNNs**
* **Isi:** Membahas penggunaan Recurrent Neural Networks (RNNs) untuk memproses data sekuensial seperti time series. Meliputi sel LSTM dan GRU, serta penggunaan CNN 1D untuk sekuens (WaveNet).
* **Status:** Model untuk data sekuensial.

#### **Chapter 16: NLP with RNNs and Attention**
* **Isi:** Penerapan RNN untuk Natural Language Processing (NLP). Membahas model Encoder-Decoder, mekanisme *attention*, dan arsitektur Transformer yang revolusioner.
* **Status:** Aplikasi Deep Learning untuk pemrosesan bahasa.

#### **Chapter 17: Representation Learning with Autoencoders and GANs**
* **Isi:** Menjelajahi pembelajaran tak terarah (*unsupervised learning*) untuk *representation learning* menggunakan Autoencoders. Juga memperkenalkan Generative Adversarial Networks (GANs) untuk menghasilkan data baru yang realistis.
* **Status:** Model generatif dan *representation learning*.

#### **Chapter 18: Reinforcement Learning**
* **Isi:** Pengantar ke dunia Reinforcement Learning. Mencakup konsep inti seperti *policy gradients*, Q-Learning, dan Deep Q-Networks (DQN). Menggunakan OpenAI Gym dan pustaka TF-Agents.
* **Status:** Membangun agen cerdas yang belajar dari interaksi.

#### **Chapter 19: Training and Deploying TensorFlow Models at Scale**
* **Isi:** Membahas siklus hidup model setelah pelatihan. Meliputi cara mendeploy model ke produksi menggunakan TF Serving dan Google Cloud AI Platform, mengoptimalkan model untuk perangkat mobile (TFLite), dan melatih model secara terdistribusi di banyak GPU dan server.
* **Status:** Membawa model dari lab ke dunia nyata.
