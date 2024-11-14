# Prasyarat, Pengenalan, Kelebihan, dan Instalasi Next.js

## Pre-requisite Next.js
Next.js adalah framework React fleksibel yang dapat memberikan kerangka pondasi untuk membuat aplikasi web yang cepat dan lengkap. Sebelum kita mengenal lebih jauh mengenai Next.js, alangkah lebih baik jika kita mengetahui apa saja yang dibutuhkan sebelum mengaplikasikan Next.js pada website mu!

### 1. Pemahaman tentang JavaScript dan ES6+
Next.js adalah framework berbasis React dan JavaScript, jadi penting untuk memahami dasar-dasar JavaScript. Untuk meningkatkan kehandalan kode, terutama dalam proyek besar, kamu juga dapat mempelajari *TypeScript, yaitu versi JavaScript yang lebih ketat dengan tipe data. Adapun fitur ES6+ seperti **let/const, **arrow function,  **destructuring, **async/await, dan **promise* juga sering digunakan dalam mengembangkan website menggunakan Next.js.

## 2. Dasar HTML dan CSS
Meskipun Next.js menangani banyak hal di sisi JavaScript, HTML, dan CSS masih menjadi bagian penting dalam pengembangan website. Kamu juga bisa melakukan kolaborasi dengan *TailwindCSS* berbasis utility yang memudahkan styling komponen dengan cepat serta menciptakan desain yang konsisten.

### 3. Pemahaman dasar React
Sudah diketahui bahwa Next.js dibangun di atas *React, oleh karenanya penting buat mu untuk menguasai React, terutama dalam memahami konsep **komponen, **props, **state, **useEffect, dan **routing dasar di React*.

### 4. Pengetahuan tentang Server-Side Rendering (SSR) dan Client-Side Rendering (CSR)
Next.js mendukung rendering server-side (SSR) dan cliendt-side (CSR), jadi kamu harus memahami terlebih dahulu perbedaan dan kapan harus menggunakan SSR atau CSR. Memahami konsep *Static Site Generation (SSG)* dan *Incremental Static Regeneration (ISR)* juga dapat membantu memahami strategi rendering yang lebih optimal.

### 5. Pemahaman tentang API dan Fetching 
Next.js sering kali digunakan untuk membuat aplikasi *full-stack, termasuk API. Oleh karena itu kamu harus memahami konsep **REST API* dan cara melakukan *fetch data* di React, seperti menggunakan fetch() atau library seperti *axios*.

### 6. Pemahaman dasar Node.js
Next.js memiliki beberapa fitur yang berjalan di server, seperti API Routes, sehingga pengetahuan dasar *Node.js* akan bermanfaat. Kamu juga perlu memahami cara pengelolaan paket menggunakan *npm* atau *yarn*.

### 7. Tools pengembangan seperti Git dan Terminal
Pemahaman tentang *Git* akan memudahkan dalam mengelola proyek dan berkolaborasi. Selain itu, ketika kamu sudah familiar dengan *command line*, kamu akan dengan mudah mengelola dependencies dan menjalankan perintah pengembangan Next.js.


  

## Pengenalan Next.js

  

### Apa Itu Next.js?

---

**Next.js** adalah framework open-source berbasis React yang digunakan untuk membuat aplikasi web full-stack menggunakan JavaScript. Dengan Next.js, pengembangan aplikasi web bisa menjadi lebih mudah dan cepat karena framework ini menawarkan fitur-fitur dan optimisasi bawaan.

  

Di balik layar, Next.js menangani banyak konfigurasi teknis, seperti _bundling_ (menggabungkan kode) dan _compiling_ (mengonversi kode), sehingga Anda bisa fokus pada pengembangan aplikasi tanpa perlu mengatur konfigurasi secara manual. Selain itu, Next.js mendukung **Server-side Rendering (SSR)** dan **Static Site Generation (SSG)**, yang membuat aplikasi lebih cepat, responsif, dan SEO-friendly.

  

---

### Cara Kerja Next.js

---

Next.js bekerja dengan memanfaatkan teknologi modern seperti React, Node.js, dan Webpack. Berikut adalah beberapa fitur utama yang mendukung cara kerja Next.js:

  

#### 1. Server-side Rendering (SSR) dan Static Site Generation (SSG)

Next.js memungkinkan pengguna untuk memilih antara **Server-side Rendering (SSR)** dan **Static Site Generation (SSG)** untuk menghasilkan halaman web:

  

-  **SSR (Server-side Rendering)**: Jika memilih SSR, halaman web akan dihasilkan di sisi server setiap kali pengguna memintanya. Metode ini memastikan halaman web dapat dihasilkan dan dikirim ke browser dengan cepat, sehingga cocok untuk konten yang sering diperbarui.

-  **SSG (Static Site Generation)**: SSG menghasilkan halaman statis pada saat build time (proses pembuatan), jadi halaman sudah siap ditampilkan di browser tanpa menunggu waktu pemuatan. Ini berguna untuk konten yang jarang berubah karena halaman lebih cepat diakses pengguna.

  

#### 2. Code Splitting

Next.js menggunakan teknik **code splitting** untuk membagi kode aplikasi menjadi beberapa file yang lebih kecil. Dengan cara ini:

- Pengguna hanya mengunduh kode yang diperlukan untuk halaman yang sedang mereka akses, bukan seluruh aplikasi.

- Teknik ini membuat waktu pemuatan lebih cepat dan efisien, karena hanya kode yang diperlukan yang dikirim ke browser.

  

#### 3. Optimasi Otomatis (Automatic Optimization)

Next.js mendukung **optimasi otomatis** untuk meningkatkan performa aplikasi web. Beberapa optimasi yang dilakukan secara otomatis oleh Next.js meliputi:

-  **Pengoptimalan gambar**: Menghasilkan gambar dalam format yang lebih kecil dan efisien.

-  **Preloading konten**: Memuat beberapa elemen penting di latar belakang untuk mengurangi waktu pemuatan.

-  **Optimasi ukuran gambar**: Menyesuaikan ukuran gambar secara otomatis agar lebih cepat dimuat.

  

Dengan optimasi ini, aplikasi web berjalan lebih cepat dan pengalaman pengguna menjadi lebih baik.

  

#### 4. Hot Module Replacement (HMR)

Fitur **Hot Module Replacement (HMR)** memungkinkan pengembang melihat perubahan kode secara langsung di browser tanpa harus memuat ulang halaman. Fitur ini sangat berguna dalam proses pengembangan karena:

- Mempercepat proses debugging.

- Mempermudah pengujian dan iterasi kode.

- Mengurangi waktu yang dibutuhkan dalam proses pengembangan, sehingga pengembang dapat bekerja lebih efisien.

  

---

  

### Fitur Utama Next.js dan Penjelasannya

---

  

| Fitur | Deskripsi |

|--------------------|---------------------------------------------------------------------------------------------------------|

| **Routing** | - Sistem `file-based routing`, otomatis membuat rute dari file di folder `pages/`. |

| | - Mendukung layout (tata letak) yang konsisten dan rute bersarang untuk pengaturan halaman. |

| | - Menyediakan loading states (status pemuatan) dan error handling (penanganan kesalahan). |

| **Rendering** | - Mendukung rendering di sisi klien (Client-side) dan server (Server-side) sesuai kebutuhan aplikasi. |

| | - Optimasi dengan rendering statis dan dinamis serta *streaming* di lingkungan Edge dan Node.js. |

| **Data Fetching** | - Pengambilan data langsung di Komponen Server untuk performa yang lebih baik. |

| | - Mendukung `memoization`, caching (penyimpanan data sementara), dan revalidasi data otomatis. |

| **Styling** | - Mendukung CSS Modules, Tailwind CSS, dan CSS-in-JS. |

| | - Memberikan fleksibilitas dalam menggunakan gaya sesuai preferensi tanpa konflik antar komponen. |

| **Optimasi** | - Optimasi gambar dengan `next/image`, optimasi font, dan pemuatan skrip hanya ketika diperlukan. |

| **TypeScript** | - Dukungan penuh untuk TypeScript, dengan pemeriksaan tipe otomatis dan kompilasi yang cepat. |

---

### Kapan Harus Menggunakan Next.js?

---

-  **Untuk Proyek Aplikasi Web Kompleks**: Next.js sangat berguna jika Anda bekerja pada aplikasi web yang besar, dinamis, atau memiliki banyak halaman dan interaksi pengguna.

-  **Saat Butuh SEO dan Performa Tinggi**: Karena Next.js mendukung server-side rendering dan optimasi, ini sangat baik untuk aplikasi yang butuh peringkat SEO tinggi dan performa cepat.

-  **Jika Menginginkan Fitur Lengkap di Satu Framework**: Dengan Next.js, banyak kebutuhan seperti rute, pengambilan data, dan optimasi sudah diurus, jadi Anda tidak perlu mencari banyak library tambahan.

## Kelebihan Next.js

Berikut beberapa kelebihan dari Next.js: 


### 1. SEO-Friendly
Dengan dukungan SSR dan SSG, Next.js sangat SEO-friendly karena memungkinkan mesin pencari merayapi konten dengan mudah. Dengan SEO yang baik, situs web yang dibuat dengan Next.js memiliki peluang lebih besar untuk mendapatkan peringkat tinggi di hasil pencarian Google.

### 2. Rendering yang Fleksibel (Server-Side dan Static Generation)
Next.js mendukung rendering dari sisi server (Server-Side Rendering atau SSR) dan pre-rendering statis (Static Generation atau SSG). SSR memungkinkan aplikasi memuat lebih cepat, sedangkan SSG menghasilkan halaman statis yang dihasilkan saat proses build, yang sangat cepat saat diakses.

### 3. Automatic Image Optimization
Fitur Image Optimization membantu dalam mempercepat waktu muat dengan pengaturan otomatis ukuran dan format gambar sesuai perangkat pengguna, yang meningkatkan performa aplikasi.

### 4. Mendukung TypeScript
Next.js mendukung TypeScript secara native, sehingga developer akan mendapatkan manfaat dari tipe data statis untuk menulis kode yang lebih aman dan dapat diandalkan.

### 5. Deployment yang Mudah
Next.js memiliki proses deployment yang mudah, terutama dengan dukungan Vercel. Pengembang dapat langsung menerbitkan aplikasi dengan konfigurasi minimal, serta menikmati fitur bawaan seperti optimasi performa, cache, dan integrasi CDN untuk pengalaman yang cepat dan mudah.



## Instalasi Next.js 15

Langkah-langkah berikut menjelaskan cara menginstall Next.js versi 15 untuk proyek baru.


### Prasyarat
Pastikan **Node.js** versi 14 atau lebih baru **sudah terpasang**. Jika belum, unduh dan instal dari [nodejs.org](https://nodejs.org/).

  

### Langkah-langkah Instalasi

#### 1. Buat Direktori Proyek Baru (Opsional)

Jika ingin membuat proyek Next.js dari awal, kalian bisa membuat folder baru:

  

`mkdir nama-proyek`

`cd nama-proyek`
  

#### 2. Inisialisasi Proyek Next.js

Gunakan perintah `npx` untuk membuat proyek Next.js dengan template bawaan:

`npx create-next-app@15`

Kalian akan ***diminta memasukkan nama proyek***. Setelah itu, ***folder baru akan dibuat dengan nama tersebut***, dan Next.js serta semua dependensi yang diperlukan akan diinstal secara otomatis.

  

#### 3. Jalankan Server Pengembangan
Setelah instalasi selesai, masuk ke direktori proyek dan jalankan perintah berikut untuk memulai server pengembangan:
`cd nama-proyek`

`npm run dev`

Aplikasi Next.js akan berjalan di `http://localhost:3000` secara default.

  

### Verifikasi Instalasi
Buka browser atau Chrome dan akses `http://localhost:3000`. Jika halaman default Next.js muncul, instalasi berhasil.

  

#### Catatan Tambahan:

1. Kamu juga bisa membuat proyek Next.js **menggunakan Yarn**:

`yarn create next-app`

2. Untuk kalian yang **memakai `pnpm`**, jalankan: `pnpm create next-app`

  

Dengan mengikuti langkah-langkah di atas, Next.js versi terbaru akan terpasang dan siap digunakan.
