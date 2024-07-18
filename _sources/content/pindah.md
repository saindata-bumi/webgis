# Menyalin folder dari Github
Kadang kala kita membutuhkan salah satu folder pada suatu repositori github yang harus kita pindahkan kedalam ruang kerja kita. Setelah browsing di https://pypi.org/project saya menemukan package yang memudahkan untuk melakukan itu di https://pypi.org/project/gh-folder-download/. Berikut langkah langkah yang harus dilakukan

1. Install paket tersebut dengan perintah pip install gh-folder-download
2. Tentukan folder yang akan di pindahkan, misal folder di https://github.com/sentinel-hub/eo-learn/tree/master/examples
3. ketik perintah gh-folder-download --url https://github.com/sentinel-hub/eo-learn/tree/master/examples --force
4. Selesai (perhatikan apakah folder sudah berpindah didirekotri kita
   