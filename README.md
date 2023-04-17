# Praktikum 1

Data Model Mapping
1. Mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, jalan, kota, kodepos, no_hp, kd_ds)
2. Dosen (kd_ds, nama)
3. Matakuliah (kd_mk, nama, sks)
4. JadwalMengajar (kd_ds, kd_mk, hari, jam, ruang)
5. KRSMahasiswa (nim, kd_mk, kd_ds, semester, nilai)

Buat DDL Script berdasarkan skema ERD tersebut diatas.
Jalankan script DDL tersebut pada DBMS MySQL

1. Script Tabel mahasiswa

![sc mahasiswa](https://user-images.githubusercontent.com/115356128/232085147-2b7e6877-9024-4308-8196-b3800313de5c.png)

OUTPUT

![hasil mahasiswa](https://user-images.githubusercontent.com/115356128/232085224-2b7973e2-ecfc-46cb-82a5-089ef539cc76.png)

2. Script Tabel dosen

![sc dosen](https://user-images.githubusercontent.com/115356128/232085466-095dbd3b-778c-457e-ba3f-504a25707fdc.png)

OUTPUT

![hasil dosen](https://user-images.githubusercontent.com/115356128/232085557-f2eb9437-a280-4701-93ea-7883e837d3b4.png)

3. Script Tabel matakuliah

![sc matkul](https://user-images.githubusercontent.com/115356128/232085698-b110b12d-9270-4460-9d88-ee7eac8fd7ae.png)

OUTPUT

![hasil matkul](https://user-images.githubusercontent.com/115356128/232085747-37cbf8ef-dcf4-49a0-bdd4-4b5f4ee37b7d.png)

4. Script Tabel JadwalMengajar

![sc jadwal](https://user-images.githubusercontent.com/115356128/232086158-04c181f0-484e-44c2-8b5c-0dfabc75ecb4.png)

OUTPUT

![hasil jadwal](https://user-images.githubusercontent.com/115356128/232086204-ea35bdef-f3cd-4dba-8101-7e6a995a4d06.png)

6. Script Tabel KRSmahasiswa

![sc krs](https://user-images.githubusercontent.com/115356128/232086272-44e9ccad-dcc7-492e-83e3-ca874de3a03e.png)

OUTPUT

![hasil krs](https://user-images.githubusercontent.com/115356128/232086314-d76a19a8-6be6-494b-a807-0ece1cd9f890.png)

DDL Script
![ddl script](https://user-images.githubusercontent.com/115356128/232086628-22b70bc8-a630-4288-ac6a-8436230baffc.png)



# Tugas Praktikum 2
```
1. Isi data pada table tersebut sebanyak minimal 5 record data.
2. Tampilkan semua isi/record tabel! 
3. Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 1979-08-31! 
4. Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan nama Ari saja! 
5. Hapus Mahasiswa yang bernama Dina! 
6. Tampilkan record atau data yang tanggal kelahirannya lebih dari atau sama dengan 1996-1-2! 
7. Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin perempuan! 
8. Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita!
9. Tampilkan data nama dan alamat mahasiswa saja dari tabel tersebut
10. Tampilkan data mahasiswa terurut berdasarkan nama
```

1. Isi data pada table tersebut sebanyak minimal 5 record data.
![ddl 1](https://user-images.githubusercontent.com/115356128/232091268-12c09b73-7b86-4c31-9cbb-d013455c50d1.png)

2. Tampilkan semua isi/record tabel!
![ddl 2](https://user-images.githubusercontent.com/115356128/232091567-89a38d10-be90-4e24-9a90-2cc47c06d7e9.png)

3. Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 1979-08-31!
![ddl 3](https://user-images.githubusercontent.com/115356128/232096964-ded9b7be-6c7f-432f-ae33-c273c7edb9bf.png)

4. Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan nama Ari saja!
![ddl 4](https://user-images.githubusercontent.com/115356128/232098808-5d9f9d82-4cf4-48e7-a1fd-ad6cf411293d.png)

5. Hapus Mahasiswa yang bernama Dina!
![ddl 5](https://user-images.githubusercontent.com/115356128/232099151-b2da6eaa-2978-46b1-b90b-796f83fea363.png)

6. Tampilkan record atau data yang tanggal kelahirannya lebih dari atau sama dengan 1996-1-2!
![ddl 6](https://user-images.githubusercontent.com/115356128/232101668-c4669eb9-2cba-4b02-a92e-f5ca05161357.png)

7. Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin perempuan!
![ddl 7](https://user-images.githubusercontent.com/115356128/232102325-75a4073b-40b2-48ad-9fac-28ea7c75b7e9.png)

8. Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita!
![ddl 8](https://user-images.githubusercontent.com/115356128/232105569-3aed12de-0123-4303-87c9-257a1dae6b1c.png)

9. Tampilkan data nama dan alamat mahasiswa saja dari tabel tersebut
![ddl 9](https://user-images.githubusercontent.com/115356128/232107282-f0ade418-ea82-4b09-b694-ddb72e3be43d.png)

10. Tampilkan data mahasiswa terurut berdasarkan nama
![ddl 10](https://user-images.githubusercontent.com/115356128/232107576-8a765cb8-c53d-4759-925f-65adc1880bc4.png)


Evaluasi dan Pertanyaan
1. Apa bedanya penggunaan BETWEEN dan penggunaan operator >= dan <= ?
(misal: tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11')
(misal: tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11')
```
Operator BETWEEN digunakan untuk memeriksa apakah sebuah nilai berada di antara dua nilai yang diberikan, termasuk kedua nilai tersebut. Contoh penggunaannya adalah tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11', yang artinya mengambil data dengan tanggal lahir di antara 10 Oktober 1990 dan 11 Oktober 1992, termasuk kedua tanggal tersebut.
Sedangkan operator >= dan <= digunakan untuk membandingkan nilai dan mengambil data dengan nilai yang lebih besar atau lebih kecil dari suatu nilai tertentu. Contoh penggunaannya adalah tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11', yang artinya mengambil data dengan tanggal lahir yang lebih besar atau sama dengan 10 Oktober 1990 dan lebih kecil atau sama dengan 11 Oktober 1992.
```
2. Berikan kesimpulan anda!
```
Data Manipulation Language (DML) adalah bahasa pemrograman yang digunakan untuk mengakses, memanipulasi dan mengelola data dalam database. DML memungkinkan pengguna untuk melakukan operasi seperti menambahkan data baru, memperbarui data yang ada, menghapus data, dan mengambil data untuk mendapatkan data yang dibutuhkan.

Di DML, pengguna dapat mengakses data menggunakan perintah SQL (Structured Query Language). SQL adalah bahasa standar untuk mengakses dan mengelola data dalam basis data relasional. Perintah SQL yang digunakan dalam DML adalah untuk menyisipkan, memodifikasi, menghapus, dan menampilkan data seperti dijelaskan di atas. 
```
