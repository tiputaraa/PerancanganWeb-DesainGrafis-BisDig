
# PerancanganWeb-DesainGrafis-BisDig

## Studi Kasus

Situs portofolio mahasiswa tidak terlihat rapi saat dibuka di smartphone. Gambar terlalu besar dan teks meluber ke luar layar.

## Konsep Responsive Design

Responsive design adalah pendekatan dalam pengembangan web yang memastikan tampilan situs dapat menyesuaikan diri secara optimal pada berbagai ukuran layar dan perangkat. Tujuannya adalah agar pengalaman pengguna tetap baik, baik saat dibuka di desktop, tablet, maupun smartphone.

## Media Queries

Media queries adalah fitur dalam CSS yang memungkinkan kita menerapkan gaya tertentu tergantung pada kondisi perangkat seperti lebar layar, tinggi layar, orientasi, dan resolusi. Dengan media queries, kita bisa menyesuaikan ukuran teks, gambar, margin, dan layout lainnya agar sesuai dengan perangkat pengguna.

## Contoh CSS

```css
/* styles.css */

/* Default styles for desktop */
img.responsive {
  width: 100%;
  height: auto;
  max-width: 800px;
  display: block;
  margin: 0 auto;
}

.container {
  width: 90%;
  margin: auto;
  font-family: Arial, sans-serif;
}

/* Responsive Design using Media Queries */
@media (max-width: 768px) {
  img.responsive {
    max-width: 100%;
  }

  .container {
    font-size: 16px;
    padding: 10px;
  }
}

@media (max-width: 480px) {
  .container {
    font-size: 14px;
  }
}
```

File CSS ini akan membuat layout gambar menjadi fleksibel dan teks tidak meluber keluar layar ketika dibuka dari perangkat mobile.
