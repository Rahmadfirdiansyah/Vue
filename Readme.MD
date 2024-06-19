
# Vue

Vue adalah sebuah kerangka kerja (framework) JavaScript yang digunakan untuk membangun antarmuka pengguna (user interfaces). Vue.js membantu pengembang dalam membuat bagian visual dari sebuah aplikasi web. Kerangka kerja ini menggunakan teknologi dasar web seperti HTML (HyperText Markup Language), CSS (Cascading Style Sheets), dan JavaScript.

## Pertanyaan Interview Vue.js

#### Apa itu Vue.js ?
Vue.js adalah sebuah kerangka kerja untuk membuat antarmuka pengguna yang dibangun di atas JavaScript. Ini adalah kerangka kerja yang progresif. Vue.js bertanggung jawab terhadap lapisan tampilan (view) dari sebuah aplikasi.

#### Apa itu Komponen prop dalam Vue.js ?
Komponen Prop adalah cara untuk mengirimkan data dari komponen induk ke komponen anak dalam Vue.js. Sebuah komponen dapat memiliki sebanyak mungkin prop yang diperlukan.

## Installasi

Disini saya menggunakan Vue CLI untuk membuat project Vue.

Menggunakan npm
```bash
npm install -g @vue/cli
```
menggunakan yarn
```bash
yarn global add @vue/cli
```

## Membuat Proyek Hello-world

Gunakan Git-bash untuk mengeksekusi kode
```bash
vue create hello-world
```
Jika perintah diatas bermasalah gunakan perintah `nano ~/.bashrc` lalu tambahkan baris `alias vue='winpty vue.cmd'` simpan dan keluar dari editor tekan **ctrl+x** lalu **Y** dan tekan **Enter** selanjutnya buka ulang Git-bash ketik perintah `source ~/.bashrc` dan sekarang gunakan perintah `vue create hello-world`
