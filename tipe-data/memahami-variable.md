# Memahami Variable&#x20;

### Variable

Variabel adalah tempat untuk menyimpan data, variabel digunakan agar kita bisa mengakses data yang sama dimanapun kita mau. Di golang sendiri hanya bisa menyimpan dengan tipe data yang sama, jika kita ingin menyimpan tipe data yang berbeda kita harus membuat variable baru.

Untuk membuat variable cukup mudah, kita bisa menggunakan kata kunci var lalu diikuti nama variable sesuai yang kita inginkan dan tipe data yang digunakan.

Contoh code pembuatan variable:

{% code fullWidth="false" %}
```go
var name string
var age int
```
{% endcode %}

Code di atas akan membuat sebuah variable 'name' yang bertipe data string dan variable 'age' yang bertipe data integer



### Deklarasi Multiple Variable

Di Go-Lang sendiri kita bisa mendeklarasikan variable sekaligus banyak, sehingga code yang dibuat akan rapih dan mudah dibaca

Contoh code multiple variable:

```go
var (
    FirstName = "adli"
    LastName  = "ghozian"
)
```
