# Lab11Web
Nama : Anggita Risqi Nur Clarita

NIM : 312210450

Kelas : TI.22.A.4

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Modul Praktikum 11|[Click Here](https://drive.google.com/file/d/1RethUEdwHr7mrhY2UioUPXBXEomRCSLe/view)|
|2|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|3|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|

## Praktikum
> ### Instruksi Praktikum
> 1. Persiapkan text editor misalnya **VSCode**.
>
> 2. Buat folder baru dengan nama **lab11_web** pada docroot webserver **(htdocs)**
>
> 3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Langkah-langkah Praktikum
### Jalankan Apache dan MySQL server dari menu XAMPP Control

![8](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/ee480a57-db6b-41e2-a46b-57c7945a2798)


1. **Buat Folder class**

    Folder yang dimaksud berisi file *config.php, database.php* dan *form.php*.

    ![1](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/4f5a4419-685d-4914-ba4b-b3787bd021e2)


2. **Buat Folder module**

    Folder yang dimaksud berisi file **home.php** (tapi saya tidak membuatnya, hehe) dan folder lagi yang bernama **artikel** dan di dalam folder tersebut berisi file *index.php, tambah.php, ubah.php, hapus.php* dan *contact.php* (*contact.php* tambahan dari saya).

    ![2](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/43f16a4e-9d47-4989-9434-653fb983bba0)


3. **Buat Folder template**
    
    Folder yang dimaksud berisi file *header.php, footer.php* dan *sidebar.php* (tapi saya tidak membuat file sidebar.php, hehe).

    ![3](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/4df64aff-6c33-46ba-a575-4d84adce3a47)


4. **Copy file library (class) dari praktikum 10 dan letakkan pada folder class.**

    File library (class) yang dimaksud adalah file *database.php* dan *form.php* dari **praktikum 10**. File-file tersebut berisi kelas Database dan Form yang akan digunakan dalam praktikum ini.

    **Library** adalah kumpulan kode yang dapat digunakan kembali untuk berbagai keperluan. Dalam praktikum ini, library yang digunakan adalah library *database* dan *form*. Library database menyediakan fungsi-fungsi untuk mengakses database, sedangkan library form menyediakan fungsi-fungsi untuk membuat dan memproses form.

    **CRUD** adalah singkatan dari *Create, Read, Update, Delete*. CRUD merupakan operasi dasar yang dapat dilakukan pada data dalam database. Dalam praktikum ini, modul artikel akan menerapkan operasi CRUD untuk mengelola data barang.

5. **Hasil Output Halaman Home :**


    ![4](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/759f239c-8e2b-4689-878f-0045202ef155)



6. **Hasil Output Tambah Barang :**


    ![5](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/91cd84aa-ab65-42bb-acc8-e7fdaff8fa08)



7. **Hasil Output Ubah Barang :**


    ![6](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/ca216848-2a0d-474a-9de8-bcd9d0315a66)



8. **Hasil Output Contact :** 


    ![7](https://github.com/AnggitaRisqiNC/Lab11Web/assets/115614419/216980c5-812e-44c5-ade3-359b970aeba6)


## Finish