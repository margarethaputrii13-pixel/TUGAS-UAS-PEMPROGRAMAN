# TUGAS-UAS-PEMPROGRAMAN

nama =margaretha futri irwan       
Nim =312510337          
Kelas =TI25.c5

🔹 1. Tujuan Program

Program ini bertujuan untuk:
	•	Menerima data mahasiswa
	•	Memvalidasi nilai
	•	Menghitung nilai akhir berdasarkan bobot
	•	Menampilkan hasil nilai mahasiswa secara terstruktur

Bobot penilaian yang digunakan adalah:
	•	Nilai Tugas: 30%
	•	Nilai UTS: 30%
	•	Nilai UAS: 40%

⸻

🔹 2. Struktur Program

Program ini terdiri dari tiga class utama:

a. Class Student (Model)
Class ini berfungsi untuk menyimpan data mahasiswa, seperti:
	•	NIM
	•	Nama
	•	Kelas
	•	Nilai tugas, UTS, dan UAS

Class ini tidak melakukan proses apa pun, hanya sebagai wadah data.

⸻

b. Class StudentProcess (Controller / Process)
Class ini berisi logika program, yaitu:
	•	Validasi nilai, untuk memastikan nilai berada di rentang 0 sampai 100
	•	Perhitungan nilai akhir, menggunakan rumus pembobotan

Dengan pemisahan ini, logika program menjadi lebih rapi dan mudah dikembangkan.

⸻

c. Class StudentView (View)
Class ini bertugas menangani:
	•	Input data dari pengguna
	•	Output atau tampilan hasil nilai mahasiswa

Dengan konsep ini, tampilan dan logika program tidak saling bercampur.

⸻

🔹 3. Alur Jalannya Program

Alur program berjalan sebagai berikut:
	1.	Program meminta pengguna memasukkan data mahasiswa
	2.	Sistem memvalidasi setiap nilai
	3.	Data mahasiswa disimpan ke dalam objek Student
	4.	Nilai akhir dihitung oleh StudentProcess
	5.	Hasil ditampilkan oleh StudentView
	6.	Jika terjadi kesalahan input, program akan menampilkan pesan error

⸻

🔹 4. Demo Program

Saat program dijalankan:
	•	Pengguna diminta memasukkan NIM, nama, kelas, dan nilai
	•	Program otomatis menghitung nilai akhir
	•	Hasil ditampilkan dengan format rapi dan jelas

Jika nilai yang dimasukkan tidak valid, program akan menolak dan menampilkan pesan kesalahan.

⸻

🔹 5. Kesimpulan

Dengan menerapkan konsep OOP dan MVC, program ini memiliki kelebihan:
	•	Struktur kode lebih rapi
	•	Mudah dipahami
	•	Mudah dikembangkan di masa depan
	•	Memisahkan data, proses, dan tampilan
