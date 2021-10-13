<h1 align="center"> Clean Vs Messy Rooms Classifier using Tensorflow </h1>
# Overview
Pada projek ini yaitu bertugas untuk mengklasifikasi gambar sebuah ruangan apakah rapi atau berantakan. Arsitektur model dibangun dengan menggunakan Convolutional Neural Network (CNN) dari library Tensorflow. 

# Dataset
Dataset pada projek ini diperoleh dari Kaggle. Gambar terdiri dari dua kelas, yaitu ruangan rapi dan berantakan. Dataset berjumlah ~200 gambar ruangan. Terdapat 192 gambar dalam training set (96 gambar per kelas); 20 gambar (10 gambar per kelas) dalam validation set; 10 gambar (5 per kelas) di set tes. Lokasi ruangan beragam, termasuk kamar tidur, ruang keluarga, ruang makan, ruang belajar, dan dapur, yang mungkin membantu mencegah model menangkap fitur yang tidak terkait tetapi lebih fokus pada "kekacauan".

# Work Steps
<ol>
  <li>Import library</li>
  <li>Download an extract file</li>
  <li>Stores the directory of each class in the train directory and validattion into a variable.</li>
  <li>Data pre-procesing using image augmentation</li>
  <li>Prepare train data</li>
  <li>Building a model architecture with CNN</li>
  <li>Predict image</li>
</ol>  
