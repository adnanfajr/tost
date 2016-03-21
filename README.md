# Praktikum Open Data Kit

Pembuatan Formulir Survei dan Pengambilan Data

##Format Isian :
 1. Nama Mahasiswa
 2. NRP Mahasiswa
 3. Nama Instansi
 4. Nama Perwakilan Instansi
 5. Nama Mata Kuliah
 6. Tujuan Survei
 7. Data yang diperlukan
 
##Dokumentasi :
 1. Install [Apache Tomcat 6][8] pada server
 
 2. Install [ODK Aggregate][9]
 
 2. Untuk membuat formulir dengan format XML menggunakan tools dari [ODK Build][5]. Hasil dari pembuatan formulir XML adalah sebagai berikut : [Formulir XML][1]

 3. Untuk melihat formulir yang dipergunakan dapat dilihat sebagai berikut :
  - [Link menuju form.doc][2] (Formulir pengajuan yang dibuat oleh mahasiswa secara cetak)
  - [Link menuju letter.doc][6] (Surat yang dibuat oleh pegawai TU setelah pengajuan formulir mahasiswa)
 
 4. Proses pengisian form melalui [ODK Collect][7] dapat dilihat sebagai berikut :
  - [Screenshot 1][3]
  - [Screenshot 2][4]
  
 5. Hasil dari pengisian formulir dapat dilihat pada http://<IP server>:8080/<directory instalasi ODK Aggregate>


  [1]: https://github.com/adnanfajr/tost/blob/master/form/Form%20Survei%20dan%20Pengambilan%20Data.xml
  [2]: https://github.com/adnanfajr/tost/blob/master/doc/form.doc
  [3]: https://github.com/adnanfajr/tost/blob/master/doc/screenshot-1.png
  [4]: https://github.com/adnanfajr/tost/blob/master/doc/screenshot-2.png
  [5]: https://opendatakit.org/use/build/
  [6]: https://github.com/adnanfajr/tost/blob/master/doc/letter.doc
  [7]: https://opendatakit.org/downloads/download-info/odk-collect-apk/
  [8]: https://tomcat.apache.org/download-60.cgi
  [9]: https://opendatakit.org/downloads/download-category/aggregate/