<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Biografi Saya</title>
    <link rel="stylesheet" href="./style.css" />
    <style>
      hr {
        margin: 40px;
      }
    </style>
  </head>
  <body>
    <!-- Header: Judul dan Navigasi -->
    <header>
      <nav>
        <ul>
          <li><a href="#tentang">Tentang</a></li>
          <li><a href="#pengalaman">Pengalaman</a></li>
          <li><a href="#kontak">Kontak</a></li>
          <li><a href="#data scrafing">Data scrafing</a></li>
        </ul>
      </nav>
    </header>

    <!-- Konten Utama -->
    <div class="main-box">
      <!-- Bagian Tentang (Biografi) -->
      <article id="tentang">
        <h3>Tentang Saya</h3>
        <p>
          Halo, saya adalah Gilang Maulana. Saya merupakan mahasiswa Teknik Informatika di Politeknik Negeri Bandung, angkatan 2024.
        </p>
          <p>
            <h3>Profil Diri:</h3>
            <ul>
              <li>Nama    : Gialng Maulana</li>
              <li>Kelas   : D4 1B</li>
              <li>NIM     : 241524044</li>
              <li>Domisili: Bandung</li>
            </ul>

          </p>
      </article>

      <!-- Bagian Pengalaman -->
      <article id="pengalaman">
        <h3>Pengalaman</h3>
        <p>
          saat ini saya belum memiliki pengalaman nyata pada dunia kerja pengembangan website,
          oleh karena itu saya harap pengembangan website ini dapat menjadi langkah awal.
         </p> 
      </article>

      <!-- Bagian Keterampilan: Tabel Keterampilan -->
      <article id="keterampilan">
        <h3>Keterampilan</h3>
        <table border="1">
          <thead>
            <tr>
              <th>Keterampilan</th>
              <th>Proficiency</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>C/C++</td>
              <td>Amateur</td>
            </tr>
            <tr>
              <td>HTML/CSS</td>
              <td>Amateur</td>
            </tr>
          </tbody>
        </table>
      </article>
    </div>

    <!-- Footer: Kontak -->
    <footer id="kontak">
      <h3>Hubungi Saya</h3>
      <p>(click gambar di bawah ini)</p>
      <nav>
        <a href="https://wa.me/qr/2HVARQLA76ZBB1">
          <img src="https://up.yimg.com/ib/th?id=OIP.ZsUQ2OMgjKhgnc9VjnWcfgHaHa&pid=Api&rs=1&c=1&qlt=95&w=112&h=112" alt="gambar 1" id="gambar-wa">
        </a>
        <a href="https://www.facebook.com/gilang.maulana.5076798">
          <img src="https://s.yimg.com/fz/api/res/1.2/bfhuQx02Fd0qgLXZbH1dww--~C/YXBwaWQ9c3JjaGRkO2ZpPWZpdDtoPTI0MDtxPTgwO3c9MjQw/https://s.yimg.com/zb/imgv1/ff6c2336-05c2-34bf-8d42-c8eb48fbacf1/t_500x300" alt="gambar 2" id="gambar-fb">
        </a>
      </nav>
    </footer>
  </body>
</html>
