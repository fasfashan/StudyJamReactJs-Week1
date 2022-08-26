# StudyJamReactJs-Week1
>Berikut adalah ringkasan di pertemuan pertama StudyJam ReactJS bersama Nest Academy


Pembahasan di pertemuan pertama ini membahas seputar dasar-dasar HTML, CSS dan pengenalan terhadap code editor dan juga browser. Mentor menjelaskan secara singkat apa itu Front-end dev, lalu lanjut ke HTML, dan juga CSS.


## 1️⃣Mengenal Front-end Dev

Seorang Front-End Web Developer adalah Software Developer yang bertanggung jawab untuk merancang dan membangun berbagai aplikasi web secara responsif, interaktif, dan juga *user friendly*. Seorang Front-End Web Developer memiliki peranan besar dalam pengembangan aplikasi web karena bertanggung jawab langsung kepada pengalaman pengguna. —Dicoding

### Tools yang sering digunakan di antaranya:
- Kode editor (VS Code, Sublime Text, etc)
- Browser (Firefox Dev, Chrome, etc)

Ada beberapa istilah di dalam ranah Front-end Dev seperti Front of the Front, dan juga Back of the Front. Tapi istilah ini belum terlalu dikenal di Indonesia.

### Front of the Front
- Handle HTML dan CSS. Javascript sebagai interaksi
- Optimalkan Image, CSS
- Responsive Web
- Mengubah desain ke kode
- Browser compatibility CSS


### Back of the Front
- Handle Data dengan menggunakan Javascript
- Optimalkan Web dengan server
- Optimalkan Web Apps dengan reusable component dan memory
- Browser compatibility javascript

## 2️⃣Pengenalan HTML

Pada pertemuan pertama masih membahas seputar struktur HTML. Sedari awal mentor sudah menekankan untuk menggunakan semantic HTML untuk menghindari penggunaan div secara berlebih. Selain untuk user, semantic HTML juga berguna untuk developer itu sendiri.

>Rekomendasi bacaan semantic HTML: https://www.thoughtco.com/why-use-semantic-html-3468271, https://www.w3schools.com/html/html5_semantic_elements.asp


## 3️⃣Pengenalan CSS

CSS merupakan sekumpulan rule yang kita berikan kepada browser. Layaknya HTML, CSS bukan bahasa pemrograman! CSS sendiri diibaratkan seperti baju yang dikenakan pada manusia, sementara HTML adalah manusia itu sendiri. Jadi, bisa disimpulkan bahwa CSS hadir untuk mempercantik halaman HTML. Layaknya manusia yang menggunakan baju.

### Specificity CSS
> Specificity pada CSS adalah aturan pemberian bobot nilai pada elemen-elemen tertentu di CSS. Semakin tinggi nilainya maka properti-properti CSS pada elemen tersebut yang dimunculkan.

#### Universal Selector 
- Score 0 points

#### Element atau pseudo-element selector
- Score : 1 points

#### Class, pseudo-class, or attribute selector
- Score : 10 points

#### ID Selector
- score 100

#### !Important
- score 10000
>inline style score 1000 dan !important score 10.000 maka harus berhati hati ketika digunakan.

### Box Model
>Di bawah adalah contoh struktur dari box model
![image](https://user-images.githubusercontent.com/69034771/186846395-5437201b-f25f-4a65-a36a-3c3ca5782947.png)

## 4️⃣Struktur Folder

### Mengapa penting?
>Struktur sebuah Website sangat penting mengingat semakin berkembangnya project kita, maka semakin banyaknya file yang kita miliki maka kebutuhan untuk struktur file HTML dan CSS menjadi cukup penting.

Meskipun bukan aturan yang saklek, tapi berikut adalah contoh penggunaan struktur folder yang benar<br>
![image](https://user-images.githubusercontent.com/69034771/186847080-ea64422c-ca65-426b-8ab6-e6481b97ab1f.png)

## 🥇Task Frontend Weeks 1
1. Membuat project di vscode, lalu didalam body terdapat tag HTML sehingga menghasilkan  kurang lebih seperti ini : 
    - Menu navigasi
    - Header
    - Main
    - footer 
    - jenis input 
    - terdapat gambar
    - terdapat button
        - Menggunakan VSCode
        - Menggunakan Live Server
        
2. Buat seperti ini : 
    - Tampilan
    - Element-element<br>
    https://survey-form.freecodecamp.rocks/
