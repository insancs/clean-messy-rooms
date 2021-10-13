<h1 align="center"> Clean Vs Messy Rooms Classifier using Tensorflow </h1>

## Overview
Pada projek ini yaitu bertugas untuk mengklasifikasi gambar sebuah ruangan apakah rapi atau berantakan. Arsitektur model dibangun dengan menggunakan Convolutional Neural Network (CNN) dari library Tensorflow. 

## Dataset
Dataset pada projek ini diperoleh dari [Kaggle](https://www.kaggle.com/cdawn1/messy-vs-clean-room). Gambar terdiri dari dua kelas, yaitu ruangan rapi dan berantakan. Dataset berjumlah ~200 gambar ruangan. Terdapat 192 gambar dalam training set (96 gambar per kelas); 20 gambar (10 gambar per kelas) dalam validation set; 10 gambar (5 per kelas) di set tes. Lokasi ruangan beragam, termasuk kamar tidur, ruang keluarga, ruang makan, ruang belajar, dan dapur, yang mungkin membantu mencegah model menangkap fitur yang tidak terkait tetapi lebih fokus pada "kekacauan".

## Work Steps
<ol>
  <li>Import library</li>
  <li>Download and extract file</li>
  <li>Storing training and validation data sets into variables</li>
  <li>Data pre-processing using image augmentation</li>
  <li>Prepare train data</li>
  <li>Building a model architecture with CNN</li>
  <li>Plotting accuracy and loss</li>
  <li>Predict image</li>
</ol>  

## Visualize Accuracy and Loss 
<p align="center">
    <img src="images/accuracy_loss.JPG" width="500" height="200">
</p>

## Predict Model
<p align="center">
    <img src="images/predict.JPG" width="400">
</p>
