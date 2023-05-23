# Memahami Tipe Data dan Constant

### Tipe data variable

Saat kita ingin membuat variable maka kita wajib mencantumkan tipe data si variable tersebut, namun jika kita langsung menginisialisasikan data pada variablenya maka kita tidak harus menambahkan tipe datanya, karena tipe data variable tersebut akan mengikuti tipe data valuenya.

Contoh code tanpa tipe data:

```go
var name = "Adli Ghozian"
```

Variable name di atas akan berisikan 'Adli Ghozian' yang bertipe datakan string.



### Kata kunci var

Di golang kata kunci var tidaklah wajib, asalkan saat membuat variable kita langsung menginisialisasikan datanya, agar tidak perlu menggunakan var kita perlu menggunakan kata kunci := saat menginisialisasikan data pada variable tersebut

Contoh code tanpa var:

```go
name := "Adli Ghozian"
```

Code di atas maka kita berhasil membuat variable 'name' dengan value 'Adli Ghozian' yang bertipe data string



### Perbedaan var dan const

Sebenarnya untuk membuat variable kita juga bisa menggunakan const/constant untuk sebagai kata kuncinya, jika kita membuat variable menggunakan var, maka variable tersbut masih bisa akan kita ganti valuenya, tetapi jika kita membuat variable dengan kata kunci const maka value variable tersebut tidak dapat diubah atau static.

Contoh code membuat constant:

```go
const name string
const age = 15
```

Contoh code mengubah value variable:

```go
name := "Bagas"
fmt.Println(name)

name = "Adli Ghozian"
fmt.Println(name)

//output
Bagas         //print ke-1
Adli Ghozian  //print ke-2
```

variable 'name' di atas awalnya diisi dengan 'Bagas' lalu digantik valuenya dengan 'Adli Ghozian'&#x20;



### Declarasi Multiple Constant

```go
const {
    FirstName string = "adli"
    LastName         = "ghozian"
}
```



