# Template LaTeX Paper IEEE

[![latest version](https://img.shields.io/github/v/release/b201lab/template-paper-ieee)](https://github.com/b201lab/template-paper-ieee/releases/)
[![commits since latest version](https://img.shields.io/github/commits-since/b201lab/template-paper-ieee/latest)](https://github.com/b201lab/template-paper-ieee/commits/master)
[![repo size](https://img.shields.io/github/repo-size/b201lab/template-paper-ieee)](https://github.com/b201lab/template-paper-ieee)
[![license](https://img.shields.io/github/license/b201lab/template-paper-ieee)](./LICENSE)
[![build status](https://img.shields.io/github/actions/workflow/status/b201lab/template-paper-ieee/ci.yaml?branch=main)](https://github.com/b201lab/template-paper-ieee/actions/workflows/ci.yaml)

Repositori ini berisi template [LaTeX](https://www.latex-project.org/) dari paper untuk konferensi yang diselenggarakan oleh [Institute of Electrical and Electronics Engineers](https://www.ieee.org/) (IEEE).
Template yang ada pada repositori ini menggunakan format resmi [IEEETran](http://www.michaelshell.org/tex/ieeetran/) versi 1.8b yang dikeluarkan oleh IEEE.
Repositori ini sendiri dibuat berdasarkan template yang ada pada repositori [latextemplates/IEEE](https://github.com/latextemplates/IEEE) dengan beberapa perubahan seperti pengurangan konten, penggunaan bahasa indonesia, dsb.

> Contoh file PDF dari template ini bisa dilihat di [sini](https://b201lab.github.io/template-paper-ieee/paper.pdf).

## Fitur

- Menggunakan format resmi yang dikeluarkan oleh IEEE.
- Disertai bagian-bagian yang diperlukan seperti abstrak, pustaka, dsb.
- Penomoran gambar dan referensi secara otomatis.
- Penambahan gambar, persamaan ilmiah, potongan kode, dan tabel pada dokumen.
- Kompilasi dokumen secara otomatis menggunakan [GitHub Actions](https://github.com/features/actions).

## Cara Menggunakan Template

Bagian utama dokumen terletak pada file [`main.tex`](./main.tex) yang digunakan untuk mengatur package LaTeX yang digunakan serta file lain yang akan dimasukkan pada dokumen.
Setelah kompilasi dilakukan, hasilnya akan ada beberapa file `main` dengan format yang berbeda.
Yang terutama adalah file `main.pdf` yang merupakan hasil akhir dari proses kompilasi dokumen.

Selain file `main.tex`, ada juga beberapa bagian lain dari template ini yang bisa diubah, seperti:
- **[`deskripsi`](./deskripsi)**, berisi file `*.tex` untuk deskripsi judul, penulis, abstrak, dan kata kunci.
- **[`gambar`](./gambar)**, berisi file `*.jpg`, `*.png`, maupun format gambar lain yang akan dimasukkan pada dokumen.
- **[`konten`](./konten)**, berisi file `*.tex` dari bagian-bagian yang akan dimasukkan pada dokumen.
- **[`program`](./program)**, berisi file kode program yang akan dimasukkan pada dokumen.
- **[`pustaka/pustaka.bib`](./pustaka/pustaka.bib)**, berisi daftar pustaka yang akan dimasukkan pada dokumen.

> Penjelasan lebih lanjut mengenai penggunaan template ini akan dijelaskan dengan comment yang tersedia pada setiap file yang ada.

## Contoh Penggunaan Template

Berikut adalah daftar repositori lain yang menggunakan template yang berasal dari repositori ini:
- [threeal/paper-simulasi-robot](https://github.com/threeal/paper-simulasi-robot).
- [chillytaka/buku_final](https://github.com/chillytaka/buku_final).

## Lisensi

Kode sumber yang ada pada repositori ini dilisensikan di bawah [lisensi MIT](./LICENSE).
