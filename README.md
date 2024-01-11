1. Apa itu pengertian, manfaat, fungsi github
   GitHub adalah platform pengembangan software online berbasis cloud yang digunakan untuk menyimpan, melacak, dan sebagai tempat kolaborasi antar developer dalam suatu proyek perangkat lunak.
   **Fungsi GitHub**
   1. Memudahkan Kolaborasi Pengerjaan Project
   2. Mencegah Perubahan Kode yang Bisa Merusak Kode Asli
   3. Sebagai Portofolio Bagi Developer
      Manfaat Github
   1. Memudahkan Berkontribusi pada Proyek Open Source
   2. Dokumentasi
   3. Mencari dan Memamerkan Bakat
   4. Lacak Perubahan Kode di Seluruh Versi
   5. GitHub adalah Repository
   6. Opsi Integrasi
   7. Mengembangkan dan Menerapkan Strategi Manajemen
      
2. Cara membuat akun di github
   1. Buka https://github.com di browser web, lalu pilih Daftar.
   2. Masukkan alamat email Anda.
   3. Buat kata sandi untuk akun GitHub baru Anda, dan Masukkan nama pengguna juga.
   4. Verifikasi akun Anda dengan memecahkan teka-teki. Pilih tombol Mulai Teka-teki untuk melakukannya, lalu ikuti perintah.
   5. Setelah Anda memverifikasi akun Anda, pilih tombol Buat akun .
   6. Selanjutnya, GitHub mengirimkan kode peluncuran ke alamat email Anda.
   7. GitHub mengajukan beberapa pertanyaan untuk membantu menyesuaikan pengalaman Anda.
   8. Di layar Tempat tim berkolaborasi dan mengirim, Anda dapat memilih apakah Anda ingin menggunakan akun Gratis atau akun Tim. Untuk memilih akun Gratis , pilih tombol Lewati personalisasi .

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

4. Cara membuat repository di github
   Membuat repo GitHub
   1. Buka Visual Studio, lalu pilih Buat proyek baru.
       Tip
      Jika Anda belum memiliki proyek di Visual Studio untuk ditambahkan ke repositori, Anda dapat dengan cepat membuat aplikasi konsol C# baru dan menamainya MyNewApp. Visual Studio mengisi aplikasi baru Anda dengan kode "Halo, Dunia!" default.
   2. Dari menu Git , pilih Buat Repositori Git.
   3. Dalam dialog Buat repositori Git, di bawah bagian Dorong ke jarak jauh baru, pilih GitHub.
   4. Di bagian Buat repositori GitHub baru dari dialog Buat repositori Git, masukkan nama repositori yang ingin Anda buat.
   5. Setelah masuk dan memasukkan info repositori, pilih tombol Buat dan Dorong untuk membuat repositori dan menambahkan aplikasi Anda.

5. Cara menggunakan perintah gif melalui commdand
   Tutorial Git & Github (Command Prompt)
   Langkah 1. Membuat Project di Android Studio
   Langkah 2. Membuat repository baru di Github
   Langkah 3. Instalasi Git client
   Langkah 4. Membuat repository lokal dan menghubungkan dengan Github
   Langkah 5. Melakukan perubahan dan mengupload perubahan source code
   Mengecek status git
   
