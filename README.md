# soal untuk pretest-data-engineer

## Knowledge Base

1. Apa yang Anda ketahui tentang Data Engineer ?
2. Ceritakan pengalaman Anda dalam mengolah data?
3. Apa yang kamu ketahui tentang AI
4. Mengapa Data menjadi sesuatu yang sangat penting sekarang, dan apa dampak dari kebocoran data
5. Apa yg anda ketahui mengenai model generative AI ? da apa saja penerapannya

## Answer

1. Menurut saya data engineer ialah orang yang bekerja dengan mengumpulkan dan mempersiapkan data.
2. Saya pernah melakukan sentiment analysis di twitter untuk capres tahun 2024, dan melakukan visualisasi data untuk proyek IoT lomba Innovillage tahun 2024.
3. Yang saya pahami AI itu sistem cerdas yang memproses big data kemudian menjalankan hasil optimal.
4. Karena era digital sekarang yang mana data memiliki harga atau nilai yang tinggi, dampaknya tentu keamanan kemudian finansial.
5. Yg saya ketahui merupakan model yg bisa menghasilkan teks, gambar, audio, atau video, contohnya, chatGPT, gemini, dll.

## Soal Coding

studi kasus =
seorang data engineer diharuskan oleh klien untuk membuat
blueprint data orchestration di sebuah tools yaitu Kestra.
klien ingin memproses data review lazada (review-lazada.csv).

kami sudah menyediakan akses kestra di
[Kestra] https://kestra-magang.t-dev.site/
silahkan pelajari kestra lihat dokumentasinya
dan silahkan lakukan proses dibawah ini:

1. satu flows untuk proses data cleansing dimana bersihkan data reviewnya kemudian export ke csv
2. satu flows untuk proses menghitung sentiment analysis berdasarkan kolom rating

Keterangan :
flow kestra dan script python sertakan dalam git kalian ketika pelaporan

## Result

1. data_cleaning
   flow : (data_cleaning.txt)
   csv : (review_clean.csv)
2. klasifikasi
   flow : (klasifikasi.txt)
   csv : (review_result.csv)
