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

DDL Script
![ddl script](https://user-images.githubusercontent.com/115356128/232086628-22b70bc8-a630-4288-ac6a-8436230baffc.png)


4. Script Tabel JadwalMengajar

![sc jadwal](https://user-images.githubusercontent.com/115356128/232086158-04c181f0-484e-44c2-8b5c-0dfabc75ecb4.png)

OUTPUT

![hasil jadwal](https://user-images.githubusercontent.com/115356128/232086204-ea35bdef-f3cd-4dba-8101-7e6a995a4d06.png)

6. Script Tabel KRSmahasiswa

![sc krs](https://user-images.githubusercontent.com/115356128/232086272-44e9ccad-dcc7-492e-83e3-ca874de3a03e.png)

OUTPUT

![hasil krs](https://user-images.githubusercontent.com/115356128/232086314-d76a19a8-6be6-494b-a807-0ece1cd9f890.png)
