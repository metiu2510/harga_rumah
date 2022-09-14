Tugas 1
Aku pun melanjutkan prosesnya dengan membaca file harga_rumah.txt dan merepresentasikan setiap data ke dalam tipe data dictionary dan menampung keseluruhan data dalam sebuah list bernama harga_rumah:



Setelah selesai memasukkan data dan menemukan jika nilai dari setiap atribut (tanah, bangunan, jarak_ke_pusat) tidak setara, aku mulai agak bingung. Tapi, harus tenang dan jangan panik!

Aku kembali mengecekanya dan memutuskan utnuk melakukan proses transformasi data. Transformasi data dilakukan dengan mengurangi setiap nilai atribut dalam data dengan nilai atribut minimum dan membaginya dengan nilai atribut maksimum yang dikurangi dengan nilai atribut minimum, seperti ini:

Untuk atribut tanah, nilai maksimum adalah 150 dan nilai minimum adalah 70.
Saat nilai atribut tanah 100, proses transformasi akan mengubah nilai atribut ini menjadi 0,375
nilai_transformasi = 100 - 70 / (150 - 70)
Aku mulai mendapat solusi untuk mempermudah proses transformasi data.

Tugas 2
Mula-mula,  aku akan membuat sebuah fungsi bernama get_all_specified_attribute yang menerima parameter list_of_dictionary (tipe data list yang berisikan sekumpulan tipe data dictionary) dan specified_key (tipe data string). Fungsi akan mengembalikan sebuah list yang berisikan seluruh atribut dengan kunci (key) specified_key.

Tugas 3

Kemudian, setelah berhasil membuat fungsi  tersebut, aku juga membuat fungsi min_value yang menerima parameter list_attributes (berupa tipe data list) dan mengembalikan nilai terkecil dalam list_attributes dan max_value yang menerima parameter list_attributes dan mengembalikan nilai terbesar dalam list_attributes.

Tugas 4
Selanjutnya aku membuat fungsi transform_attribute yang menerima parameter attr (sebuah bilangan), max_attr (sebuah bilangan) dan min_attr (sebuah bilangan) yang mengembalikan nilai transformasi dari sebuah attribute.

Tugas 5
“Sudah cukup, Nja?” tanyaku saat Senja terdiam lama menelusuri hasil kerjaku.

“Menurutku kita masih butuh fungsi baru yaitu fungsi data_transformation yang menerima parameter list_of_dictionary (sebuah list yang berisikan tipe data dictionary) dan list_attribute_names (sebuah list yang berisikan tipe data string) mengembalikan hasil transformasi data dari list_of_dictionary berdasarkan list_attribute_names telah dispesifikasikan.

Tugas 6
Dari data baru dan attr_info ini, Senja menyuruhku membuat fungsi transform_data yang menerima parameter data dan attr_info dan mengembalikan nilai atribut dari data baru yang telah ditransformasikan.

Tugas 7
Setelah itu, Senja memintaku untuk membuat sistem prediksi harga berdasarkan nilai kemiripan atribut.

Tugas 8
Dan aku menggunakan semua fungsi yang telah aku definisikan dari Step 1 s/d Step 7.

Hitung harga rumah yang telah ditransformasikan ke dalam variabel harga_rumah berikut dengan atributnya attr_info
Gunakan variabel data untuk memprediksi harga rumah
data = {'tanah': 110, 'bangunan': 80, 'jarak_ke_pusat': 35}
transformasikan data tersebut dengan dengan menggunakan attr_info yang telah diperoleh yang kembali disimpan ke variabel data.
Hitunglah prediksi harga dari variabel data tersebut. 
