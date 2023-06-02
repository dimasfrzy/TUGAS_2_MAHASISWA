# TUGAS_2_MAHASISWA
Kode di atas mengimplementasikan tiga kelas: Mahasiswa, Jurusan, dan Universitas. Berikut adalah langkah-langkah dari kode tersebut:

1.Diawali dengan implementasi kelas Mahasiswa, Jurusan, dan Universitas.
  Kelas Mahasiswa memiliki tiga atribut: nama, nim, dan jurusan. Method __init__ digunakan untuk menginisialisasi objek Mahasiswa dengan nilai-nilai atribut tersebut.
  Kelas Jurusan memiliki dua atribut: NamaJurusan dan DaftarMahasiswa. NamaJurusan adalah nama jurusan yang diinisialisasi melalui method __init__, sedangkan DaftarMahasiswa adalah daftar mahasiswa yang akan ditambahkan ke dalam jurusan. Kelas ini juga memiliki method tambah_mahasiswa untuk menambahkan mahasiswa ke dalam daftar, dan tampilkan_daftar_mahasiswa untuk menampilkan informasi mahasiswa yang terdaftar dalam jurusan.
  Kelas Universitas memiliki dua atribut: NamaUniversitas dan DaftarJurusan. NamaUniversitas adalah nama universitas yang diinisialisasi melalui method __init__, sedangkan DaftarJurusan adalah daftar jurusan yang akan ditambahkan ke dalam universitas. Kelas ini juga memiliki method tambah_jurusan untuk menambahkan jurusan ke dalam daftar, dan tampilkan_daftar_jurusan untuk menampilkan nama-nama jurusan dalam universitas.
  
2.Membuat objek universitas_xyz yang merupakan objek dari kelas Universitas dengan nama "XYZ University".

3.Membuat objek jurusan_ti yang merupakan objek dari kelas Jurusan dengan nama "Teknik Informatika". Kemudian objek jurusan_ti ditambahkan ke dalam objek universitas_xyz dengan menggunakan method tambah_jurusan.

4.Membuat objek mahasiswa_kalian yang merupakan objek dari kelas Mahasiswa dengan nama "Kalian masing", NIM "Kalian masing", dan jurusan jurusan_ti. Kemudian objek mahasiswa_kalian ditambahkan ke dalam objek jurusan_ti dengan menggunakan method tambah_mahasiswa.

5.Menampilkan daftar jurusan di dalam objek universitas_xyz dengan menggunakan method tampilkan_daftar_jurusan.

6.Menampilkan daftar mahasiswa yang terdaftar dalam objek jurusan_ti di dalam objek universitas_xyz dengan menggunakan method tampilkan_daftar_mahasiswa.

Dengan langkah-langkah di atas, kode tersebut menggambarkan hubungan antara mahasiswa, jurusan, dan universitas dalam suatu struktur yang dapat digunakan untuk menyimpan dan mengelola informasi mengenai mahasiswa dan jurusan di dalam universitas.
