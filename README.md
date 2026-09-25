# Lab1Web
## Identitas Mahasiswa
Nama: Alfi Iftihal Nurul Afiat
Nim: 312510041
Mata Kuliah: Pemograman Web
Praktikum: 1-HTML Dasar
## Deskripsi Praktikum
Praktikum ini membahas dasar dasar HTML (HyperText Markup Language) untuk membuat struktur halaman web sederhana.
Pada praktikum ini dilakukan pembuatan dokumen HTML dengan menerapkan:
- Struktur dasar HTML5
- Tag dan elemen HTML
- Heading
- Paragraf
- Formatting teks
- Gambar
- Hyperlink internal dan eksternal
- List HTML
- Komentar HTML
  ## Tujuan Praktikum
  Tujuan dari praktikum ini adalah:

1. Memahami struktur dasar dokumen HTML.
2. Memahami penggunaan tag-tag dasar HTML.
3. Membuat halaman web sederhana menggunakan HTML.
## Struktur Repository
```
Lab1Web/
│
├── index.html
├── halaman2.html
├── images/
│   └── profil.jpg
│
└── README.md
```
## Langkah Praktikum

## 1. Membuat Struktur Dasar HTML
pada tahap awal dibuat dokumen HTML5 menggunakan deklarasi:
```html
<!DOCTYPE html>
```
Kemudian dibuat struktur utama HTML yang terdiri dari:
- `<html>`
- `<head>`
- `<title>`
- `<body>`
Hasil:
![Struktur HTML](secreenshot%20struktur%20html.png)
---
## 2. Membuat Heading dan Paraghraf
Heading digunakan untuk membuat judul dan subjudul pada halaman web.
Tag yang digunakan:
```html
<h1>
<h2>
```
Sedangkan paraghraf dibuat menggunakan:
```html
<p>
```
Hasil:
![Heading dan Paragraf](./secreenshoots/paraghraf.png.png)

---
## 3. Formatting Text
Pada tahap ini dilakukan performatan teks menggunakan beberapa tag HTML seperti:
```html
<b>
<i>
<strong>
```
Contoh penggunaan:
```html
<p>
Belajar <b>HTML Dasar</b>
</p>
```
Hasil:
![Formatting Text](secreenshoots/format-text.png.png)

---
## 4. Menambahkan gambar
Gambar ditaambahkan menggunakan tag:
```html
<img>
```
dengan atribut:
- `src` untuk lokasi gambar
- `alt` untuk deskripsi gambar
contoh:
```html
<img src="images/profil.jpg" alt="Foto Profil">
```
Hasil:
![Gambar HTML](secreenshoots/gambar.png.png)

---
## 5. Membuat Hyperlink
Hyperlink digunakan untuk menghubungkan halaman web.
Pada praktikum ini dibuat:
### Hyperlink Internal 
Menghubungkan halaman `index.html` dengan `halaman2.html`.
contoh:
```html
<a href="halaman2.html">
Halaman 2
</a>
```
### Hyperlink Eksternal
Menghubungkan ke website lain.
Contoh:
```html
<a href="https://www.google.com">
Google
</a>
```
Hasil:
![Hyperlink](secreenshoots/hyperlink.png.png)

---
## 6. Membuat List HTML
Terdapat dua jenis list yang digunakan:
### Unordered List
List menggunakan tanda bullet.
```html
<ul>
<li>HTML</li>
<li>CSS</li>
</ul>
```
### Ordered List
List menggunakan urutan angka.
```html
<ol>
<li>Belajar HTML</li>
<li>Membuat Website</li>
</ol>
```
Hasil:

![List HTML](secreenshoots/list.png.png)

---
## 7. Membuat Komentar HTML
Komentar digunakan untuk memberikan catatan pada kode HTML.
Komentar ditulis menggunakan:
```html
<!-- komentar -->
```
Komentar tidak akan tampil pada halaman browser.
Hasil:
![Komentar HTML](secreenshoots/komentar.png.png)

---
# Hasil Website
Website hasil praktikum telah berhasil dibuat menggunakan HTML dasar dan dapat dijalankan melalui GitHub Pages.
Link Website:
https://github.com/alfiiftihalnurul-dot/Lab1Web
# Jawaban Pertanyaan


## 1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?

`<!DOCTYPE html>` berfungsi untuk memberi tahu browser bahwa dokumen menggunakan standar HTML5 sehingga halaman dapat ditampilkan sesuai aturan HTML yang benar.


---

## 2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?

**Tag** adalah penanda dalam HTML.

Contoh:

```html
<p>
```


**Elemen** adalah keseluruhan bagian HTML yang terdiri dari tag pembuka, isi, dan tag penutup.

Contoh:

```html
<p>Paragraf</p>
```


**Atribut** adalah informasi tambahan pada sebuah tag.

Contoh:

```html
<img src="gambar.jpg">
```


---

## 3. Apa perbedaan `<p>` dengan `<br>`?

`<p>` digunakan untuk membuat paragraf baru.

Contoh:

```html
<p>Ini paragraf</p>
```


Sedangkan `<br>` digunakan untuk membuat perpindahan baris.

Contoh:

```html
Halo<br>
Nama Saya
```


---

## 4. Apa fungsi atribut href pada tag `<a>`?

Atribut `href` digunakan untuk menentukan alamat tujuan hyperlink.

Contoh:

```html
<a href="halaman2.html">Halaman 2</a>
```


---

## 5. Apa perbedaan hyperlink internal dengan eksternal?

Hyperlink internal mengarah ke halaman dalam website yang sama.

Contoh:

```html
<a href="halaman2.html">
```


Hyperlink eksternal mengarah ke website lain.

Contoh:

```html
<a href="https://google.com">
```


---

## 6. Apa fungsi atribut src dan alt pada tag `<img>`?

`src` berfungsi menentukan lokasi file gambar.

`alt` berfungsi memberikan deskripsi gambar jika gambar tidak dapat ditampilkan.


Contoh:

```html
<img src="images/profil.jpg" alt="Foto">
```


---

## 7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?

`<ul>` digunakan untuk daftar tanpa urutan.

`<ol>` digunakan untuk daftar yang memiliki urutan.


---

## 8. Apa yang terjadi jika path gambar pada atribut src salah?

Jika path gambar salah, browser tidak dapat menemukan file sehingga gambar tidak akan tampil.

Browser dapat menampilkan ikon gambar rusak atau teks alternatif dari atribut `alt`.


---

## 9. Mengapa struktur heading h1 sampai h6 perlu digunakan secara terstruktur?

Heading digunakan untuk membuat hierarki informasi pada halaman web.

`<h1>` digunakan sebagai judul utama, sedangkan `<h2>` sampai `<h6>` digunakan sebagai bagian yang lebih kecil.


---

## 10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?

Komentar digunakan untuk memberikan catatan pada kode HTML yang tidak ditampilkan pada browser.

Contoh:

```html
<!-- Bagian Profil -->
```


---

# Kesimpulan

Pada praktikum HTML Dasar ini telah dipelajari struktur dasar HTML, penggunaan tag dan atribut, pembuatan heading, paragraf, gambar, hyperlink, list, dan komentar.

Dengan praktikum ini mahasiswa dapat memahami dasar pembuatan halaman web menggunakan HTML sebelum mempelajari teknologi lanjutan seperti CSS dan JavaScript.

