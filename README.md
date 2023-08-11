# IT job recomendation
Sebuah program untuk membantu merekomendasikan pekerjaan IT berdasarkan dari **'Kualifikasi yang Diperlukan', 'Kelayakan', 'Judul', 'Deskripsi Pekerjaan', 'Persyaratan Pekerjaan'**

## Latar Belakang
<p align="justify"> Industri Teknologi Informasi (IT) telah menjadi motor utama dalam transformasi digital global. Perkembangan seperti kecerdasan buatan, komputasi awan, dan keamanan siber menciptakan permintaan tinggi akan tenaga ahli IT di berbagai sektor. Peluang pekerjaan dalam IT sangat beragam, mulai dari pengembangan perangkat lunak hingga analis data. </p>

<p align="justify"> Namun, dinamika industri ini mengharuskan individu untuk selalu mengikuti perkembangan terkini. Rekomendasi pekerjaan di bidang IT diperlukan untuk membantu individu memahami peran yang sesuai dengan minat dan keahlian mereka. Dengan informasi ini, para pencari kerja dapat mempersiapkan diri untuk mengambil langkah berharga dalam karir IT yang sukses. </p>

## Tujuan Program
1. Menghasilkan model model machine learning untuk memberikan rekomendasi
2. Rekomendasi pekerjaan IT

## Hasil

<p align="justify"> Pada tugas klasifikasi ini, berhasil melatih model menggunakan data latih dan menguji kinerjanya pada data uji. Model tersebut mencapai <b>akurasi pelatihan</b> sebesar <b>90.14%</b> dan <b>akurasi pengujian</b> sebesar <b>76.16%</b>. </p>

<p align="justify"> Setelah menganalisis performa model menggunakan berbagai metrik evaluasi, termasuk presisi, recall, dan skor F1 untuk setiap kelas. Berikut adalah laporan evaluasi klasifikasi untuk setiap kelas: </p>

1. Kelas 0: Presisi 83%, Recall 83%, F1-Score 83%
2. Kelas 1: Presisi 100%, Recall 100%, F1-Score 100%
3. Kelas 2: Presisi 100%, Recall 50%, F1-Score 67%
4. Kelas 3: Presisi 100%, Recall 100%, F1-Score 100%
5. Kelas 4: Presisi 89%, Recall 80%, F1-Score 84%
6. Kelas 5: Presisi 75%, Recall 90%, F1-Score 82%
7. Kelas 6: Presisi 80%, Recall 86%, F1-Score 83%
8. Kelas 7: Presisi 89%, Recall 80%, F1-Score 84%
9. Kelas 8: Presisi 100%, Recall 17%, F1-Score 29%
10. Kelas 9: Presisi 52%, Recall 65%, F1-Score 58%
11. Kelas 10: Presisi 76%, Recall 57%, F1-Score 65%
12. Kelas 11: Presisi 100%, Recall 100%, F1-Score 100%
13. Kelas 12: Presisi 60%, Recall 79%, F1-Score 68%
14. Kelas 13: Presisi 100%, Recall 75%, F1-Score 86%

<p align="justify"> Selanjutnya, rincian mengenai kinerja secara keseluruhan dengan menggunakan rata-rata presisi, recall, dan F1-score: </p>
1. Rata-rata Presisi: 86%<br>
2. Rata-rata Recall: 76%<br>
3. Rata-rata F1-Score: 78%<br>
<br>
<p align="justify">Setelah menganalisis matriks konfusi untuk mendapatkan wawasan lebih lanjut tentang bagaimana model berkinerja pada setiap kelas. Matriks konfusi menggambarkan seberapa baik model mengklasifikasikan instans ke dalam kelas yang benar atau salah. Dari hasil matriks konfusi, terlihat bahwa ada variasi dalam kemampuan model dalam mengklasifikasikan berbagai kelas. Kelas dengan nilai presisi, recall, dan F1-score yang lebih rendah mungkin memerlukan perhatian lebih lanjut untuk ditingkatkan kinerjanya. Secara keseluruhan, meskipun model ini memiliki akurasi yang baik pada data latih, hasil evaluasi pada data uji menunjukkan adanya potensi untuk meningkatkan kinerja model pada beberapa kelas tertentu. Saya merekomendasikan lebih lanjut untuk melakukan analisis lebih mendalam, seperti tuning parameter model atau mungkin mengumpulkan lebih banyak data, untuk meningkatkan hasil klasifikasi pada kelas yang memiliki kinerja lebih rendah.</p>

