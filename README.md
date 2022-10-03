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
`First Class Function` adalah salah satu fungsi dalam javascript yang dapat menerapkan fungsi kedalam variabel, objek, ataupun array. Selain itu fungsi ini juga dapat di passing sebagai argument pada fungsi. Berikut adalah contoh penerapan fungsi ke dalam variabel, objek, dan array.

![4](https://user-images.githubusercontent.com/100962621/193523501-cd6fb9eb-835f-40b8-b09f-3b2daa3fb443.PNG)

Kita bisa assign anonymous function ke dalam variabel, objek, dan array dimana isi function tersebut dapat di return apabila ditambahkan tanda kurung dibagian akhir sewaktu proses pemanggilan. Dengan memberi nama pada variabel maka akan membantu proses debug code nya. Berikut adalah contoh passing a function sebagai argumen.


## 4. Higher-order function
## 5. Execution Context
## 6. Execution Stack
## 7. Event Loop
## 8. Callbacks
## 9. Promises dan Async/Await

