# WRITING-WEEK-3
## Java Script
### Apa itu Java script array ? 
Struktur data yang digunakan untuk menyimpan sekumpulan data dalam satu tempat
### Contoh codingan array
``` PRODUCT TEAM 
1. product manager
2. front end developer
3. back end developer
let productTeam = ['Product Manager', 'front end developer', 'back end developer'];
console.log[prodctTeam] 
```

### cara mengupdate array
``` let producTeam = ['product manager', 'front end developer', 'back end developer'];

productTeam[0] = 'productDesigner';
console.log(productTeam);
```
Array memiliki 5 properti yang sering digunakan yaitu constructor, length, index, input, dan prototype.

### Apa itu .length
.length adalah mengembalikan nilai darijumlah panjang data suatu array.
### contoh .length
``` let producTeam = ['product manager', 'front end developer', 'back end developer'];

console.log(productTeam.length);
```
### array method 
Array memiliki method atau biasa disebut built-in methods.

Artinya Javascript sudah memudahkan kita dengan menyediakan function/method umum yang bisa kita gunakan.
### method .push()
.push() adalah method untuk menambahkan item array pada urutan paling akhir
### contoh .push
``` let toDolist = [
'belajar javascript'
'mencuci baju'
'latihan membuat aplikasi javascript'
];

toDoList.push('mengikuti kelas online programing');
```

### method .pop()
.pop() adalah method yang menghapus item array index terakhir
### contoh method .pop()
``` let toDoList = [
'belajar javascript'
'mencuci baju'
'latihan membuat aplikasi javascript'
];

toDoList.pop();
console.log(toDoList);
```
### method .forEach()
.forEach() adalah method untuk melakukan looping pada setiap elemen array
### contoh method .forEach()
``` const cars= ['tesla', 'honda', 'toyota'];
cars.forEach(element =>{
  console.log(element);
 });
  ```
### methode .map()
.map() adalah melakukan perulangan/looping dengan membuat array baru.
### contoh method .map()
``` let arr =[1, 2, 3, 4, 5,];

let doubled = arr.map(num => {
  return num * 2;
  });
  
  console.log(doubled);
  ```
  
  ### Java script
 java script adalah bahsa yang single thread (mempunyai 1 jalur), lawan dari single trhread adalah multi thread (mempunyai banyak jalur)
 ### contoh dari single thread 
 1. non blocking
 2. asyncronus
 ### asyncronus 
 asyncronus ialah jikalau si A lama maka membiarkan yang cepat untuk masuk, cara menghindari asyncronus adalah dengan cara callback, promises dan async await
