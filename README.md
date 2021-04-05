# Praktikum 2
# Pemrograman Web
```
Alfansha Abiftyo Hadyatama
311910321
TI.19.A.2
Universitas Pelita Bangsa
```
## Langkah 1
Membuat dokumen HTML seperti berikut.

<img width="960" alt="1" src="https://user-images.githubusercontent.com/56286071/113553454-02811300-9622-11eb-8ae5-45dc6bcf19ca.png">

# Langkah 2
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian ```head``` dokumen.

<img width="960" alt="2" src="https://user-images.githubusercontent.com/56286071/113553624-4411be00-9622-11eb-96c5-91b2f23b2acd.png">

# Langkah 3
Kemudian tambahkan deklarasi inline CSS pada tag ```<p>``` seperti berikut.

<img width="960" alt="3" src="https://user-images.githubusercontent.com/56286071/113553782-77ece380-9622-11eb-896c-f14fa577eaca.png">

# Langkah 4
Membuat CSS eksternal dan Kemudian tambahkan tag ``` <link> ``` untuk merujuk file css yang sudah dibuat pada bagian ```<head>```.

<img width="960" alt="4(1)" src="https://user-images.githubusercontent.com/56286071/113554219-2ee95f00-9623-11eb-99f9-6999668e6b34.png">

Kemudian refresh browser untuk melihat hasilnya.

<img width="960" alt="4(2)" src="https://user-images.githubusercontent.com/56286071/113554319-56d8c280-9623-11eb-872a-e4523db4897b.png">

# Langkah 5
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector, Pada file style_eksternal.css.

<img width="960" alt="5" src="https://user-images.githubusercontent.com/56286071/113554474-97d0d700-9623-11eb-919e-8cfc3eb02d71.png">



# Pertanyaan dan Tugas
#### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
```
Saya melakukan beberapa eksperimen seperti mengubah nilai yang hasilnya mengubah ukuran ataupun warna dan mengganti background.
```

<img width="960" alt="6  soal1" src="https://user-images.githubusercontent.com/56286071/113554830-1b8ac380-9624-11eb-9d80-6fc42dcb1ee9.png">

#### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
```
Pendeklarasian CSS elemen h1 mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.
```

#### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?Berikan penjelasan dan contohnya!

```
Setelah saya mencoba, jika mendeklarasikan CSS pada elemen yang sama namun dengan isi deklarasi yang berbeda, maka semua deklarasi CSS tersebut akan ditampilkan. Contohnya:
```

<img width="960" alt="7  soal3" src="https://user-images.githubusercontent.com/56286071/113555124-93f18480-9624-11eb-8cd7-e9d26d73e267.png">

<img width="960" alt="8  soal3" src="https://user-images.githubusercontent.com/56286071/113555476-2eea5e80-9625-11eb-9698-da7b6d2d4f30.png">


#### Namun jika isi dari ketiga deklarasi CSSnya sama semua, maka browser hanya akan menampilkan salah satunya, dengan urutan Inline CSS, Eksternal CSS, dan yang terakhir Internal CSS.

<img width="960" alt="9  soal3" src="https://user-images.githubusercontent.com/56286071/113555539-47f30f80-9625-11eb-9f38-6e38b1a37d0f.png">

<img width="960" alt="10  soal3" src="https://user-images.githubusercontent.com/56286071/113555558-504b4a80-9625-11eb-8bb1-66e4198e396f.png">


#### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

```
Kedua deklarasi tersebut akan tampil, namun selector ID yang akan tampil jika deklarasinya ada yang sama antara ID dan Class.
```

<img width="960" alt="11  soal4" src="https://user-images.githubusercontent.com/56286071/113556280-74f3f200-9626-11eb-9687-00550f3208db.png">

<img width="960" alt="12  soal4" src="https://user-images.githubusercontent.com/56286071/113555781-a7e9b600-9625-11eb-994c-9b0a7ed648d0.png">





