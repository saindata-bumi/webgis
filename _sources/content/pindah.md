# Menyalin folder dari Github
Kadang kala kita membutuhkan salah satu folder pada suatu repositori github yang harus kita pindahkan kedalam ruang kerja kita. Setelah browsing di [https://pypi.org/project] saya menemukan package yang memudahkan untuk melakukan itu di https://pypi.org/project/gh-folder-download/. Berikut langkah langkah yang harus dilakukan

1. Install paket tersebut dengan perintah pip install gh-folder-download
2. Tentukan folder yang akan di pindahkan, misal folder di [https://github.com/sentinel-hub/eo-learn/tree/master/examples]
3. ketik perintah gh-folder-download --url [https://github.com/sentinel-hub/eo-learn/tree/master/examples --force]
4. Selesai (perhatikan apakah folder sudah berpindah didirekotri kita)

# Mengextract file zip, rar  

1. pip install patool
2. tampatkan file pada diretory aktif misalkan contoh.zip
3. Ketik pada terminal patool extract contoh.zip
4. Selesai

## Menyalin folder dari google drive
Seringkali kita melakukan penyimpanan di google drive dalam sebuah folder. Misalkan kita telah men-share folder kita dengan link  https://drive.google.com/drive/folders/1iOSDorku0NS3z03bSEbM0uxhJPtcnXVQ?usp=sharing. Kode " 1iOSDorku0NS3z03bSEbM0uxhJPtcnXVQ" adalah ID folder yang kita share.  Untuk menyalin sebuah folder dari google drive ke direktori kita silahkan ikuti langkah berikut.

1. Install model "pip install gdrive"
2. Ketik perintah "gdown https://drive.google.com/drive/folders/1iOSDorku0NS3z03bSEbM0uxhJPtcnXVQ -O pindahan --folder

Ket: pindahan adalah nama folder yang akan dibentuk direktori aktif kita tempat menyalin insi dari folder yang disali

```