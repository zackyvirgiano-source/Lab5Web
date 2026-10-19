# Praktikum 5 : HTML Lanjutan - Pemrograman Web

Repository ini dibuat untuk menyelesaikan tugas Praktikum 5 Pemrograman Web.  
  
Nama : Muhammad Zacky Virgiano 
NIM : 312510349
Kelas : I251B  
Mata Kuliah : Pemrograman Web

<img width="300" height="200" alt="JS 0" src="https://github.com/user-attachments/assets/21a8567c-cf6b-464b-9ed2-d00b982921a9" />

<img width="572" height="252" alt="js 1" src="https://github.com/user-attachments/assets/520f3d65-681f-43a2-a3b1-a88339702888" />

<img width="570" height="191" alt="js 2" src="https://github.com/user-attachments/assets/6c54dd53-3839-4fcf-aeb3-404f9fe3cccd" />

<img width="501" height="290" alt="js 3" src="https://github.com/user-attachments/assets/8a631081-f6de-42d6-8f92-c76e12d05f4d" />

<img width="561" height="245" alt="js 4" src="https://github.com/user-attachments/assets/67dd0bf4-5200-43d3-91f6-0ae5ce177463" />

<img width="557" height="250" alt="js 5" src="https://github.com/user-attachments/assets/ff556a12-386f-49b1-b12c-c30af7aad2a3" />

<img width="565" height="185" alt="js 6" src="https://github.com/user-attachments/assets/dee9b007-39cf-426a-ac03-03ed47c94cdb" />

<img width="561" height="247" alt="js 7" src="https://github.com/user-attachments/assets/747c8943-1994-4997-acf7-6b7b456c21d2" />

<img width="560" height="248" alt="js 8" src="https://github.com/user-attachments/assets/36cccde6-0170-4893-b119-6abe1ffde98e" />

<img width="565" height="182" alt="js 9" src="https://github.com/user-attachments/assets/58d188a7-b961-4973-b2e4-72ce14222b67" />

<img width="587" height="232" alt="js 10" src="https://github.com/user-attachments/assets/743c3c61-65b0-40e2-a59d-370ff7ce2670" />

<img width="548" height="237" alt="js 11" src="https://github.com/user-attachments/assets/4741ea32-cb7d-431a-8eef-c75930d28362" />

<img width="622" height="276" alt="js 12" src="https://github.com/user-attachments/assets/41bd3e8b-5c0d-4e2b-be36-85a4056604fa" />

<img width="660" height="390" alt="js 13" src="https://github.com/user-attachments/assets/6dd37ed9-771b-493d-b557-82b548ce3744" />

<img width="645" height="552" alt="js 14" src="https://github.com/user-attachments/assets/b80d70cf-6253-4451-8d98-46885f6e4c8a" />

<img width="660" height="496" alt="js 15" src="https://github.com/user-attachments/assets/a4505d13-7997-4d14-8750-31961dcf1220" />

<img width="627" height="355" alt="js16" src="https://github.com/user-attachments/assets/9dec8c9b-9dd0-4f4d-8c1b-aa5aafa4eda5" />


Praktikum 5 : HTML Dasar - Pemrograman Web 

G. JAWABAN

1. Perbedaan console.log(), alert(), prompt(), dan textContent/innerHTML

console.log() digunakan untuk menampilkan informasi di console browser. alert() digunakan untuk 
menampilkan pesan dalam kotak dialog. prompt() digunakan untuk meminta input dari pengguna melalui 
kotak dialog. textContent digunakan untuk menampilkan atau mengubah teks pada elemen HTML, 
sedangkan innerHTML digunakan untuk menampilkan atau mengubah isi HTML di dalam elemen.

2. Perbedaan let dan const

let digunakan untuk membuat variabel yang nilainya dapat diubah, sedangkan const digunakan untuk 
membuat variabel yang tidak dapat diberi nilai ulang.
Contoh:

let nama = "Zacky";
nama = "Virgiano";

const umur = 20;

Pada contoh tersebut, nilai variabel nama dapat diubah, sedangkan nilai variabel umur tidak dapat diberi 
nilai ulang

3. Perbedaan operator == dan ===

Operator == digunakan untuk membandingkan nilai dengan memungkinkan konversi tipe data, sedangkan 
operator === digunakan untuk membandingkan nilai sekaligus tipe datanya.
Contoh:

console.log(5 == "5"); // true
console.log(5 === "5"); // false

4. Fungsi if–else dan switch

if–else digunakan untuk menjalankan kode berdasarkan kondisi tertentu, sedangkan switch digunakan 
untuk memilih tindakan berdasarkan nilai suatu variabel atau ekspresi.

Contoh if–else:

let nilai = 80;
if (nilai >= 75) {
 console.log("Lulus");
} else {
 console.log("Tidak lulus");
}

Contoh switch:

let hari = 1;
switch (hari) {
 case 1:
 console.log("Senin");
 break;
 case 2:
 console.log("Selasa");
 break;
 default:
 console.log("Hari tidak diketahui");
}

if–else cocok digunakan untuk kondisi yang melibatkan perbandingan atau rentang nilai, sedangkan switch 
cocok digunakan untuk beberapa pilihan berdasarkan nilai tertentu.

5. Fungsi parameter dan return dalam function

Parameter digunakan untuk menerima data yang diberikan kepada function, sedangkan return digunakan 
untuk mengembalikan hasil dari function.

Contoh:
function tambah(a, b) {
 return a + b;
}

let hasil = tambah(5, 3);
console.log(hasil);

Hasil yang ditampilkan adalah 8. Parameter pada contoh tersebut adalah a dan b, sedangkan return 
mengembalikan hasil penjumlahan kedua nilai tersebut

6. Cara JavaScript memilih elemen HTML menggunakan document.getElementById()

document.getElementById() digunakan untuk memilih elemen HTML berdasarkan atribut id yang 
dimilikinya.

Contoh:

<p id="pesan">Halo</p>

<script>
 let elemen = document.getElementById("pesan");
 elemen.textContent = "Selamat belajar JavaScript";
</script>

Pada contoh tersebut, JavaScript memilih elemen dengan id "pesan", kemudian mengubah teksnya menjadi 
"Selamat belajar JavaScript".

7. Script untuk memvalidasi form agar nama tidak kosong dan nilai berada pada rentang 0–100

<!DOCTYPE html>
<html lang="id">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Validasi Form</title>
</head>
<body>
 <h2>Form Nilai Mahasiswa</h2>
 <form id="formNilai">
 <label>Nama:</label>
 <input type="text" id="nama">
 <br><br>
 <label>Nilai:</label>
 <input type="number" id="nilai">
 <br><br>
 <button type="submit">Kirim</button>
 </form>
 <p id="pesan"></p>
 <script>
 document.getElementById("formNilai").addEventListener("submit", function(event) {
 event.preventDefault();
 let nama = document.getElementById("nama").value.trim();
 let nilai = document.getElementById("nilai").value;
 let pesan = document.getElementById("pesan");
 if (nama === "") {
 pesan.textContent = "Nama tidak boleh kosong.";
 } else if (nilai === "" || Number(nilai) < 0 || Number(nilai) > 100) {
 pesan.textContent = "Nilai harus berada pada rentang 0–100.";
 } else {
 pesan.textContent = "Data berhasil divalidasi.";
 }
 });
 </script>
</body>
</html>

Penjelasan:
Script tersebut memeriksa apakah nama sudah diisi dan nilai berada pada rentang 0 sampai 100. Jika nama 
kosong atau nilai tidak sesuai rentang, pesan kesalahan akan ditampilkan. Jika semua data valid, pesan 
"Data berhasil divalidasi" akan ditampilkan.








