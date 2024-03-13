# REFLECTION 
Nama    : Clara Sista Widhiastuti <br>
NPM     : 2206825782 <br>
Kelas   : Adpro-A <br>

### Before optimization JMeter
#### all-student
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217455493207949322/Screenshot_2024-03-13_155332.png?ex=660416c8&is=65f1a1c8&hm=e33488518ef50c8019f04794e0bd2381d68ffef529087d6341ea86446abf99e5&)
#### higest-gpa
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217455494227038208/Screenshot_2024-03-13_162507.png?ex=660416c9&is=65f1a1c9&hm=62a3f75a7589eabc9e8456f8559aa98379e62723baa62b5b7bf71031b41c0adf&)
#### all-student-name
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217455493853876234/Screenshot_2024-03-13_162003.png?ex=660416c8&is=65f1a1c8&hm=1c1f392d17deea10da357e7c3aaabe6d5ab7cc9a698d97131ceb0cf412f87913&)

### Before optimization CLI
#### all-student
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217457221735288932/image.png?ex=66041864&is=65f1a364&hm=a4e5f14caa097b0887c432e39d03f8e364a1d554d229b3978ac47e4a01296fe2&)
#### higest-gpa
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217457725080862730/image.png?ex=660418dc&is=65f1a3dc&hm=ba7c3d627462a2bb834cc35abdc43f5e39409aec01bcf2bd3bb207e1bd9d8bb4&)
#### all-student-name
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217457445513859102/image.png?ex=6604189a&is=65f1a39a&hm=bd39c4d7e5251ab55effbc0daef7fe7baa1fa1aa0c3a70b8605ed78a86372952&)

### After optimization JMeter
#### all-student
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217455580223111229/Screenshot_2024-03-13_183305.png?ex=660416dd&is=65f1a1dd&hm=5171de58a22741a55dd8fd88631237497bf3c6e9db66e8a0fa1f270867ad1850&)
#### higest-gpa
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217455580860518491/Screenshot_2024-03-13_183502.png?ex=660416dd&is=65f1a1dd&hm=b96eb61530d7b615b4c390ed8c442b50e44b79b544716960438e792e3f11012b&)
#### all-student-name
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217455580550008842/Screenshot_2024-03-13_183418.png?ex=660416dd&is=65f1a1dd&hm=e7445abc40a28a0a9f5feb226ba1fa3e53484ec98a53aa06bf1187e013b34ddb&)

### After optimization CLI
#### all-student
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217459070601003108/image.png?ex=66041a1d&is=65f1a51d&hm=fd96823d342624bbe261083c9b510056675be235471e4132e9a837705c9646a1&)
#### higest-gpa
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217459562718957649/image.png?ex=66041a93&is=65f1a593&hm=00c1ef3c5891034b4005c62d123fffb951784522db80087180fa9231a0b29302&)
#### all-student-name
![](https://cdn.discordapp.com/attachments/1174990449421860874/1217459753140092950/image.png?ex=66041ac0&is=65f1a5c0&hm=59c59ac945f3b98b41df3749271a453132d0cbd8b4126d79f84c633c0e0ede1d&)

1. **What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler 
in the context of optimizing application performance?**<br>
Melalui jmeter kita dapat mengetahui dan mengukur waktu dari respons keseluruhan. Hasil dari pengujian JMeter memberikan
gambaran tentang kinerja dari suatu aplikasi sehingga dapat membantu mengidetifikasi kemampuan bagian tertentu dalam 
menangani suatu beban. Sedangkan, Intellij Profiler dapat digunakan untuk menganalisa secara mendalam terkait kinerja 
suatu aplikasi. Hasil dari profilling kita dapat mengukur waktu yang dihabiskan untuk menjalanlkan suatu method dalam 
beban tertentu. 

2. **How does the profiling process help you in identifying and understanding the weak points in your application?**<br>
a. Profilling dapat membantu saya dalam mengukur waktu yang dihabiskan ketika sedang mengeksekusi kode. Dari situ saya 
dapat mengetahui weak-point dari suatu method.<br> 
b. Profilling dapat membantu mencatat penggunaan memori oleh aplikasi<br>
c. Membantu menemukan bagian mana yang sering dieksekusi, sehinggga mempermudah optimizing. 

3. **Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your 
application code?**<br>
Ya, menurut saya Intellij Profiler sangat membantu dalam menganalisa dan mengidentifikasi bottlenecks dalam kode 
aplikasi saya. Karena Intellij Profiler dapat membantu mengidentifikasi bug, membantu optimasi kode, dapat membantu 
dalam membandingkan sebuah solusi mana yang lebih optimize.  

4. **What are the main challenges you face when conducting performance testing and profiling, and how do you overcome 
these challenges?** <br>
Pada awalnya saya bingung harus mengoptimize seperti apa, namun setelah mencoba-coba dan membaca kembali code, ternyata
kode yang saya buat dapat teroptimize sedikit demi sedikit. 

5. **What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?**<br>
Membantu saya dalam melakukan optimisasi kode. Sehingga awalnya kode saya yang menghabiskan banyak waktu untuk 
mengeksekusi, menjadi lebih singkat waktu yang dibutuhkan saat mengeksekusi.

6. **How do you handle situations where the results from profiling with Inte	lliJ Profiler are not entirely consistent 
with findings from performance testing using JMeter?**<br>
Ketika hasil dari pemetaan profil menggunakan IntelliJ Profiler tidak sepenuhnya konsisten kita dapat menggunakan JMeter.
Bandingkan hasil analisis kinerja dari keduanya. Kemudian, kombinasikan kedua hasil agar bisa mendapatkan hasil 
optimisasi yang maksimal.

7. What strategies do you implement in optimizing application code after analyzing results from performance testing 
and profiling? How do you ensure the changes you make do not affect the application's functionality?<br>
Ada beberapa langkah-langkah yang saya lakukan untuk menganalisa dan melakukan optimisasi. Pertama, melakukan 
identifikasi method mana yang perlu di optimisasi. Perbaiki weak-point yang sudah terdeteksi. Kemudian, lakukan uji coba 
pada perubahan yang telah dilakukan. Kemudian uji kinerja dari hasil optimisasi. 
