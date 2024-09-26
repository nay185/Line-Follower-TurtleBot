# Line Following TurtleBot
<p>Proyek ini menggunakan ROS untuk mendemostrasikan line following turtlebot yang disimulasikan di gazebo. Line following merupakan aplikasi yang mudah didesain untuk robot karena yang dibutuhkan hanyalah robot dengan kamera. Ini juga bisa digunakan untuk membuat model kesuliatan lebih tinggi tinggi yang lebih kompleks.</p>
<p>Proyek ini terutama menggunakan dua kelas utama, satu untuk mendeteksi garis dan satu untuk navigasi robot untuk melakukannya. Kelas deteksi pertama-tama memperoleh gambar dari turtlebot di lingkungan simulasi, melakukan penentuan ambang batas warna, penyembunyian dan deteksi titik pusat untuk mengomunikasikan arah yang diperlukan bagi robot untuk bergerak.</p>

<h2>Prosedur</h2>
<p>Awalnya, dunia Gazebo dibuat yang berisi beberapa dinding dan jalur yang harus diikuti oleh turtlebot. Dunia tersebut dapat dilihat di bawah ini:</p>

![Image Alt](https://github.com/nay185/nays/blob/f66a519d71230b168e9d132336400821d9743457/Projek%201.png)
