
# Vue.js

Vue adalah sebuah kerangka kerja (framework) JavaScript yang digunakan untuk membangun antarmuka pengguna (user interfaces). Vue.js membantu pengembang dalam membuat bagian visual dari sebuah aplikasi web. Kerangka kerja ini menggunakan teknologi dasar web seperti HTML (HyperText Markup Language), CSS (Cascading Style Sheets), dan JavaScript.

## Pertanyaan Interview Vue.js

#### Apa itu Vue.js ?
Vue.js adalah sebuah kerangka kerja untuk membuat antarmuka pengguna yang dibangun di atas JavaScript. Ini adalah kerangka kerja yang progresif. Vue.js bertanggung jawab terhadap lapisan tampilan (view) dari sebuah aplikasi.

#### Apa itu Komponen prop dalam Vue.js ?
Komponen Prop adalah cara untuk mengirimkan data dari komponen induk ke komponen anak dalam Vue.js. Sebuah komponen dapat memiliki sebanyak mungkin prop yang diperlukan.

[![Visual prop](https://stopbyte.com/uploads/default/original/1X/f822160a43e6ad9aafe62eed9c407a7bf3df388a.png)](https://www.google.com/url?sa=i&url=https%3A%2F%2Fstopbyte.com%2Ft%2Fhow-to-pass-data-to-a-child-component-in-vuejs%2F983&psig=AOvVaw2EiPzQp88kwFwMAo0wZRVy&ust=1718855779254000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCKie2qPj5oYDFQAAAAAdAAAAABAK)


#### Di Vue.js apa yang dimaksud dengan reaktivitas ?
Ketika Anda mengubah nilai data, halaman akan diperbarui untuk mencerminkan perubahan tersebut. Properti data dan
properti yang dihitung di Vue bersifat reaktif.
[![Visual reaktif](https://v1.vuejs.org/images/data.png)](https://v1.vuejs.org/guide/reactivity.html)

#### Deskripsikan siklus hidup Vue.js?
Siklus hidup Vue.js adalah fungsi yang dijalankan oleh setiap instance Vue yang dijalankan oleh setiap instance Vue. Setiap Vue memiliki delapan lifecycle hooks.

[![Visual Siklus hidup](https://vuejs.org/assets/lifecycle.MuZLBFAS.png)](https://vuejs.org/guide/essentials/lifecycle)

Ini meliputi titik-titik seperti inisialisasi data `created`, penempelan ke DOM `mounted`, pembaruan data `updated`, dan penghapusan `destroyed`, 

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
