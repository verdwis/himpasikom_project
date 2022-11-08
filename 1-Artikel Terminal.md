 # Basic Command Prompt Yang Wajib Anda Kuasai di Google Collab
 
 
<p align="justify">Bekerja dengan baris perintah bukanlah tugas yang menakutkan seperti yang anda bayangkan. Tidak diperlukan pengetahuan khusus untuk mengetahui bagaimana menggunakan baris perintah, ini program biasa seperti program-program yang lainnya. Semua tugas di Linux dapat diselesaikan menggunakan baris perintah, meskipun sudah ada tool-tool berbasis grafik untuk kebanyakn program, tetapi kadangkala itu semua belumlah mencukupi. Disinilah baris perintah akan menolong anda.</p>

<p align="justify">Terminal sering disebut <em>command prompt</em> atau shell. Di masa lalu, ini adalah cara pengguna untuk berinteraksi dengan komputer, namun pengguna Linux merasakan dengan menggunakan shell ia dapat mengeksekusi perintah dengan lebih cepat dibandingkan dengan cara grafis dan masih sangat berguna hingga saat. Kali ini anda akan mempelajari bagaimana menggunakan terminal.</p>

<p align="justify"><em>Command prompt</em> bisa anda gunakan untuk melihat dan menampilkan isi folder, mencari file, membuat file, hapus file, memindah, copy, pasti hingga anda bisa install, hapus, update dan upgrade apllikasi dengan mengetikan perintah di terminal. Tidak hanya itu, anda juga bisa melihat spek kompute menggunakan perintah <em>command prompt</em> dan lebih kerennya anda bisa membuat script sendiri untuk membuat perintah yang berjalan otomatis.</p>

<p align="justify">Perintah <em>command prompt</em> bisa juga gunakan pada <em>notebook</em> <strong>Google Colab</strong>. Fungsi <em>command prompt</em> pada <em>notebook</em> <strong>Google Colab</strong> mempermudah programmer dalam menjalan perintah yang ada pada komputer mennggunakn keyboard. berikut adalah perintah <em>basic command promt</em> yang bisa di implementasikan pada <em>notebook</em> <strong>Google Colab</strong>. Berikut adalah printah command promd di notebook Google Colab: </p>


## 1. Buka Google Colab Notebook

<img src="https://user-images.githubusercontent.com/101826376/200305898-cc3e9a70-b97c-46d8-8f25-26c937c31480.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; witdth: 50px " />
     
     
## 2. ls Command

<p align="justify"> Is merupakan perintah dasar pada Linux yang digunakan untuk melihat konten atau isi direktori. Secara default, command ini akan menampilkan isi dari direktori yang Anda gunakan saat ini. Jika ingin melihat isi direktori lain, ketik Is, disusul dengan path direktori. Contoh, ketik Is /content untuk melihat isi Documents.</p>

```
!ls
```
***Output :***

<img width="235" alt="image" src="https://user-images.githubusercontent.com/101826376/200484300-259d0237-ddad-49ce-9aa6-743f810da261.png">

## 3. mkdir Command

<p align="justify">Untuk membuat direktori baru, Anda bisa menggunakan perintah dasar Linux mkdir. Sebagai contoh, jika Anda mengetik mkdir <strong>test</strong>, direktori baru yang muncul disebut <strong>test</strong>.</p>

```
!mkdir test
```

***Output :***

<img width="265" alt="image" src="https://user-images.githubusercontent.com/101826376/200484745-87236224-9ef7-49ed-a117-1a4736a51911.png">

## 4. cd Command

<p align="justify">Untuk menjelajahi file dan direktori notebook colab, gunakan perintah cd. Perintah  ini memerlukan path penuh atau nama direktori, tergantung pada direktori yang Anda gunakan saat ini.</p>
<p align="justify">Misalkan saat ini Anda sedang berada di /content/sample_data dan ingin membuka sample_data, subdirektori dari content. Untuk melakukannya, Anda hanya perlu mengetikkan command ini: cd Photos.</p>

```
cd sample_data
```
***Output :***

<img width="506" alt="image" src="https://user-images.githubusercontent.com/101826376/200485438-6c54374f-a4b2-4b2b-b3df-483da1606790.png">

## 5. mv command

<p align="justify">Fungsi utama command mv adalah untuk memindahkan file meskipun sebenarnya bisa digunakan untuk mengganti atau mengubah nama file.
Argumen yang ada di mv serupa dengan argumen yang ada di perintah cp. Ketik mv, nama file, dan direktori tujuan. Contoh: <strong>mv /content/sample_data/mnist_test.csv /content/test</strong>.</p>

```
mv /content/sample_data/mnist_test.csv /content/test
```

```
cd ../test
```
```
ls
```

***Output :***

<img width="501" alt="image" src="https://user-images.githubusercontent.com/101826376/200486695-89c49eeb-c9ef-4014-a391-95c58b3c0bf6.png">

## 6. rm command

<p align="justify">rm adalah perintah dasar pada notebook colab yang berfungsi untuk menghapus direktori beserta isinya. Jika hanya ingin menghapus direktorinya saja – alternatif command selain rmdir – gunakan rm -r.</p>

```
rm -r mnist_test.csv
```
***Output :***

<img width="250" alt="image" src="https://user-images.githubusercontent.com/101826376/200487460-24fba04f-26b5-4636-b6ba-27a9c284c6f0.png">

## 7. cp command

<p align="justify">Gunakan perintah dasar notebook colab cp untuk menyalin file dari direktori saat ini ke direktori yang berbeda. Misalnya, command <strong>!cp -r /content/sample_data/california_housing_test.csv /content/drive/MyDrive/HIMPASIKOM/EngineeringForResearcher</strong> untuk membuat salinan california_housing_test.csv  (dari direktori saat ini) ke direktori EngineeringForResearcher.</[>

```
!cp -r /content/sample_data/california_housing_test.csv /content/drive/MyDrive/HIMPASIKOM/EngineeringForResearcher
```

***Output :***

<img width="579" alt="image" src="https://user-images.githubusercontent.com/101826376/200488163-7031a5cf-71db-4fcd-bc6e-14d69697f2c7.png">
















     


     
  






