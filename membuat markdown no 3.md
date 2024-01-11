3. Cara menggunakan markdown
   Format dasar Markdown
   Membuat Heading
Heading atau judul di markdown dapat dibuat dengan tanda pagar #.

Contoh:

# Heading 1
## Heading 2
### Heading 3
Maka akan menghasilkan:

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
Selain menggunakan tanda pagar, ada juga yang menggunakan simbol minus (-) dan samadengan (=) seperti ini:

Ini Headeing Level 1
====================

ini paragraf, bla bla bla...

Ini heading level 2
-------------------

ini paragraf, bla bla bla...
Format Teks
Jika kamu ingin menulis teks tebal, miring, dan strikeline, maka bisa dilakukan seperti ini:

**Tebal**
*miring*
~~strikeline~~
Selain menggunakan tanda bintang, untuk teks tebal dan miring bisa juga menggunakan garis bawah (underscore) seperti ini:

__teks tebal__
_teks miring_
Membuat Link
Link dapat kita buat dengan tanda kurung seperti ini:

[link ke petanikode](https://www.petanikode.com/)
Hasilnya:

link ke petanikode

Kita juga bisa menambahkan title untuk tooltips:

[link ke petanikode](https://www.petanikode.com/ "Pergi ke petanikode.com")
Hasilnya:

link ke petanikode

Selain menggunakan tanda kurung, kita juga bisa membuat link langsung dengan menuliskan URL lengkapnya.

Contoh:

https://en.wikipedia.org/wiki/Markdown
Maka akan menghasilkan:

https://en.wikipedia.org/wiki/Markdown

Menyisipkan Gambar
Caranya hampir sama dengan membuat link. Kita tinggal tambahkan tanda seru (!) di depannya.

Contoh:

![Gambar teks editor VS Code](https://www.petanikode.com/img/markdown/markdown-vscode.png)
Hasilnya:

Gambar teks editor VS Code
Membuat List
List dapat kita buat seperti ini:

* Milk
* Bread
    * Wholegrain
* Butter


1. Tidy the kitchen
2. Prepare ingredients
3. Cook delicious things
Hasilnya:

Milk
Bread
Wholegrain
Butter
Tidy the kitchen
Prepare ingredients
Cook delicious things
Untuk unordered list, kita bisa menggunakan tanda bintang (*) dan juga minus (-).

Contoh:

- item 1
- item 2
- item 3
Membuat Todo List atau Checklist
Sebenarnya ini pengembangan dari markdown. Tidak semua editor mendukung fitur ini.

Contoh:

**Tugas hari ini:**

- [x] Menulis artikel tentang markdown
- [ ] Belajar Git di Petanikode
- [ ] Belajar Bahasa pemrograman Rust
- [x] Membuat template blog dengan bootstrap
Maka akan menghasilkan seperti ini:

Tugas hari ini:

 Menulis artikel tentang markdown
 Belajar Bahasa pemrograman Rust
Pada HTML, kita mengenal tag <blockquote> untuk membuat kutipan. Pada markdown, kita bisa membuatnya seperti ini:

> To be or not to be, that is the question.
Hasilnya:

To be or not to be, that is the question.

Format Markdown Tingkat Lanjut
Format markdown yang baru saja kita pelajari adalah format dasar yang harus diingat. Masih ada beberapa format lagi:

Menulis Inline Code
Inline code sangat sering saya gunakan dalam teks. Cara membuatnya dengan menggunakan tanda (`).

Contoh:

Perintah `apt-get` adalah perintah untuk menginstall paket di Ubuntu.
Hasilnya:

Perintah apt-get adalah perintah untuk menginstall paket di Ubuntu.

Menulis Source Code
Source code sering saya tulis dengan markdown. Lalu menggunakan Prism.js untuk syntax higlighting.

Contoh:

```java
class HelloWorld{
    public static void main(String[] argumen){
        System.out.println("Hello World!");
    }
}
```
Hasilnya:

class HelloWorld{
    public static void main(String[] argumen){
        System.out.println("Hello World!");
    }
}
Tanda ``` berfungsi untuk menulis source code. Lalu pada pembuka kita tambahkan nama bahasanya agar teksnya berwarna (syntax highligting).

Membuat Tabel
Tabel di markdown dapat dibuat dengan cara sperti ini:

| Name  | Age |
| ----- | --- |
| Bob   | 27  |
| Alice | 23  |
