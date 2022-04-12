# Lab5Web
| Nama      | Lydia Diffani Siregar |
| ----------- | ----------- |
| NIM     | 312010498       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 5

1. Pertama - tama membuka VSC

![foto](foto/awalan.PNG)

2. Kemudian membuat dokumen HTML dengan nama file <strong> lab4_box.html </strong>
![foto](foto/1.PNG)
Ini hasil di Microsoft Edge nya
![foto](foto/hasil1.PNG)

3. <strong> Javascrip Dasar </strong>

<p> Pemakaian Alert sebagai property window. </p>

![foto](foto/2.PNG)

Ini hasil di Microsoft Edge nya
![foto](foto/hasil2.PNG)

4. Pemakaian method dalam objek

![foto](foto/3.PNG)
<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil3.PNG)

5. <p> Pemakaian Prompt </p>

![foto](foto/4.PNG)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil4.1.PNG)
![foto](foto/hasil4.2.PNG)

6. <p> Pembuatan fungsi dan cara pemanggilannya </p>

![foto](foto/5.PNG)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil5.PNG)

7. <strong> Dasar Pemrograman Di Javascript </strong>
<p> Operasi dasar aritmatika </p>

![foto](foto/6.PNG)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil6.PNG)

Seleksi kondisi (if..else)
<p> disini saya akan memasukkan data 95 </p>

![foto](foto/7.PNG)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil7.PNG)

<p> Penggunaan operator switch untuk seleksi kondisi </p>

![foto](foto/8.png)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil8.1.PNG)
![foto](foto/hasil8.2.PNG)

8. <strong> Pembuatan Form </strong>
<p> Form Input </p>

![foto](foto/9.PNG)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil9.PNG)

9. <p> Form Button. </p>

![foto](foto/10.png)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil10.1.PNG)
![foto](foto/hasil10.2.PNG)

10. <strong> HTML DOM </strong>
<strong><p> Pilihan menggunakan checkBox dengan perhitungan otomatis </p></strong>

![foto](foto/11.PNG)

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil11.PNG)

## Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form.

## JAWAB
Membuat validasi NAMA, NO.TELP,EMAIL
1. <strong>Nama</strong>
<p>Saya akan memberikan Validasi berupa inputan hanya boleh menggunakan Huruf/Alphabet saja. Contoh: Lydia (benar), Lydia01 (salah).

![foto](foto/12.PNG)

Penjelasan :

<p>Pertama membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai, pesan).</p>
<p>Data yang boleh dimasukkan adalah berupa "a-zA-Z".</p>
<p>Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan).</p>

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil12.PNG)

2. <strong>No.Telp</strong>
<p>Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: 54321 (benar), BA321 (salah).</p>

![foto](foto/13.PNG)

Penjelasan :

<p>var numberExp = /^[0-9]+$/; merupakan variabel numberExp yang diberi batasan validasi angka 0-9</p>
<p>Arti Match pada "if(nilai.value.match(numberExp))" adalah string.match(), mencari string menggunakan Regular Expression (Regex)</p>
<p>Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan)</p>

<p> Ini hasil di Microsoft Edge nya </p>

![foto](foto/hasil13.PNG)