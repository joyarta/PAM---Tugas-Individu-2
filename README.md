# Rangkuman Materi Javascript Lanjutan
## 1.Closure
Closure dibuat setiap kali kita membuat fungsi dalam javascript. Closure adalah fungsi dalam yang memiliki akses ke ruang lingkup fungsi luar.
Atau bisa disebut juga sebagai kombinasi antara fungsi dan lingkungan leksikal (Lexical scope) di dalam fungsi tersebut.

Contoh : 

![1](https://user-images.githubusercontent.com/100962621/193505774-7337d6b8-02c3-45cd-88e8-b176501bd1eb.PNG)

Dalam contoh diatas, mendeklarasikan variabel lokal yang disebut `universitas` dan membuat fungsi `tampilUniv` sebagai fungsi dalamnya. Selain itu, terdapat pula
fungsi `panggilUniv` sebagai fungsi pemanggilan.

## 2. Immediately Invoked Function Expression (IIFE)
`Immediately Invoked Function Expression (IIFE)` merupakan cara pemanggilan fungsi di javascript tanpa mendefinisikan fungsi itu sebelumnya. Atau dapat juga diartikan
fungsi yang memanggil dirinya sendiri. Untuk membuat IIFE kita bisa menggunakan dua pasang kurung buka dan tutup berdampingan `(function) (parameter)`.
Kurung pertama adalah tempat untuk mendeklarasikan Anonymous Function Expression dan kurung kedua digunakan untuk memanggil fungsi tersebut. Jika fungsi memiliki
parameter maka kita bisa meneruskan nilai atau argumen ke dalam kurung kedua.

Berikut adalah contoh IIFE tanpa parameter.

![2](https://user-images.githubusercontent.com/100962621/193516890-1a662314-75f8-479f-81c6-a5596c17f018.PNG)

Berikut adalah contoh IIFE dengan parameter.

![3](https://user-images.githubusercontent.com/100962621/193518080-62e008cf-8dc8-4a58-b73e-8c2c44eb1e10.PNG)

## 3. First-class function
`First Class Function` adalah salah satu fungsi dalam javascript yang dapat menerapkan fungsi kedalam variabel, objek, ataupun array. Berikut adalah contoh penerapannya.

![4](https://user-images.githubusercontent.com/100962621/193523501-cd6fb9eb-835f-40b8-b09f-3b2daa3fb443.PNG)

Kita bisa assign anonymous function ke dalam variabel, objek, dan array dimana isi function tersebut dapat di return apabila ditambahkan tanda kurung dibagian akhir sewaktu proses pemanggilan. Dengan memberi nama pada variabel maka akan membantu proses debug code nya. Berikut adalah contoh passing a function sebagai argumen.

## 4. Higher-order function
`Higher Order Function` adalah sebuah fungsi yang didalamnya memiliki fungsi lain sebagai argument ataupun function yang nilainya dikembalikan sebagai hasil atau output. Fungsi yang terlibah sebagai argument atau nilai pada higher order function ini disebut juga sebagai callback function. Beberapa higher order function yang sering digunakan seperti find(), filter(), sort(), dan lainnya. Berikut ini adalah contoh dari higher order function.

![6](https://user-images.githubusercontent.com/100962621/193540547-32c7d76d-fb0f-4404-b02b-d903eeacfa8b.PNG)

Array.filter() adalah salah satu metode dari higher-order function bawaan yang berfungsi untuk membuat array baru dengan mengoperasikan fungsi callback pada setiap anggota dengan mem-filter nilai-nilai didalam array yang sudah ada. Adapun argumen yang ada pada callback filter() adalah: value, index.
Berikut ini adalah contoh dari higher order function.



## 5. Execution Context
`Execution Context` didefinsikan sebagai konteks atau lingkungan dimana javascript di eksekusi. Execution Context merupakan pembungkus yang mengelola code yang sedang di jalankan. Execution Context terbagi menjadi 2 yaitu Global Execution Context dan Local Execution Context. Dan dalam javascript terdapat 2 fase (2 Phase) pada saat Execution Context yaitu creation phase dan execution phase. Ketika javascript pertama kali di eksekusi, ia akan menjalankan Creation Phase yaitu javascript mengangkat(menghoisting) seluruh variabel dan function ke atas atau dalam visualisasi ke dalam global frame, kemudian menginisiasi variabelnya dengan undefined dan menginisiasi function dengan function itu sendiri. Setelah Creation Phase dijalankan javascript akan menjalankan code secara synchron(Sinkronis) dari atas kebawah dan disinilah Execution Phase terjadi. Lebih jelasnya berikut adalah contoh kasusnya :

![7](https://user-images.githubusercontent.com/100962621/193550086-38e78e7e-be05-45c5-aa77-2182e89da140.PNG)

## 6. Execution Stack
## 7. Event Loop
## 8. Callbacks
Dalam Javascript, fungsi `Callback` adalah fungsi yang diteruskan ke fungsi lain sebagai argumen. (Lihat poin 3). Fungsi ini kemudian dapat dipanggil selama eksekusi fungsi urutan yang lebih tinggi karena dalam javascript, fungsi adalah objek yang dapat diteruskan sebagai argumen.

![5](https://user-images.githubusercontent.com/100962621/193526748-7fc553c7-d047-4ed4-94f7-5dedaeed71df.PNG)

Dari contoh diatas dapat dilihat bahwa kita mempassing fungsi katakanHai() kedalam fungsi salam() sebagai argumen. Fungsi yang dipassing sebagai argumen pada fungsi lain dinamakan `Callback Function`. Sehingga dengan kata lain fungsi katakanHai() adalah yang dinamakan Callback Function.
## 9. Promises dan Async/Await

