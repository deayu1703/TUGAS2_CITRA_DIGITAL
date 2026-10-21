# Implementasi Brightness Adjustment pada Citra Digital

Repository ini berisi tugas mata kuliah **Pengolahan Citra Digital** tentang penerapan metode *Brightness Adjustment* menggunakan Python untuk mengubah kecerahan gambar digital.

## Identitas

- **Nama:** Ade Ayu Wandira
- **NIM:** 24260007
- **Mata Kuliah:** Pengolahan Citra Digital

## Tujuan

Menerapkan metode *Brightness Adjustment* untuk meningkatkan dan menurunkan kecerahan citra digital serta menganalisis perubahan intensitas piksel.

## Metode

Brightness Adjustment dilakukan dengan menambahkan atau mengurangi nilai intensitas piksel menggunakan rumus:

\[
g(x,y) = f(x,y) + \beta
\]

Keterangan:
- \(f(x,y)\): intensitas piksel asli.
- \(g(x,y)\): intensitas piksel setelah pengolahan.
- \(\beta\): nilai perubahan kecerahan.

Pada program ini, nilai **+50** digunakan untuk mencerahkan gambar dan **-50** untuk menggelapkan gambar. Nilai intensitas dibatasi pada rentang 0–255.

## Library yang Digunakan

- **OpenCV (`cv2`)** untuk membaca dan menyimpan gambar.
- **NumPy (`numpy`)** untuk perhitungan intensitas piksel.
- **Matplotlib (`matplotlib.pyplot`)** untuk menampilkan dan membandingkan gambar.
- **OS (`os`)** untuk memperoleh informasi ukuran file.

## Hasil Pengolahan

Program menghasilkan tiga versi citra, yaitu gambar asli, gambar lebih terang, dan gambar lebih gelap.

| Jenis Gambar | Nilai Kecerahan | Rata-rata Intensitas |
|---|---:|---:|
| Gambar Asli | 0 | 63,58 |
| Gambar Terang | +50 | 113,45 |
| Gambar Gelap | -50 | 18,20 |

Hasil menunjukkan bahwa penambahan nilai kecerahan meningkatkan rata-rata intensitas piksel, sedangkan pengurangan nilai kecerahan menurunkannya.

## Struktur Repository

- `Brightness_Adjustment.ipynb` notebook berisi kode dan proses pengolahan citra.
- `foto asli.jpg` gambar sebelum pengolahan.
- `hasil/` folder penyimpanan gambar hasil Brightness Adjustment.

## Kesimpulan

Metode Brightness Adjustment berhasil digunakan untuk mengubah kecerahan citra digital. Perubahan terlihat melalui perbandingan gambar dan dibuktikan dengan perubahan nilai rata-rata intensitas piksel.

---

**Mata Kuliah:** Pengolahan Citra Digital  
**Universitas Nahdlatul Ulama Indonesia - 2026**
