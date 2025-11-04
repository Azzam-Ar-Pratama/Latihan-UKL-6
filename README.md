# Latihan-UKL-6
Tujuan:
Program ini menjumlahkan dua matriks yang ukurannya sama. Kamu masukkan ukuran matriks, isi elemen A dan B, lalu program menampilkan hasil (A + B).

Inputan:
Jumlah baris (misal 2)
Jumlah kolom (misal 3)
Semua angka untuk matriks A, satu per satu sesuai urutan baris-kolom
Semua angka untuk matriks B, sama caranya

Cara kerja program:
1. Program minta ukuran matriks. Kalau ukuran <= 0 program berhenti.
2. Program buat 3 “tabel” kosong (A, B, C) dengan ukuran yang dimasukkan.
Bayangkan tabel: baris × kolom.
3. Program minta kamu memasukkan angka untuk tabel A baris demi baris.
Contoh: untuk baris 1 kolom 1 kamu isi_ A[1][1], lalu A[1][2], dst.
Di kode, penyimpanan pakai indeks mulai dari 0 (A[0][0] adalah baris 1 kolom 1), tapi kamu diminta dengan angka yang mudah dibaca (1-based).
4. Lalu minta memasukkan angka untuk tabel B dengan urutan yang sama.
5. Program menambahkan setiap pasangan elemen A dan B: C[i][j] = A[i][j] + B[i][j].
6. Terakhir program cetak tabel C (hasil) baris per baris.

Contoh singkat:
Jika A = [[1,2],[3,4]] dan B = [[5,6],[7,8]] maka C akan jadi [[6,8],[10,12]] dan program akan menampilkannya.
