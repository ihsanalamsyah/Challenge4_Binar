# Challenge 4 Binar

Dalam Challenge ini lanjutan dari challenge sebelumnya, saya menambahkan sebuah game berupa suit jepang dengan menggunakan bahasa JavaScript

dalam menjalankan suit jepang ini harus memilih antara gunting, kertas, dan batu
computer akan mengeluarkan gunting, kertas, atau batu secara acak menggunakan fungsi 
```
let randomNumber = (Math.floor(Math.random() * 3));
```
Output dari fungsi ini berupa angka acak dari 0 sampai 2 dan fungsi tersebut dimasukkan kedalam variable getComputerChoice dengan query

```
 return choices[randomNumber];
 ```
 
Lalu dibuat fungsi jika menang, kalah, dan seri

Lalu buat fungsi game dimana variable computerChoice berisi getComputerChoice

Selain itu buat fungsi main yang berisi player memilih antara gunting, kertas, dan batu dimana setiap player memilih fungsi game akan berisi gunting, kertas atau batu

Buat fungsi game dengan isi pengkondisian dengan switch, kondisinya jika playerChoice + computerChoice =
```
         case "batugunting":
         case "kertasbatu":
         case "guntingkertas":
```
maka menjalankan fungsi win()
Jika
```
        case "kertasgunting":
        case "guntingbatu":
        case "batukertas":
```
jalankan fungsi lose()
Jika
```
        case "guntinggunting":
        case "kertaskertas":
        case "batubatu":
```
jalankan fungsi draw()
