# Pinokio

![poster.png](poster.png)


## Introduction

![animation.gif](animation.gif)

Pinokio adalah peramban yang memungkinkan Anda **menginstal, menjalankan, dan mengotomatiskan AI apa pun secara lokal di komputer Anda**. Segala sesuatu yang dapat Anda jalankan di baris perintah dapat **diotomatiskan dengan skrip Pinokio**, dengan antarmuka pengguna yang ramah.

Anda dapat menggunakan Pinokio untuk mengotomatiskan apa saja, termasuk:

1. Menginstal aplikasi dan model AI
2. Mengelola dan Menjalankan aplikasi AI
3. Membuat alur kerja untuk mengatur aplikasi AI yang telah diinstal
4. Menjalankan perintah apa pun untuk mengotomatiskan hal-hal di mesin Anda
5. dan lainnya...

## Features

Berikut adalah apa yang membuat Pinokio istimewa:

1. **Lokal:** Semuanya diinstal dan dijalankan secara lokal. Tidak ada data Anda yang disimpan di server orang lain.
2. **Gratis:** Pinokio adalah aplikasi sumber terbuka yang 100% gratis untuk digunakan tanpa batasan. Tidak ada yang perlu Anda bayar untuk akses API, karena semuanya berjalan di mesin lokal Anda. Bermainlah dengan AI sebanyak yang Anda inginkan, gratis selamanya.
3. **Privasi:** Anda tidak perlu khawatir tentang mengirimkan data pribadi hanya untuk menjalankan AI, semuanya berjalan 100% secara pribadi di mesin Anda sendiri.
4. **Antarmuka Ramah Pengguna:** Pinokio menyediakan GUI yang ramah pengguna untuk menjalankan dan mengotomatiskan apa saja yang biasanya memerlukan terminal.
5. **Sudah Lengkap:** Pinokio adalah sistem yang berdiri sendiri. Anda tidak perlu menginstal program lain. Pinokio dapat mengotomatiskan apa saja, termasuk instalasi program/pustaka. Satu-satunya program yang Anda butuhkan adalah Pinokio.
6. **Lintas Platform:** Pinokio bekerja di SEMUA sistem operasi **(Windows, Mac, Linux)**.
7. **Hemat Penyimpanan dan Sumber Daya:** Pinokio memiliki banyak fitur optimasi yang akan menghemat ratusan gigabyte ruang disk Anda. Juga, banyak fitur optimasi sumber daya lainnya (seperti memori) semuanya dimungkinkan dengan Pinokio.
8. **Bahasa Skrip yang Ekspresif:** Skrip Pinokio adalah bahasa skrip otomatisasi yang kuat dengan fitur seperti memori, templating dinamis, dan API tingkat rendah yang dapat diperluas.
9. **Portabel:** Semuanya disimpan di bawah folder terisolasi dan semuanya ada sebagai file, yang berarti Anda dapat dengan mudah mencadangkan semuanya atau menghapus aplikasi hanya dengan menghapus file.


---

## Architecture

Pinokio mengambil inspirasi dari cara kerja komputer tradisional.

Seperti bagaimana komputer dapat melakukan segala macam hal berkat arsitekturnya yang komprehensif, Pinokio sebagai komputer virtual adalah platform komprehensif untuk menjalankan dan mengotomatiskan apa saja yang dapat Anda bayangkan dengan AI.

1. [Sistem File](#file-system): Di mana dan bagaimana Pinokio menyimpan file.
2. [Prosesor](#processor): Bagaimana Pinokio menjalankan tugas.
3. [Memori](#memory): Bagaimana Pinokio mengimplementasikan mesin status menggunakan memori asli bawaannya.
4. [Skrip](#script): Bahasa pemrograman yang mengoperasikan Pinokio.
5. [UI](#ui): Antarmuka pengguna (UI) tempat pengguna mengakses aplikasi.

---

# Install

> 1. [Windows](#windows)
> 2. [Mac](#mac)
> 3. [Linux](#linux)

## Windows

Pastikan untuk mengikuti **SEMUA langkah di bawah ini!**

#### Step 1. Download

<a class='btn' href='https://github.com/pinokiocomputer/pinokio/releases/download/3.6.23/Pinokio-3.6.23-win32.zip'><i class="fa-brands fa-windows"></i> Download for Windows</a>

#### Step 2. Unzip

Ekstrak file yang telah diunduh dan Anda akan melihat file penginstal .exe.


#### Step 3. Install

Jalankan file penginstal dan Anda akan melihat peringatan Windows berikut:

![win_install.gif](win_install.gif)

Pesan ini muncul karena aplikasi diunduh dari web, dan ini adalah tindakan standar Windows untuk aplikasi yang diunduh dari internet.

Untuk melewati ini,

1. Klik **"More Info"**
2. Kemudian klik **"Run anyway"**

---

## Mac


#### Step 1. Download

<a class='btn' href='https://github.com/pinokiocomputer/pinokio/releases/download/3.6.23/Pinokio-3.6.23-darwin-arm64.zip'><i class="fa-brands fa-apple"></i> Download for Apple Silicon Mac (M1/M2/M3/M4)</a>&nbsp;&nbsp;<a class='btn' href='https://github.com/pinokiocomputer/pinokio/releases/download/3.6.23/Pinokio-3.6.23-darwin-intel.zip'><i class="fa-brands fa-apple"></i> Download for Intel Mac</a>


#### Step 2. Install (PENTING!!)

![background.gif](background.gif)

Penginstal Pinokio untuk Mac dilengkapi dengan [Sentinel](https://itsalin.com/appInfo/?id=sentinel) yang sudah terpasang. Sentinel memungkinkan Anda menjalankan aplikasi sumber terbuka yang TIDAK ada di Apple App Store (seperti Pinokio saat ini).

Anda hanya perlu menyeret dan menjatuhkan Pinokio.app yang telah diinstal ke Sentinel untuk "Menghapus aplikasi dari Karantina".


---

## Linux

Untuk Linux, Anda dapat mengunduh dan menginstal langsung dari rilis terbaru di GitHub (Gulir ke bawah halaman untuk semua binari):

<a class='btn' href='https://github.com/pinokiocomputer/pinokio/releases/tag/3.6.23'><i class="fa-brands fa-linux"></i> Go to the Releases Page</a>

---

# Community Help

Untuk tetap mengikuti semua API dan integrasi aplikasi terbaru,

## X (Twitter)

> Follow [@cocktailpeanut](https://x.com/cocktailpeanut) on X to stay updated on all the new scripts being released and feature updates.

## Discord

> Join the [Pinokio discord](https://discord.gg/TQdNwadtE4) to ask questions and get help.

---

# Quickstart

## Pinokio File System

Pinokio adalah platform mandiri yang memungkinkan Anda menginstal aplikasi secara terisolasi.

1. **Isolated Environment:** Tidak perlu khawatir mengacaukannya konfigurasi dan lingkungan sistem global Anda
2. **Batteries Included:** Tidak perlu menginstal program yang diperlukan secara manual hanya untuk menginstal sesuatu (seperti **ffmpeg**, **node.js**, **visual studio**, **conda**, **python**, **pip**, dll.). Pinokio menanganinya secara otomatis.

Untuk mencapai ini, Pinokio **menyimpan semuanya di bawah satu folder terisolasi ("rumah pinokio")**, sehingga tidak pernah harus bergantung pada konfigurasi dan program di seluruh sistem Anda tetapi menjalankan semuanya secara mandiri.

Anda dapat mengatur folder **rumah pinokio** saat pertama kali menyiapkan Pinokio, serta mengubahnya ke lokasi baru dari tab **pengaturan**.

![settings.png](settings.png)

Jadi, di mana file-file disimpan? Klik tombol "Files" dari halaman utama:

![files.png](files.png)

Ini akan membuka folder rumah Pinokio di penjelajah file Anda:

![files_explorer.png](files_explorer.png)

Mari kita lihat sekilas apa yang dilakukan setiap folder:

1. `api`: menyimpan semua aplikasi yang diunduh (skrip).
    - Folder di dalam folder ini ditampilkan di halaman utama Pinokio Anda.
2. `bin`: menyimpan modul yang diinstal secara global yang dibagikan oleh beberapa aplikasi sehingga Anda tidak perlu menginstalnya secara berulang.
    - Misalnya, `ffmpeg`, `nodejs`, `python`, dll.
3. `cache`: menyimpan semua file yang secara otomatis di-cache oleh aplikasi yang Anda jalankan.
    - Ketika ada yang tidak berfungsi, menghapus folder ini dan memulai dari awal mungkin memperbaikinya.
    - Tidak masalah untuk menghapus folder `cache` karena akan diisi ulang oleh aplikasi yang Anda gunakan saat Anda mulai menggunakan aplikasi.
4. `drive`: menyimpan semua drive virtual yang dibuat oleh API [fs.link](#fslink) Pinokio
5. `logs`: menyimpan semua file log untuk setiap aplikasi.

> Anda dapat mempelajari lebih lanjut tentang sistem file [di sini](#file-system)

---

## Hello world

Mari kita tulis skrip yang mengkloning repositori git.

![gitjson.png](gitjson.png)

1. Buat folder bernama `helloworld` di bawah folder [api](#folder-structure) Pinokio.
2. Buat file bernama `git.json` di bawah folder Pinokio `api/helloworld`.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "git clone https://github.com/pinokiocomputer/test"
    }
  }]
}
```

Sekarang ketika Anda kembali ke Pinokio, Anda akan melihat repositori helloworld Anda muncul. Navigasikan ke dalamnya dan klik tab git.json untuk menjalankannya:

![gitclone.gif](gitclone.gif)

Anda akan melihat bahwa folder api/helloworld/test telah dikloning dari repositori https://github.com/pinokiocomputer/test.

---

## Templates

Kita juga dapat secara dinamis mengubah perintah apa yang dijalankan, dan bagaimana menjalankannya, menggunakan templat.

Sebagai contoh, mari kita tulis skrip yang menjalankan dir di Windows, dan ls di Linux dan Mac.

Di folder api/helloworld Anda, buat file bernama files.json:


```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "{{platform === 'win32' ? 'dir' : 'ls'}}"
    }
  }]
}
```


Ekspresi templat {{ }} berisi ekspresi JavaScript
Ada beberapa variabel yang tersedia di dalam setiap ekspresi templat, dan salah satunya adalah platform.
Nilai platform bisa berupa darwin (Mac), win32 (Windows), atau linux (Linux).
Ini berarti, di Windows, skrip di atas setara dengan:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "dir"
    }
  }]
}
```

Atau jika bukan Windows (Mac atau Linux), itu setara dengan:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "ls"
    }
  }]
}
```

> Anda dapat mempelajari lebih lanjut tentang templat [here](#template-interpreter)


---

## Environment Variable Setup

Seringkali, skrip mungkin memerlukan variabel lingkungan tertentu untuk diatur agar dapat berjalan dengan baik.

Meskipun variabel lingkungan dapat diatur di dalam tab "Configure", ini masih merepotkan dan sebagian besar pengguna tidak akan tahu variabel lingkungan mana yang perlu diisi.

Untuk mengatasi masalah ini, sebuah skrip dapat SECARA EKSPLISIT meminta variabel lingkungan yang diperlukan untuk berjalan.

Jika variabel lingkungan telah diatur, skrip akan langsung menggunakan variabel tersebut untuk memulai secara otomatis tanpa jeda.
Jika variabel lingkungan BELUM diatur, skrip TIDAK akan memulai, tetapi akan menampilkan formulir yang perlu diisi.
Untuk mencapai ini, Anda dapat melampirkan array pre dalam skrip.

```
{
  "pre": [<requirement>, <requirement>, ...]
}
```

Di mana `<requirement>` adalah objek yang menjelaskan variabel lingkungan yang diperlukan:

```
<requirement> := {
  env: <environment_variable_name>,
  title: <title>,
  description: <description>,
  default: <default_value>
}
```

- `<environment_variable_name>`: Nama variabel lingkungan yang diperlukan untuk memulai skrip.
- `<title>`: (opsional) Judul sederhana untuk bidang
- `<description>`: (opsional) Deskripsi untuk bidang
- `<default>`: (opsional) Nilai default yang akan diisi sebelumnya saat formulir ditampilkan.

Misalnya, katakanlah skrip kita terlihat seperti berikut:


```json
{
  "pre": [{
    "title": "custom env",
    "description": "set custom env 1",
    "env": "CUSTOM_ENV"
  }, {
    "title": "custom env 2",
    "description": "set custom env 2",
    "env": "CUSTOM_ENV2"
  }],
  "run": [
    ...
  ]
}
```

Ada 2 skenario yang mungkin:

1. Variabel lingkungan telah diisi sebelumnya oleh pengguna: Skrip akan langsung memulai secara otomatis seperti biasa.
2. Variabel lingkungan BELUM diatur: Dalam kasus ini, layar formulir berikut akan ditampilkan:

![pre_env.png](pre_env.png)


---

## Run in daemon mode

Ketika skrip Pinokio selesai dijalankan, setiap sesi shell yang dibuat melalui skrip akan dihentikan, dan semua proses terkait akan dimatikan.

Sebagai contoh, mari kita coba meluncurkan server web lokal menggunakan [http-server](https://github.com/http-party/http-server). Buat folder baru bernama httpserver di bawah folder Pinokio api, dan buat skrip baru bernama index.json:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "npx -y http-server"
    }
  }]
}
```

Kemudian kembali ke Pinokio dan Anda akan melihat aplikasi ini muncul di halaman utama. Klik masuk dan klik tab index.json di bilah sisi, dan itu akan memulai skrip ini, yang seharusnya meluncurkan server web menggunakan npx http-server.

Tapi masalahnya, tepat setelah meluncurkan server, itu akan segera mati dan Anda tidak akan bisa menggunakan server web.

Ini karena Pinokio secara otomatis mematikan semua proses yang terkait dengan skrip saat menyelesaikan semua langkah dalam array run.

Untuk menghindari ini, Anda perlu memberitahu Pinokio bahwa aplikasi ini harus tetap aktif meskipun semua langkah telah selesai dijalankan. Kita hanya perlu menambahkan atribut daemon:

```json
{
  "daemon": true,
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "npx -y http-server"
    }
  }]
}
```

Sekarang coba mulai ulang skrip, dan Anda akan melihat bahwa server web mulai berjalan dan tidak mati.

Server web akan melayani semua file di folder saat ini (dalam hal ini hanya `index.json`), seperti ini:

![httpserver.gif](httpserver.gif)

Anda dapat menghentikan skrip dengan menekan tombol "stop" di bagian atas halaman.


> Pelajari lebih lanjut tentang mode daemon [here](#daemon-mode)


---

## Run multiple commands

Anda juga dapat menjalankan beberapa perintah dengan satu panggilan `shell.run`.

Mari kita coba contohnya. Kita akan menginstal, menginisialisasi, dan meluncurkan mesin dokumentasi dalam satu skrip.

Hal-hal seperti ini biasanya tidak dapat diakses oleh orang biasa (karena Anda harus menjalankan ini di terminal), tetapi dengan Pinokio, itu semudah satu klik.

1. Buat folder bernama `docsify` di bawah folder Pinokio `api` f
2. Buat file bernama `index.json` di bawah folder `api/docsify`. File `index.json` harus terlihat seperti berikut:


```json
{
  "daemon": true,
  "run": [{
    "method": "shell.run",
    "params": {
      "message": [
        "npx -y docsify-cli init docs",
        "npx -y docsify-cli serve docs"
      ]
    }
  }]
}
```

Contoh ini melakukan 2 hal:

1. Menginisialisasi proyek Dokumentasi [docsify](https://docsify.js.org/)
2. Meluncurkan server pengembangan docsify

Ketika Anda mengklik tautan server pengembangan dari terminal Pinokio, itu akan membuka halaman dokumentasi di peramban web:

![docsify.gif](docsify.gif)


> Pelajari lebih lanjut tentang API `shell.run` [here](#shell)

---


## Install packages into venv

Salah satu kasus penggunaan umum untuk Pinokio adalah:

1. Membuat/mengaktifkan venv
2. Menginstal dependensi ke dalam venv yang diaktifkan

Mari kita coba contoh sederhana. Contoh ini adalah aplikasi gradio minimal dari [official gradio tutorial](https://www.gradio.app/guides/quickstart#building-your-first-demo)

Pertama, buat folder bernama `gradio_demo` di bawah folder `api` Pinokio.

Selanjutnya, buat file bernama `app.py` di folder `api/gradio_demo`.

```python
# app.py
import gradio as gr

def greet(name, intensity):
    return "Hello, " + name + "!" * int(intensity)

demo = gr.Interface(
    fn=greet,
    inputs=["text", "slider"],
    outputs=["text"],
)
demo.launch()
```

Kita juga memerlukan file `requirements.txt` yang terlihat seperti ini:

```
# requirements.txt
gradio
```

Terakhir, kita memerlukan skrip `install.json` yang akan menginstal dependensi dari file `requirements.txt`:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "venv": "env",
      "message": "pip install -r requirements.txt"
    }
  }]
}
```

Struktur folder akan terlihat seperti ini:

```
/PINOKIO_HOME
  /api
    /gradio_demo
      app.py
      requirements.txt
      install.json
```

Kembali ke Pinokio dan Anda akan melihat aplikasi `gradio_demo` Klik ke UI dan klik tab `install.json` , dan itu akan:

1. Membuat folder `venv` di jalur `env`
2. Mengaktifkan lingkungan `env`
3. Menjalankan `pip install -r requirements.txt`, yang akan menginstal dependensi `gradio` ke dalam lingkungan `env`.

Berikut adalah seperti apa proses instalasi itu (perhatikan bahwa folder `env` baru telah dibuat di akhir):

![gradio_install.gif](gradio_install.gif)


> Pelajari lebih lanjut tentang API venv [here](#venv)

---

## Run an app in venv

> dilanjutkan dari [last section](#install-packages-into-venv).

Sekarang mari kita tulis skrip sederhana yang akan meluncurkan server gradio dari `app.py` dari bagian terakhir. Buat file bernama `start.json` di folder yang sama:

```json
{
  "daemon": true,
  "run": [{
    "method": "shell.run",
    "params": {
      "venv": "env",
      "message": "python app.py"
    }
  }]
}
```

Kembali ke Pinokio dan Anda akan melihat bahwa file `start.json` sekarang juga muncul di bilah sisi. Klik untuk memulai skrip `start.json` Ini akan:

1. Mengaktifkan lingkungan `env` yang kita buat dari langkah instalasi
2. Menjalankan `python app.py` in **daemon mode** dalam mode daemon (`daemon: true`), yang akan meluncurkan server gradio dan menjaganya tetap berjalan.

Ini akan terlihat seperti ini:

![gradio_start.gif](gradio_start.gif)

> Pelajari lebih lanjut tentang API venv [here](#venv)


---

## Download a file

Pinokio memiliki API lintas platform untuk mengunduh file dengan mudah dan andal (termasuk percobaan ulang otomatis, dll.).

Mari kita coba menulis skrip sederhana yang mengunduh PDF.

Pertama, buat folder bernama `download` di bawah folder Pinokio `api` , lalu buat file bernama `index.json`:

```json
{
  "run": [{
    "method": "fs.download",
    "params": {
      "uri": "https://arxiv.org/pdf/1706.03762.pdf",
      "dir": "pdf"
    }
  }]
}
```

Ini akan mengunduh file di https://arxiv.org/pdf/1706.03762.pdf ke folder bernama `pdf` (API `fs.download` secara otomatis membuat folder di lokasi tersebut jika belum ada). Berikut adalah seperti apa tampilannya:

![fsdownload.gif](fsdownload.gif)

> Pelajari lebih lanjut tentang API `fs.download` [here](#fsdownload)

---

## Call a script from another script

Dalam banyak kasus, Anda mungkin ingin memanggil skrip dari skrip lain. Beberapa contoh:

1. Skrip orkestrasi yang menjalankan `stable diffusion` lalu `llama`.
2. Agen yang memulai `stable diffusion`, segera membuat permintaan untuk menghasilkan gambar, dan akhirnya menghentikan server `stable diffusion` untuk menghemat sumber daya, secara otomatis.
3. Agen yang membuat permintaan ke titik akhir `llama` , lalu meneruskan responsnya ke titik akhir `stable diffusion`.

Kita dapat mencapai ini menggunakan API `script`:

- `script.start`: Memulai skrip jarak jauh (Unduh terlebih dahulu jika belum ada)
- `script.return`: Jika skrip saat ini adalah proses anak, tentukan nilai kembalian, yang akan tersedia di langkah berikutnya dari skrip pemanggil.


Berikut adalah contohnya. Mari kita buat `caller.json` dan `callee.json`sederhana:


`caller.json`:

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "callee.json",
      "params": { "a": 1, "b": 2 }
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{input}}"
    }
  }]
}
```

Langkah pertama, `caller.json` akan memanggil `callee.json` dengan parameter `{ "a": 1, "b": 2 }`.

Objek parameter ini akan diteruskan ke `callee.json` sebagai `args`:

`callee.json`:

```json
{
  "run": [{
    "method": "script.return",
    "params": {
      "ressponse": "{{args.a + args.b}}"
    }
  }]
}
```

Skrip `callee.json` segera mengembalikan nilai `{{args.a + args.b}}` dengan panggilan `script.return`.

Akhirnya `caller.json` akan memanggil langkah terakhir `log`, , yang akan mencetak nilai `{{input}}`, yaitu nilai kembalian dari `callee.json`. Ini akan mencetak `3`:

![localscript.gif](localscript.gif)

---

## Install, start, and stop remote scripts

Bagian terakhir menjelaskan bagaimana Anda dapat memanggil skrip dari dalam repositori yang sama. Tapi bagaimana jika Anda ingin memanggil skrip dari repositori lain?

API `script.start` juga dapat mengunduh dan menjalankan skrip jarak jauh secara langsung.

Buat folder bernama `remotescript` di bawah folder Pinokio `api` dan buat file bernama `install.json` di bawah `api/remotescript`:

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "https://github.com/cocktailpeanutlabs/moondream2.git/install.js"
    }
  }, {
    "method": "script.start",
    "params": {
      "uri": "https://github.com/cocktailpeanutlabs/moondream2.git/start.js"
    }
  }, {
    "id": "run",
    "method": "gradio.predict",
    "params": {
      "uri": "{{kernel.script.local('https://github.com/cocktailpeanutlabs/moondream2.git/start.js').url}}",
      "path": "/answer_question_1",
      "params": [
        { "path": "https://media.timeout.com/images/105795964/750/422/image.jpg" },
        "Explain what is going on here"
      ]
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{input}}"
    }
  }, {
    "method": "script.stop",
    "params": {
      "uri": "https://github.com/cocktailpeanutlabs/moondream2.git/start.js"
    }
  }]
}
```

1. Langkah pertama memulai skrip [https://github.com/cocktailpeanutlabs/moondream2.git/install.js](https://github.com/cocktailpeanutlabs/moondream2/blob/main/install.js).

    - Jika repositori `moondream2.git` sudah ada di Pinokio, itu akan menjalankan skrip [install.js](https://github.com/cocktailpeanutlabs/moondream2/blob/main/install.js).

    - Jika belum ada, Pinokio secara otomatis mengkloning repositori `https://github.com/cocktailpeanutlabs/moondream2.git` terlebih dahulu, lalu memulai skrip [install.js](https://github.com/cocktailpeanutlabs/moondream2/blob/main/install.js) setelah itu.

2. Setelah instalasi selesai, kemudian meluncurkan aplikasi gradio menggunakan skrip [https://github.com/cocktailpeanutlabs/moondream2.git/start.js](https://github.com/cocktailpeanutlabs/moondream2/blob/main/start.js) . Skrip ini akan kembali setelah server dimulai.

3. Sekarang kita menjalankan `gradio.predict`, menggunakan API [kernel.script.local()](#kernelscriptlocal) untuk mendapatkan objek variabel lokal untuk skrip [start.js](https://github.com/cocktailpeanutlabs/moondream2/blob/main/start.js) , lalu mengambil nilai `url`-nya (yang diatur secara terprogram di dalam skrip `moondream2.git/start.js`).
    - Pada dasarnya, langkah ini membuat permintaan ke titik akhir gradio untuk bertanya kepada LLM "Jelaskan apa yang sedang terjadi di sini", dengan mengirimkan sebuah gambar.
4. Selanjutnya, nilai kembalian dari `gradio.predict` dicatat ke terminal menggunakan API `log`.
5. Terakhir, kita menghentikan skrip `moondream2/start.js` untuk mematikan server gradio moondream menggunakan API `script.stop`.
    - Jika kita tidak memanggil `script.stop`, aplikasi moondream2 akan tetap berjalan bahkan setelah skrip ini berhenti.

Berikut adalah seperti apa tampilannya:

![remotescript.gif](remotescript.gif)


> Kemampuan untuk menjalankan `script.start`, lalu `script.stop` sangat berguna untuk menjalankan AI di komputer pribadi, karena kebanyakan komputer pribadi tidak memiliki memori yang tak terbatas, dan komputer Anda akan cepat kehabisan memori jika Anda tidak dapat mematikan mesin AI ini secara terprogram.
>
> Dengan `script.stop`, Anda dapat memulai skrip, mendapatkan responsnya, dan segera mematikannya setelah tugas selesai, yang akan membebaskan memori sistem, yang dapat Anda gunakan untuk menjalankan tugas AI berikutnya.

---

## Build UI with pinokio.js

Aplikasi Pinokio memiliki struktur sederhana:

1. [shortcut](#shortcut): Pintasan aplikasi yang muncul di halaman utama Pinokio.
2. [app](#app): Tata letak UI utama untuk aplikasi


`Shortcut`

![shortcut.png](shortcut.png)

`App`

- **Menu:** Bilah sisi yang menampilkan semua tautan yang dapat Anda jalankan (serta status berjalannya)
- **Window:** Viewport yang menampilkan **halaman web**, atau **terminal** yang menjalankan skrip

![main.gif](main.gif)


Secara default, jika Anda tidak memiliki file `pinokio.js` di proyek Anda,

- **shortcut** menampilkan nama folder sebagai judul, dan ikon default sebagai ikon aplikasi.
- **menu** menampilkan semua file `.js` atau `.json` di akar repositori Anda.

Meskipun ini nyaman untuk memulai, itu tidak cukup fleksibel:

1. Anda tidak dapat mengontrol apa yang ditampilkan di bilah menu
2. Anda tidak dapat mengontrol bagaimana skrip diluncurkan (misalnya dengan meneruskan `params`)
3. Anda tidak dapat mengontrol bagaimana aplikasi ditampilkan
    - Judul aplikasi akan menjadi nama folder Anda
    - Tidak ada deskripsi
    - Ikon hanya akan menampilkan ikon default.

Untuk menyesuaikan bagaimana aplikasi itu sendiri berperilaku, Anda akan ingin menulis skrip UI bernama `pinokio.js`.

Mari kita coba menulis UI minimal:

1. Buat folder bernama `downloader` di folder `/PINOKIO_HOME/api`
2. Tambahkan ikon apa saja ke folder `/PINOKIO_HOME/api/downloader` dan beri nama `icon.png`
3. Buat file bernama `/PINOKIO_HOME/api/downloader/download.json`
4. Buat file bernama `/PINOKIO_HOME/api/downloader/pinokio.js``

**/PINOKIO_HOME/api/downloader/icon.png**

![doraemon.png](doraemon.png)


**/PINOKIO_HOME/api/downloader/download.json**

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "git clone {{input.url}}"
    }
  }]
}
```

**/PINOKIO_HOME/api/downloader/pinokio.js**

```js
module.exports = {
  title: "Download Anything",
  description: "Download a git repository",
  icon: "icon.png",
  menu: [{
    text: "Start",
    href: "download.json",
    params: {
      url: "https://github.com/cocktailpeanut/dalai"
    }
  }]
}
```

Hasil akhir akan terlihat seperti ini di penjelajah file Anda:

![downloader.png](downloader.png)

Sekarang kembali ke Pinokio dan segarkan, dan Anda akan melihat aplikasi Anda muncul:

![custom_ui_preview.png](custom_ui_preview.png)

- Judul menampilkan `Download Anything`
- Deskripsi menampilkan `Download a git repository`
- Ikon adalah `icon.png` yang telah kita tambahkan

Sekarang ketika Anda mengklik masuk ke aplikasi, Anda akan melihat berikut:

![custom_ui.gif](custom_ui.gif)

1. Anda akan melihat item menu `Start`.
2. Klik ini untuk menjalankan `download.json` yang ditentukan oleh atribut `href`.
3. Perhatikan juga bahwa skrip meneruskan nilai https://github.com/cocktailpeanut/dalai `params.url`.
4. `params` yang diteruskan ke `download.json` tersedia sebagai variabel `input` , sehingga `git clone {{input.url}}` akan diinstansiasi sebagai `git clone https://github.com/cocktailpeanut/dalai`.


---

## Publish your script

Setelah Anda memiliki repositori skrip yang berfungsi, Anda dapat mempublikasikannya ke layanan hosting git apa pun dan membagikan URL-nya, dan siapa saja akan dapat menginstal dan menjalankan skrip Anda.

---


## Install script from any git url

Anda dapat menginstal repositori skrip Pinokio apa pun dengan sangat mudah:

1. Klik tombol "Unduh dari URL" di bagian atas halaman Discover.
2. Masukkan URL git (Anda juga dapat menentukan cabang secara opsional).

![download_git.gif](download_git.gif)

---

## List your script on the directory

Jika Anda mempublikasikan ke GitHub, Anda dapat menandai repositori Anda dengan "pinokio" agar muncul di bagian "terbaru" pada halaman Discover.

![tagging.gif](tagging.gif)

Sekarang itu akan secara otomatis muncul di bagian "terbaru" (di bagian bawah halaman "Discover"):

![latest.png](latest.png)

> Pinokio membangun bagian "Terbaru" secara otomatis dari API GitHub "/repositories" di https://api.github.com/search/repositories?q=topic:pinokio&sort=updated&direction=desc
>
> Jadi jika Anda telah menandai repositori Anda sebagai "pinokio" tetapi tidak muncul, periksa hasil API, dan coba cari tahu mengapa itu tidak termasuk di sana.

---

## Auto-generate app launchers

Meskipun penting untuk memahami bagaimana semua ini bekerja, dalam banyak kasus Anda mungkin menginginkan "kombinasi peluncur" sederhana, yang mencakup:

1. **App install script:** Menginstal dependensi aplikasi
2. **App Launch script:** Memulai aplikasi
3. **UI:** Menampilkan UI peluncur.
4. **Reset script:** Mengatur ulang status aplikasi ketika ada yang salah.
5. **Update script:** Memperbarui aplikasi ke versi terbaru dengan 1 klik.

Kasus penggunaan ini sering dibutuhkan, sehingga kami telah mengimplementasikan program yang secara otomatis menghasilkan skrip ini secara instan. Ini disebut [Gepeto](#gepeto).

---

# Gepeto

<div class='videoWrapper'>
  <iframe width="1280" height="720" src="https://www.youtube.com/embed/D8jdowszkMg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

[Gepeto](https://gepeto.pinokio.computer) adalah program yang memungkinkan Anda **secara otomatis menghasilkan skrip Pinokio, khususnya untuk peluncur aplikasi.**

Mari kita mulai dengan benar-benar menghasilkan aplikasi dan peluncurnya dalam 1 menit.

## Gepeto Quickstart


<div class='videoWrapper'>
  <iframe width="1280" height="720" src="https://www.youtube.com/embed/I-_W-MkV8tc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>


#### 1. Install Gepeto on Pinokio

Jika Anda belum menginstal Gepeto, temukan di Pinokio dan instal terlebih dahulu.

![gepeto_install.gif](gepeto_install.gif)

#### 2. Generate Scripts with Gepeto

Anda akan melihat UI web sederhana yang memungkinkan Anda mengisi formulir. Untuk kesederhanaan, cukup masukkan `Helloworld` sebagai nama proyek, dan tekan **kirim**.

![gepeto_generate.gif](gepeto_generate.gif)

Ini akan menginisialisasi sebuah proyek. Ketika Anda kembali ke halaman utama Pinokio,

1. Anda akan melihat entri baru bernama `Helloworld`. Klik masuk dan Anda akan melihat layar peluncur.
2. Juga, periksa folder `/PINOKIO_HOME/api` Anda, Anda akan menemukan folder baru bernama `Helloworld` dengan beberapa file skrip.

#### 3. Install and Start the App

Sekarang mari kita klik tombol **instal** untuk menginstal aplikasi, dan ketika selesai, klik **mulai** untuk meluncurkan.

![gepeto_launch.gif](gepeto_launch.gif)

Anda akan melihat aplikasi [gradio](https://www.gradio.app/) minimal, di mana Anda dapat memasukkan prompt dan itu akan menghasilkan gambar menggunakan [Stable Diffusion XL Turbo](https://stability.ai/news/stability-ai-sdxl-turbo).

Jadi apa yang baru saja terjadi? Kita baru saja **membuat proyek kosong**, yang dilengkapi dengan aplikasi demo minimal.

Mari kita lihat setiap file yang dihasilkan di bagian berikutnya.

---

## Creating an empty project

Gepeto secara otomatis menghasilkan satu set skrip minimal yang diperlukan untuk peluncur aplikasi. Peluncur aplikasi tipikal memiliki fitur berikut:

1. **Install:** Menginstal dependensi yang diperlukan untuk menjalankan aplikasi. (`install.js`)
2. **Launch:** Meluncurkan aplikasi itu sendiri. (`start.js`)
3. **Reset install:** Mengatur ulang semua dependensi yang diinstal jika Anda perlu menginstal ulang dari awal. (`reset.js`)
4. **Update:** Memperbarui ke versi terbaru ketika proyek diperbarui. (`update.js`)
5. **GUI:** Skrip yang menjelaskan seperti apa tampilan dan perilaku peluncur di halaman utama Pinokio dan sebagai menu bilah sisi. (`pinokio.js`)

Berikut adalah seperti apa tampilannya:

![type2.png](type2.png)

Perhatikan bahwa selain skrip yang disebutkan di atas, Gepeto juga menghasilkan beberapa file tambahan:

- `app.py`: Aplikasi demo sederhana. **Ganti ini dengan kode Anda sendiri.**
- `requirements.txt`: Menyatakan semua dependensi PIP yang diperlukan untuk `app.py`. **Ganti dengan milik Anda sendiri.**
- `icon.png`: File ikon default untuk aplikasi. **Ganti dengan milik Anda sendiri.**
- `torch.js`: `torch.js` adalah skrip utilitas yang dipanggil dari `install.js`. Karena torch digunakan di hampir semua proyek AI, dan cukup sulit untuk menginstalnya secara lintas platform, skrip ini disertakan secara default. Anda tidak perlu khawatir tentang file ini, cukup pahami bahwa itu digunakan oleh `install.js`. **Jangan sentuh.**


File penting yang perlu diperhatikan adalah file `app.py` dan `requirements.txt`:

##### app.py

```python
import gradio as gr
import torch
from diffusers import DiffusionPipeline
import devicetorch
# Get the current device ("mps", "cuda", or "cpu")
device = devicetorch.get(torch)
# Create a diffusion pipeline
pipe = DiffusionPipeline.from_pretrained("stabilityai/sdxl-turbo").to(device)
# Run inference
def generate_image(prompt):
    return pipe(
      prompt,
      num_inference_steps=2,
      strength=0.5,
      guidance_scale=0.0
    ).images[0]
# Create a text input + image output UI with Gradio
app = gr.Interface(fn=generate_image, inputs="text", outputs="image")
app.launch()
```

##### requirements.txt

Berikut adalah pustaka yang diperlukan untuk menjalankan `app.py`.

```
transformers
accelerate
diffusers
gradio
devicetorch
```

Jadi bagaimana file-file ini sebenarnya digunakan?

##### install.js

Jika Anda melihat ke dalam `install.js`, Anda akan melihat bahwa itu menjalankan `pip install -r requirements.txt` untuk menginstal dependensi di dalam file, seperti ini:

```javascript
module.exports = {
  run: [
    // Delete this step if your project does not use torch
    {
      method: "script.start",
      params: {
        uri: "torch.js",
        params: {
          venv: "env",                // Edit this to customize the venv folder path
          // xformers: true   // uncomment this line if your project requires xformers
        }
      }
    },
    // Edit this step with your custom install commands
    {
      method: "shell.run",
      params: {
        venv: "env",                // Edit this to customize the venv folder path
        message: [
          "pip install -r requirements.txt"
        ],
      }
    },
    //  Uncomment this step to add automatic venv deduplication (Experimental)
    //  {
    //    method: "fs.link",
    //    params: {
    //      venv: "env"
    //    }
    //  },
    {
      method: "notify",
      params: {
        html: "Click the 'start' tab to get started!"
      }
    }
  ]
}
```

1. Langkah pertama menjalankan `script.start` untuk memanggil skrip bernama `torch.js`. Ini menginstal torch.
2. Langkah kedua menjalankan file `pip install -r requirements.txt` untuk menginstal semua yang ada di file tersebut.


##### start.js

Dan jika Anda melihat ke dalam `start.js`, Anda akan melihat bahwa itu menjalankan `python app.py` untuk memulai aplikasi:

```javascript
module.exports = {
  daemon: true,
  run: [
    // Edit this step to customize your app's launch command
    {
      method: "shell.run",
      params: {
        venv: "env",                // Edit this to customize the venv folder path
        env: { },                   // Edit this to customize environment variables (see documentation)
        message: [
          "python app.py",    // Edit with your custom commands
        ],
        on: [{
          // The regular expression pattern to monitor.
          // When this pattern occurs in the shell terminal, the shell will return,
          // and the script will go onto the next step.
          "event": "/http:\/\/\\S+/",

          // "done": true will move to the next step while keeping the shell alive.
          // "kill": true will move to the next step after killing the shell.
          "done": true
        }]
      }
    },
    // This step sets the local variable 'url'.
    // This local variable will be used in pinokio.js to display the "Open WebUI" tab when the value is set.
    {
      method: "local.set",
      params: {
        // the input.event is the regular expression match object from the previous step
        url: "{{input.event[0]}}"
      }
    },
//    Uncomment this step to enable local wifi sharing (access the app from devices on the same network)
//    {
//      method: "proxy.start",
//      params: {
//        uri: "{{local.url}}",
//        name: "Local Sharing"
//      }
//    }
  ]
}
```

1. Langkah pertama memulai shell (`shell.run`), mengaktifkan lingkungan venv di jalur `env` dan menjalankan perintah `python app.py`. Kemudian memantau terminal shell untuk ekspresi reguler yang cocok dengan pola `/http:\/\/[0-9.:]+/`, dan melanjutkan ke langkah berikutnya (tanpa mengakhiri shell).

2. Langkah berikutnya mengatur variabel lokal `url` menggunakan kecocokan ekspresi reguler dari langkah sebelumnya.

Dan itulah sekilas tentangnya!

---

## Customizing the empty project

Untuk memastikan kita memahami intinya, mari kita coba memodifikasi kode yang dihasilkan secara otomatis untuk menyesuaikan aplikasi:


BUka `app.py` dan ganti saja dengan sesuatu yang lebih sederhana:

```python
import gradio as gr
def square(num):
    return num * num
app = gr.Interface(fn=square, inputs="number", outputs="number")
app.launch()
```

Juga, Anda bisa menghapus semua kecuali `gradio` di file `requirements.txt`:

```
gradio
```

Sekarang mulai ulang aplikasi. Ini adalah aplikasi yang mengambil angka dan menampilkan nilai kuadratnya:

![gepeto_customize.gif](gepeto_customize.gif)

---

## Creating a launcher for an existing project

Sejauh ini kita telah melihat "cara memulai dari nol". Tapi bagaimana jika Anda ingin mengambil proyek YANG SUDAH ADA dan hanya menulis peluncur untuknya? Misalnya:

1. Menulis peluncur lokal untuk ComfyUI
2. Menulis peluncur lokal untuk FaceFusion
3. Menulis peluncur lokal untuk HuggingFace Spaces
4. Dan seterusnya.

Dalam kasus ini, Anda hanya perlu memasukkan URL repositori git dari proyek yang ingin Anda instal, saat pertama kali menjalankan Gepeto.

![gepeto_web.png](gepeto_web.png)

Sebagai contoh, mari kita bangun peluncur untuk [Devika](https://github.com/stitionai/devika), sebuah aplikasi agen AI.

1. Masukkan `devika-launcher` di bidang **Project Name**.
2. Masukkan `https://raw.githubusercontent.com/stitionai/devika/main/.assets/devika-avatar.png` di bidang **Icon URL**.
3. Masukkan `https://github.com/stitionai/devika` di bidang **Git URL** .

dan tekan **Submit**. Gepeto akan menghasilkan peluncur. Pergi ke halaman utama Pinokio, Anda akan menemukan peluncur yang dihasilkan:

![devika-home.png](devika-home.png)

Klik masuk dan klik tab **Files** untuk melihat folder yang dihasilkan:

![devika-view.gif](devika-view.gif)

Folder yang dihasilkan terlihat seperti ini:

![devika-launcher.png](devika-launcher.png)

> Perhatikan bahwa tidak ada file `app.py` dan `requirements.txt` Karena kita memasukkan URL git, Gepeto mengasumsikan bahwa logika aplikasi yang sebenarnya akan ada di repositori tersebut dan oleh karena itu tidak menghasilkan dua file ini dalam kasus ini.

##### install.js

Mari kita lihat `install.js`. Ini adalah skrip default yang dihasilkan oleh Gepeto:

```javascript
module.exports = {
  run: [
    // Edit this step to customize the git repository to use
    {
      method: "shell.run",
      params: {
        message: [
          "git clone https://github.com/stitionai/devika app",
        ]
      }
    },
    // Delete this step if your project does not use torch
    {
      method: "script.start",
      params: {
        uri: "torch.js",
        params: {
          venv: "env",                // Edit this to customize the venv folder path
          path: "app",                // Edit this to customize the path to start the shell from
          // xformers: true   // uncomment this line if your project requires xformers
        }
      }
    },
    // Edit this step with your custom install commands
    {
      method: "shell.run",
      params: {
        venv: "env",                // Edit this to customize the venv folder path
        path: "app",                // Edit this to customize the path to start the shell from
        message: [
          "pip install gradio devicetorch",
          "pip install -r requirements.txt"
        ]
      }
    },
    //  Uncomment this step to add automatic venv deduplication (Experimental)
    //  {
    //    method: "fs.link",
    //    params: {
    //      venv: "env"
    //    }
    //  },
    {
      method: "notify",
      params: {
        html: "Click the 'start' tab to get started!"
      }
    }
  ]
}
```

Ini adalah skrip instalasi default yang dihasilkan oleh Gepeto.

1. Jalankan `git clone https://github.com/stitionai/devika app` untuk mengunduh repositori git ke folder `app`.
2. Panggil skrip `torch.js` yang secara otomatis menginstal versi Pytorch yang benar untuk sistem saat ini.
3. Jalankan `pip install gradio devicetorch` lalu `pip install -r requirements.txt`, untuk menginstal dependensi.

Skrip ini mengasumsikan bahwa instalasi untuk proyek Devika ini dilakukan dengan menjalankan `pip install -r requirements.txt`. Biasanya ini berhasil dalam banyak kasus, tetapi seringkali Anda harus melakukan lebih banyak. Mari kita lihat README.md Devika:

![devika-install.png](devika-install.png)

Tampaknya kita perlu melakukan lebih banyak:

1. Selain `pip install -r requirements.txt` kita juga perlu menginstal **Playwright**.
2. Juga kita perlu menginstal dependensi NPM dengan `bun install`.

Mari kita edit `install.js` untuk mencerminkan ini:

```js
module.exports = {
  run: [
    // Edit this step to customize the git repository to use
    {
      method: "shell.run",
      params: {
        message: [
          "git clone https://github.com/stitionai/devika app",
        ]
      }
    },
    // Delete this step if your project does not use torch
    {
      method: "script.start",
      params: {
        uri: "torch.js",
        params: {
          venv: "env",                // Edit this to customize the venv folder path
          path: "app",                // Edit this to customize the path to start the shell from
          // xformers: true   // uncomment this line if your project requires xformers
        }
      }
    },
    // Edit this step with your custom install commands
    {
      method: "shell.run",
      params: {
        venv: "env",                // Edit this to customize the venv folder path
        path: "app",                // Edit this to customize the path to start the shell from
        message: [
          "pip install gradio devicetorch",
          "pip install -r requirements.txt",
          "playwright install --with-deps"
        ]
      }
    },
    {
      method: "shell.run",
      params: {
        path: "app/ui",
        message: "npm install"
      }
    },
    //  Uncomment this step to add automatic venv deduplication (Experimental)
    //  {
    //    method: "fs.link",
    //    params: {
    //      venv: "env"
    //    }
    //  },
    {
      method: "notify",
      params: {
        html: "Click the 'start' tab to get started!"
      }
    }
  ]
}
``` 

1. Perhatikan langkah ketiga: kita telah menambahkan perintah tambahan `playwright install --with-deps`
2. Selain itu, langkah keempat telah ditambahkan, di mana kita menjalankan `npm install` (Kita menggunakan `npm install` alih-alih `bun install` yang diusulkan karena secara efektif sama dan NPM sudah termasuk dalam Pinokio secara default)

##### start.js

Sekarang, bagaimana dengan benar-benar meluncurkan aplikasi? Skrip `start.js` menangani ini. Mari kita lihat file yang dihasilkan:

```js
module.exports = {
  daemon: true,
  run: [
    {
      method: "shell.run",
      params: {
        venv: "env",                // Edit this to customize the venv folder path
        env: { },                   // Edit this to customize environment variables (see documentation)
        path: "app",                // Edit this to customize the path to start the shell from
        message: [
          "python app.py",    // Edit with your custom commands
        ],
        on: [{
          // The regular expression pattern to monitor.
          // When this pattern occurs in the shell terminal, the shell will return,
          // and the script will go onto the next step.
          "event": "/http:\/\/\\S+/",

          // "done": true will move to the next step while keeping the shell alive.
          // "kill": true will move to the next step after killing the shell.
          "done": true
        }]
      }
    },
    {
      // This step sets the local variable 'url'.
      // This local variable will be used in pinokio.js to display the "Open WebUI" tab when the value is set.
      method: "local.set",
      params: {
        // the input.event is the regular expression match object from the previous step
        url: "{{input.event[0]}}"
      }
    },
  ]
}
```

Skrip yang dihasilkan menjalankan perintah default `python app.py`. Tapi lagi-lagi, kita perlu membuat beberapa perubahan pada perintah. Mari kita lihat file `README.md` di https://github.com/stitionai/devika?tab=readme-ov-file#installation:

![devikia-launch.png](devika-launch.png)

1. Kita perlu menjalankan `python devika.py` untuk backend
2. Kita kemudian perlu menjalankan `bun run start` untuk frontend (atau `npm run start`)

Berikut adalah seperti apa skrip `start.js` yang diperbarui:

```js
module.exports = {
  daemon: true,
  run: [
    {
      method: "shell.run",
      params: {
        venv: "env",                // Edit this to customize the venv folder path
        env: { },                   // Edit this to customize environment variables (see documentation)
        path: "app",                // Edit this to customize the path to start the shell from
        message: [
          "python devika.py",
        ],
        on: [{
          "event": "/Devika is up and running/i",   // wait until the terminal prints this message
          "done": true
        }]
      }
    },
    {
      method: "shell.run",
      params: {
        path: "app/ui",
        message: "npm run start",
        on: [{ "event": "/http:\/\/\\S+/", "done": true }]
      }
    },
    {
      // This step sets the local variable 'url'.
      // This local variable will be used in pinokio.js to display the "Open WebUI" tab when the value is set.
      method: "local.set",
      params: {
        // the input.event is the regular expression match object from the previous step
        url: "{{input.event[0]}}"
      }
    },
  ]
}
```

Berikut adalah perubahannya:

1. Alih-alih `python app.py`, sekarang kita memiliki perintah `python devika.py`.
2. Perintah `python devika.py` menunggu hingga terminal menemui pola ekspresi reguler `/Devika is up and running/i`. Ini memastikan bahwa itu tidak melanjutkan ke langkah berikutnya hingga server benar-benar mulai.
3. Juga, kita memiliki langkah baru yang menjalankan `npm run start`
4. `npm run start` menunggu hingga terminal menemui pola `/http:\/\/\\S+/`. Ini memanfaatkan fakta bahwa aplikasi mencetak URL titik akhir di akhir peluncuran.

Setelah kita memperbarui kedua file `install.js` dan `start.js` mari kita kembali ke Pinokio dan coba menginstal dan memulai:

![devika_launch.gif](devika_launch.gif)

---

## Adding cross platform support

Seringkali kita menemui proyek yang TIDAK mendukung lintas platform secara langsung. (Misalnya hanya mendukung CUDA--GPU Nvidia--dan tidak mendukung Mac).

> Biasanya Anda dapat dengan cepat mengetahui apakah suatu aplikasi mendukung lintas platform, hanya dengan mencari **cuda** di code aplikasi.
>
> Jika ada bagian dari kode yang meng-hardcode **"cuda"** Jika ada bagian dari kode yang meng-hardcode
>
> Kita dapat memperbaiki ini dengan hanya menemukan semua kejadian ini dan mengganti **"cuda"** yang di-hardcode dengan nilai perangkat yang benar untuk platform pengguna.

Mari kita lalui prosesnya langkah demi langkah:

1. Buat salinan dari proyek asli (sehingga Anda dapat mengedit kode).
2. Perbarui kode aplikasi untuk mendukung lintas platform
3. Gunakan repositori salinan ini (bukan proyek asli) saat menjalankan Gepeto.

### 1. Create a copy

Sebagian besar proyek AI sumber terbuka di-host di [GitHub](https://github.com) atau [HuggingFace](https://huggingface.co).

Sebelum Anda membuat perubahan pada kode, Anda perlu membuat salinan sendiri dengan melakukan fork pada proyek asli untuk membuat versi Anda sendiri.

#### HuggingFace Spaces

Di HuggingFace Spaces, Anda perlu **duplicate the space**. Pastikan untuk mengaturnya ke **public**.

![hf_duplicate.gif](hf_duplicate.gif)


#### GitHub

Di GitHub, Anda perlu **melakukan fork pada repositori**.

![gh_fork.gif](gh_fork.gif)

### 2. Clone the repository to your machine

Sekarang setelah Anda memiliki salinan Anda sendiri, Anda dapat mengkloning repositori git ke mesin lokal Anda untuk mulai mengedit kode.

Katakanlah repositori Anda adalah https://huggingface.co/spaces/cocktailpeanut/cosxl

Anda dapat mengkloningnya dari terminal menggunakan:

```
git lfs install
git clone https://huggingface.co/spaces/cocktailpeanut/cosxl
```

Perintah `git lfs install` digunakan untuk mengizinkan file besar, yang sering terjadi ketika repositori berisi file besar.

Sekarang Anda siap untuk mengedit file untuk menambahkan dukungan lintas platform.

### 3. Add device support for Torch

Banyak proyek hanya mendukung perangkat CUDA (GPU Nvidia). Untuk memastikan aplikasi mendukung perangkat non-CUDA, kita perlu:

1. Temukan semua kemunculan `"cuda"` dalam kode aplikasi (misalnya `app.py`)
2. Ganti semua kemunculan tersebut dengan variabel bernama `device`
3. Pastikan variabel `device` diatur dengan benar

Mari kita lihat contohnya:

```python
# app.py
import torch
...
pipe_edit = CosStableDiffusionXLInstructPix2PixPipeline.from_single_file(edit_file, num_in_channels=8)
pipe_edit.scheduler = EDMEulerScheduler(sigma_min=0.002, sigma_max=120.0, sigma_data=1.0, prediction_type="v_prediction")
pipe_edit.to("cuda")

pipe_normal = StableDiffusionXLPipeline.from_single_file(normal_file, torch_dtype=torch.float16)
pipe_normal.scheduler = EDMEulerScheduler(sigma_min=0.002, sigma_max=120.0, sigma_data=1.0, prediction_type="v_prediction")
pipe_normal.to("cuda")
```

Kode Python ini memiliki "cuda" yang di-hardcode di dua tempat:

- `pipe_edit.to("cuda")`
- `pipe_normal.to("cuda")`

Dalam kasus ini, kita perlu mengganti string "cuda" ini dengan perangkat aktual pengguna.

Kita dapat melakukannya dengan menggunakan pustaka minimal bernama devicetorch.

Pertama tambahkan baris di requirements.txt untuk menyertakan devicetorch:

```
# requirements.txt
devicetorch
```

Selanjutnya, impor `devicetorch` dan panggil `devicetorch.get(torch)` untuk mendapatkan nama perangkat aktual:

```python
# app.py
import torch
import devicetorch
...

# Dapatkan nama perangkat saat ini secara dinamis: akan mengembalikan "cuda", "mps", atau "cpu".
device = devicetorch.get(torch)

pipe_edit = CosStableDiffusionXLInstructPix2PixPipeline.from_single_file(edit_file, num_in_channels=8)
pipe_edit.scheduler = EDMEulerScheduler(sigma_min=0.002, sigma_max=120.0, sigma_data=1.0, prediction_type="v_prediction")
pipe_edit.to(device)

pipe_normal = StableDiffusionXLPipeline.from_single_file(normal_file, torch_dtype=torch.float16)
pipe_normal.scheduler = EDMEulerScheduler(sigma_min=0.002, sigma_max=120.0, sigma_data=1.0, prediction_type="v_prediction")
pipe_normal.to(device)
```

Ada beberapa kasus di mana ini jauh lebih rumit dan metode ini tidak berhasil (Dalam kasus ini saya sarankan untuk meminta penulis proyek asli untuk secara resmi mendukung MPS).

Namun dalam kebanyakan kasus, pendekatan di atas cukup untuk menambahkan dukungan lintas platform untuk aplikasi AI apa pun.

### 4. More torch handling


Seringkali ketika Anda melakukan pemeriksaan "cuda" (seperti disebutkan di atas), Anda JUGA akan menemui potongan kode khusus CUDA seperti ini:

```python
torch.cuda.empty_cache()
```

Sekali lagi, kode ini mengasumsikan bahwa itu hanya akan berjalan pada perangkat CUDA, dan akan GAGAL jika Anda menjalankan kode pada perangkat MPS (Mac).

Pustaka `devicetorch` juga memiliki metode utilitas bernama `devicetorch.empty_cache(torch)` untuk menangani ini. Cukup beri komentar pada kode yang ada dan ganti dengan devicetorch.empty_cache(torch)

```python
#torch.cuda.empty_cache()
devicetorch.empty_cache(torch)
```

Ini akan secara otomatis menjalankan:

- `torch.cuda.empty_cache()` jika perangkat adalah CUDA.
- `torch.mps.empty_cache()` jika perangkat adalah MPS.

### 4. Run gepeto

Sekarang dorong pembaruan kembali ke repositori salinan Anda. Kita akan menggunakan repositori INI untuk menginstal aplikasi (bukan repositori asli).

Ketika Anda menjalankan Gepeto, Anda akan melihat bidang **Git URL** :

![gepeto_web.png](gepeto_web.png)

Masukkan URL repositori Anda, dan tekan "Kirim". Itu saja! Coba instal dengan skrip yang dihasilkan!

---

## Downloading files with script


Kadang-kadang, proyek akan memberitahu Anda bahwa Anda perlu mengunduh file tertentu dan menempatkannya di dalam jalur folder tertentu.

Misalnya, mungkin dikatakan:

> Download `https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/resolve/main/sd_xl_base_1.0.safetensors` to `models/checkpoints`
> 
> Download `https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/resolve/main/sd_xl_refiner_1.0.safetensors` to `models/checkpoints`

Kita sebenarnya dapat menggunakan API bawaan [fs.download](#fsdownaload) untuk mengunduh file-file ini:


```json
{
  "run": [{
    ...
  }, {
    "method": "fs.download",
    "params": {
      "url": "https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/resolve/main/sd_xl_base_1.0.safetensors",
      "dir": "app/models/checkpoints"
    }
  }, {
    "method": "fs.download",
    "params": {
      "url": "https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/resolve/main/sd_xl_refiner_1.0.safetensors",
      "dir": "app/models/checkpoints"
    }
  }]
}
```

Ini akan mengunduh file-file ke direktori tersebut.

Jika folder belum ada, itu akan secara otomatis membuat folder terlebih dahulu.


---

## Porting huggingface spaces to local

1. Buat salinan
2. Gunakan file `app.py` dan `requirements.txt`
3. Hapus bagian spaces

Kadang-kadang sebuah aplikasi mungkin memiliki beberapa perubahan tambahan.

1. **Huggingface spaces:** Ketika mencoba membuat versi lokal dari ruang HuggingFace yang memanfaatkan [Zero GPU](https://huggingface.co/zero-gpu-explorers), Anda perlu mengomentari deklarasi `@spaces.GPU`.

2. **Environment variables:** Ketika kode menggunakan variabel lingkungan Cari `os.environ.get(...)`,ini berarti aplikasi mengharapkan variabel lingkungan.

### 1. Handling Huggingface Space

Beberapa ruang HuggingFace menggunakan fitur yang disebut [Zero GPU](https://huggingface.co/zero-gpu-explorers), yang secara dinamis menetapkan GPU ke setiap aplikasi berdasarkan permintaan.

Ini adalah fitur khusus HuggingFace, dan tidak diperlukan saat berjalan secara lokal. Berikut adalah contoh penggunaannya:

```python
import spaces
from diffusers import DiffusionPipeline

pipe = DiffusionPipeline.from_pretrained(...)
pipe.to('cuda')

@spaces.GPU
def generate(prompt):
    return pipe(prompt).images

gr.Interface(fn=generate, inputs=gr.Text(), outputs=gr.Gallery()).launch()
```

Karena kita tidak menggunakan fitur `spaces` , kita dapat **mengomentari baris-baris terkait spaces ini**:

- `import spaces`
- `@spaces.GPU`

Hasilnya:

```python
#import spaces
from diffusers import DiffusionPipeline

pipe = DiffusionPipeline.from_pretrained(...)
pipe.to('cuda')

#@spaces.GPU
def generate(prompt):
    return pipe(prompt).images

gr.Interface(fn=generate, inputs=gr.Text(), outputs=gr.Gallery()).launch()
```


### 2. Environment Variables

Kadang-kadang kode mungkin mencari variabel lingkungan sistem. Untuk mengetahui apakah ini terjadi, cari: `os.environment.get`.

Misalnya, katakanlah kode memiliki:

```python
# app.py
mps_fallback = os.environ.get("PYTORCH_ENABLE_MPS_FALLBACK")
```

Anda dapat meneruskan variabel lingkungan `PYTORCH_ENABLE_MPS_FALLBACK` dengan mengatur objek `env` saat meluncurkan `app.py`, seperti ini:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "python app.py",
      "env": {
        "PYTORCH_ENABLE_MPS_FALLBACK": "1"
      }
    }
  }]
}
```





---

# Guides

Bagian ini akan menjelaskan beberapa teknik yang sering digunakan untuk menulis skrip.

## Install Torch

Banyak proyek AI bergantung pada [PyTorch](https://pytorch.org/). Namun, menginstal PyTorch sedikit rumit. Mari kita lihat contohnya.

### Problem

Bayangkan sebuah proyek dengan struktur folder berikut ,struktur ini tipikal untuk [huggingface gradio space](https://huggingface.co/spaces):

```
app.py
requirements.txt
install.js
```

- `app.py`: File aplikasi yang sebenarnya
- `requirements.txt`: File yang mencakup semua deklarasi dependensi, yang dapat diinstal dengan `pip install -r requirements.txt`
- `install.js`: Skrip Pinokio untuk menginstal proyek

File `requirements.txt` mungkin terlihat seperti ini:

```
diffusers
accelerate
torch
transformers
gradio
```


Cara naif untuk menulis skrip instalasi `install.js` mungkin seperti ini:

```javascript
module.exports = {
  "run": [{
    "method": "shell.run",
    "params": {
      "venv": "env",
      "message": "pip install -r requirements.txt"
    }
  }]
}
```

Namun ini tidak akan berhasil dalam banyak kasus, karena dengan PyTorch, **setiap kombinasi OS/GPU memiliki perintah instalasi uniknya sendiri**, seperti yang dapat dilihat di [Official PyTorch Website](https://pytorch.org/get-started/locally/) (Lihat baris bawah **"Run this Command:"**):

![torch.gif](torch.gif)


### Solution

Untuk mengatasi masalah ini dan memindahkan proyek AI agar berjalan secara lokal dan lintas platform, kita perlu:

1. Abaikan deklarasi generik `torch`, `torchvision`, dan `torchaudio` di dalam `requirements.txt`.
2. Perbarui `install.json` agar menginstal versi Torch yang benar.

#### 1. Update requirements.txt

Pertama, mari kita komentari setiap kemunculan `torch`, `torchvision`, dan `torchaudio`, karena kita akan menulis penginstal khusus untuk ini:

```
diffusers
accelerate
#torch        <= commented out, will be ignored.
transformers
gradio
```

Berikut adalah contoh nyata: https://huggingface.co/spaces/cocktailpeanut/SPRIGHT-T2I/blob/main/requirements.txt

#### 2. Update the install script

Mari kita perbarui `install.js` untuk menambahkan semua kombinasi perintah instalasi Torch yang mungkin:

```javascript
module.exports = {
  "run": [
    // Torch for windows nvidia
    {
      "when": "{{platform === 'win32' && gpu === 'nvidia'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio  --index-url https://download.pytorch.org/whl/cu121"
      }
    },
    // Torch for windows amd
    {
      "when": "{{platform === 'win32' && gpu === 'amd'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch-directml"
      }
    },
    // Torch for windows cpu
    {
      "when": "{{platform === 'win32' && (gpu !== 'nvidia' && gpu !== 'amd')}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio"
      }
    },
    // Torch for mac
    {
      "when": "{{platform === 'darwin'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cpu"
      }
    },
    // Torch for linux nvidia
    {
      "when": "{{platform === 'linux' && gpu === 'nvidia'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio"
      }
    },
    // Torch for linux rocm (amd)
    {
      "when": "{{platform === 'linux' && gpu === 'amd'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/rocm5.7"
      }
    },
    // Torch for linux cpu
    {
      "when": "{{platform === 'linux' && (gpu !== 'amd' && gpu !=='amd')}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu"
      }
    },
    // Install requirements.txt
    {
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install -r requirements.txt"
      }
    }
  ]
}
```

1. Ini akan memeriksa array `run` dan memeriksa klausa `when` dan hanya menjalankan perintah ketika kondisi terpenuhi.
2. Kemudian pada langkah terakhir, itu akan menjalankan `pip install -r requirements.txt`asli


## Install Torch and Xformers

[Xformers](https://github.com/facebookresearch/xformers) adalah pustaka lain yang sering digunakan dalam proyek AI, tetapi hanya untuk CUDA (GPU NVIDIA).

Setiap kali Anda menemukan proyek yang menyertakan `xformers` sebagai dependensi, Anda perlu melakukan hal yang sama seperti yang Anda lakukan untuk `torch`:

1. Komentari baris `xformers` dari `requirements.txt`
2. Tambahkan logika penanganan khusus untuk `xformers` ike dalam skrip instalasi, sehingga hanya diinstal ketika aplikasi berjalan pada GPU `nvidia`.

Misalnya, file `requirements.txt` yang diperbarui mungkin terlihat seperti ini:

```
diffusers
accelerate
#torch        <= commented out, will be ignored.
#xformers     <= commented out, will be ignored.
transformers
gradio
```

Selain itu, kita perbarui skrip instalasi agar menangani `xformers` dengan benar ketika GPU adalah Nvidia:

1. Periksa apakah GPU adalah `nvidia`.
2. Jika ya, tambahkan `xformers` ke perintah `pip install`.

```javascript
module.exports = {
  "run": [
    // Torch for windows nvidia
    {
      "when": "{{platform === 'win32' && gpu === 'nvidia'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio xformers --index-url https://download.pytorch.org/whl/cu121"
      }
    },
    // Torch for windows amd
    {
      "when": "{{platform === 'win32' && gpu === 'amd'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch-directml"
      }
    },
    // Torch for windows cpu
    {
      "when": "{{platform === 'win32' && (gpu !== 'nvidia' && gpu !== 'amd')}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio"
      }
    },
    // Torch for mac
    {
      "when": "{{platform === 'darwin'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cpu"
      }
    },
    // Torch for linux nvidia
    {
      "when": "{{platform === 'linux' && gpu === 'nvidia'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio xformers"
      }
    },
    // Torch for linux rocm (amd)
    {
      "when": "{{platform === 'linux' && gpu === 'amd'}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/rocm5.7"
      }
    },
    // Torch for linux cpu
    {
      "when": "{{platform === 'linux' && (gpu !== 'amd' && gpu !=='amd')}}",
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu"
      }
    },
    // Install requirements.txt
    {
      "method": "shell.run",
      "params": {
        "venv": "env",
        "message": "pip install -r requirements.txt"
      }
    }
  ]
}
```

Baris yang telah diubah hanyalah:

- **Torch untuk windows nvidia:**  `"pip install torch torchvision torchaudio xformers --index-url https://download.pytorch.org/whl/cu121"`
- **Torch untuk linux nvidia:** `"pip install torch torchvision torchaudio xformers"`

## Build an App Launcher Instantly

Skrip Pinokio dapat digunakan untuk melakukan berbagai hal (menjalankan perintah shell, membuat permintaan jaringan, menulis ke file, dll.), tetapi kadang-kadang kita menginginkan cara yang sangat sederhana untuk menghasilkan beberapa skrip secara otomatis untuk menginstal dan menjalankan beberapa aplikasi.

Untuk kasus penggunaan khusus—tetapi sangat sering—ini, kami memiliki program yang disebut [gepeto], yang secara otomatis menghasilkan satu set skrip yang umum digunakan untuk menginstal, menjalankan, dan mengelola aplikasi.

Jika membangun peluncur aplikasi adalah tujuan Anda, kami menyarankan Anda memulai dari penggunaan Gepeto.

---

# File System

<img src="fs.png" class='fixed'>


## Home directory

Pinokio menyimpan semuanya di dalam lokasi terpusat (**Direktori Utama Pinokio**). Ini berarti Anda dapat:

1. Menghapus aplikasi hanya dengan menghapus folder (Tanpa file yang diinstal di seluruh sistem dan DLL yang berantakan)
2. Mencadangkan seluruh ruang kerja atau aplikasi individu hanya dengan mencadangkan folder.


![home.png](home.png)

Saat Anda pertama kali menginstal Pinokio, Anda akan diminta untuk mengatur jalur folder **utama**.

Anda juga dapat memperbaruinya nanti di tab pengaturan.

---

## Self-contained File System

Folder tingkat atas di bawah direktori utama Pinokio terlihat seperti berikut:

> Kami akan menggunakan notasi `/PINOKIO_HOME` untuk merujuk ke direktori utama Pinokio mulai dari titik ini.
>
> Folder `/PINOKIO_HOME` adalah folder apa pun yang Anda atur sebagai rumah Pinokio Anda.

```
/PINOKIO_HOME
  /api
    /stable-diffusion-webui.git
    /comfyui.git
    /brushnet.git
    ...
  /bin
    /miniconda
    /homebrew
    /py
  /drive
    /drives
      /peers
        ...
      /pip
  /cache
  /logs
```



### /api

Folder `api` adalah tempat repositori aplikasi yang diunduh disimpan. Folder API dapat berisi salah satu dari berikut:

1. **Diunduh dari git:** Repositori yang Anda unduh dari git.
2. **Dibuat secara lokal:** Anda dapat secara manual membuat folder dan bekerja dari sana.


### /bin

Folder `bin` menyimpan semua binari yang umum digunakan oleh mesin AI.

- **miniconda:** Untuk lingkungan conda
- **brew:** Untuk menangani Homebrew di Mac
- **python** (dan `pip`)
- **node.js** (dan `npm`)
- dll.

Hal-hal yang diinstal ke folder `/bin` dapat dibagikan di antara beberapa aplikasi di folder `/api`.

### /drive

Folder `drive` menyimpan drive virtual, digunakan untuk mendeduplikasi file yang berlebihan guna menghemat ruang disk, berbagi data di antara beberapa aplikasi, dan secara keseluruhan memisahkan data dari aplikasi untuk banyak skenario yang berguna.

> Pelajari lebih lanjut tentang drive virtual [di sini](#virtual-drive)

### /cache

Folder `cache` menyimpan file cache yang diunduh atau dihasilkan secara terprogram oleh aplikasi (melalui `pip`, `torch`, `huggingface-cli`, dll.)

### /logs

Folder `logs` berisi log, yang penting untuk debugging ketika ada yang tidak berfungsi.

---

## Distributed File URI

Pinokio uses a unique **distributed URI system** that lets you:

- Reference **local files**
- With **universally unique identifiers**

Let's first take a look at the most obvious option--Relative file paths.

### Relative Path

Pinokio menggunakan sistem **URI terdistribusi** yang unik yang memungkinkan Anda:

- Merujuk ke **file lokal**
- Dengan **pengidentifikasi unik secara universal**

Mari kita lihat dulu opsi yang paling jelas—Jalur file relatif.

### Jalur Relatif

URI bisa berupa jalur relatif. Jalur ini diselesaikan relatif terhadap skrip yang sedang berjalan.

Katakanlah kita memiliki folder di `/PINOKIO_HOME/api/myapp`, yang terlihat seperti ini:

```
/myapp
  start.js
  subroutine.json
```

Dan berikut adalah seperti apa `start.js`:

```json
// start.js
module.exports = {
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "subroutine.json"
    }
  }]
}
```

Dalam contoh ini, skrip `start.js` memanggil skrip lain bernama `subroutine.json`. Ini adalah jalur relatif.

Interpreter Pinokio secara otomatis menyelesaikan jalur `subroutine.json` sebagai folder yang sama yang berisi `start.js`, yaitu `/PINOKIO_HOME/api/myapp`.

Jadi panggilan `script.start` akan mencari file `/PINOKIO_HOME/api/myapp/subroutine.json` dan menjalankan skrip tersebut.


### Git Path

Jalur relatif cukup untuk sebagian besar kasus, tetapi bagaimana jika skrip yang ingin Anda jalankan BUKAN dari repositori yang sama? Bagaimana jika Anda ingin mengunduh repositori jarak jauh dan menjalankan beberapa skrip di dalamnya?

Di sinilah skema URI Git masuk.

#### Specification

Tujuan ini dicapai dengan mengadopsi [git url protocol](https://www.git-scm.com/docs/http-protocol#_url_format).


```
<REMOTE_GIT_URI>/<RELATIVE_PATH_WITHIN_THE_REPOSITORY>
```

Misalnya, untuk merujuk file di `install.js` di dalam repositori git https://github.com/cocktailpeanutlabs/comfyui.git jalur HTTP akan terlihat seperti:

https://github.com/cocktailpeanutlabs/comfyui.git/install.js

Beberapa aturan:

1. The `<REMOTE_GIT_URI>` harus diakhiri dengan `.git` (Ini adalah cara standar untuk merujuk ke repositori git)
2. Informasi URL diambil dari file `.git/config` di dalam repositori yang diunduh.
    - Ini berarti repositori lokal tanpa `.git/config` tidak akan memiliki URI yang dapat dialamatkan secara publik. Anda perlu mempublikasikannya di suatu tempat sebelum Anda dapat menggunakan URI git universal.


#### Content Addressable

Selain dapat merujuk nama file, Anda juga dapat merujuk file dalam versi tertentu, seperti:

1. Jalur file dalam hash commit tertentu
2. Jalur file dalam cabang tertentu

```json
// commit hash uri
{
  "method": "script.start",
  "params": {
    "uri": "https://github.com/facefusion/facefusion-pinokio.git/install.js",
    "hash": "ced4e76aa2a7c60a08535af8c340efea153ec381"
  }
}

// git branch uri
{
  "method": "script.start",
  "params": {
    "uri": "https://github.com/facefusion/facefusion-pinokio.git/install.js",
    "branch": "master"
  }
}
```

Skrip di atas akan:

1. Memeriksa apakah repositori diinstal secara lokal
2. Jika tidak, `git clone` repositori `https://github.com/facefusion/facefusion-pinokio.git`
3. Beralih ke **commit hash** (`ced4e76aa2a7c60a08535af8c340efea153ec381`) atau **branch** (`master`)
4. Menyelesaikan jalur file yang diunduh secara lokal `install.js` dari repositori git yang diunduh secara otomatis
5. Dan menjalankannya

---

## Virtual Drive

### Introduction

Drive virtual memungkinkan Anda menyimpan data di luar aplikasi sambil membuatnya berperilaku seolah-olah berada di dalam, dengan memanfaatkan tautan simbolik.

![virtualdrive.png](virtualdrive.png)

Ini berguna untuk berbagai kasus seperti:

1. Menyimpan file yang tetap ada di beberapa instalasi (Mirip dengan Volume Docker)
2. Berbagi file di antara beberapa aplikasi (misalnya, ComfyUI, Fooocus, dan Stable-Diffusion-WebUI berbagi file model AI `.safetensor` di antara mereka sehingga Anda tidak perlu mengunduh file yang berlebihan untuk setiap aplikasi)
3. Menyimpan semua file pustaka (seperti PyTorch) secara deduplikasi, yang menghemat banyak ruang disk.

### Use Cases

1. **Persistence:** Karena Drive ada secara independen, mereka tetap ada bahkan jika Anda menghapus aplikasi atau memperbaruinya. Jika Anda ingin menyimpan file model AI besar untuk beberapa aplikasi, dan ingin model tersebut tetap ada bahkan ketika Anda menghapus atau memperbarui aplikasi, ini sangat berguna.
2. **Shareable:** Drive virtual juga dapat menentukan peers, yang memungkinkan beberapa aplikasi berbagi satu drive virtual. Ketika Anda menentukan array `peer` , API `fs.link` akan mencari drive peer yang sudah ada sebelum membuat drive khusus baru. Jika drive peer ada, `fs.link` akan hanya menautkan ke jalur drive yang ditemukan alih-alih membuat yang baru.
3. **Save Disk Space:** Tujuan utama dari drive virtual adalah untuk menghindari duplikat file sebanyak mungkin, yang **secara signifikan menghemat ruang disk**. Dalam banyak kasus, ini dapat menghemat puluhan gigabyte **per application**.

### How it works

#### 1. Symbolic Link

Drive virtual diimplementasikan secara internal dengan [symbolic links](https://en.wikipedia.org/wiki/Symbolic_link#:~:text=In%20computing%2C%20a%20symbolic%20link,FreeBSD%2C%20Linux%2C%20and%20macOS.) di Linux/Mac, dan [junctions](https://learn.microsoft.com/en-us/sysinternals/downloads/junction) di Windows.

Ketika Anda membuat satu set drive virtual menggunakan API `fs.link` , berikut adalah yang terjadi:

1. Buat satu set folder drive virtual di bawah folder `/PINOKIO_HOME/drive`.
2. Buat tautan simbolik dari folder aplikasi yang ditentukan ke folder drive virtual yang baru dibuat (yang ada DI LUAR repositori aplikasi)
3. Berkat tautan simbolik, ketika Anda merujuk salah satu folder aplikasi yang menautkan ke drive virtual, itu akan berperilaku seolah-olah file benar-benar berada di dalam jalur folder aplikasi yang ditentukan, tetapi pada kenyataannya file disimpan di folder "drive virtual" eksternal.
4. Ketika Anda menghapus repositori aplikasi, file yang Anda simpan menggunakan drive virtual akan tetap ada, karena drive virtual ada di luar repositori aplikasi. Hanya tautan yang dihapus.


#### 2. Programmable

Biasanya membuat tautan simbolik adalah proses yang membosankan yang harus dilakukan orang secara manual, karena lingkungan sistem setiap orang berbeda.

Namun berkat arsitektur sistem file [self-contained](#self-contained-file-system) dan [distributed](#distributed-file-uri) pinokio, dimungkinkan untuk menulis skrip yang akan secara deterministik mengotomatiskan pembuatan tautan simbolik terlepas dari seperti apa lingkungan sistem global pengguna.

> Pelajari lebih lanjut tentang API `fs.link` [here](#fslink).

#### 3. It "just" works.

Abstraksi drive virtual menyatu dengan mulus ke dalam aplikasi apa pun yang sudah Anda miliki, dan aplikasi TIDAK perlu ditulis dengan cara khusus untuk memfasilitasi drive virtual.

Aplikasi bekerja PERSIS sama seperti ketika mereka tidak menggunakan drive virtual, **tanpa harus mengubah kode apa pun**. Bahkan Anda dapat mengaktifkan dan menonaktifkan fitur drive virtual dengan sangat mudah, hanya dengan menyertakan atau mengecualikan satu panggilan API `fs.link`.


**Example**: Katakanlah sebuah aplikasi di jalur `/PINOKIO_HOM/api/sd` memiliki potongan kode yang mengatakan `open("models/checkpoint.pt")`

- **Tanpa drive virtual:** Ini akan membuka file di `/PINOKIO_HOME/api/sd/models/checkpoint.pt` di dalam repositori saat ini.
- **Dengan drive virtual:** Katakanlah kita telah membuat tautan dari `/PINOKIO_HOME/api/sd/models` ke jalur drive virtual `models` untuk repositori ini.
  - Ini akan mencoba membuka file di `/PINOKIO_HOME/api/sd/models/checkpoint.pt`
  - Folder `/PINOKIO_HOME/api/sd/models` itu sendiri bukan folder aktual dengan konten, melainkan tautan simbolik ke drive virtual yang dibuat secara eksternal.
  - Tetapi perbedaan ini tidak mengubah apa pun, upaya untuk membuka `/PINOKIO_HOME/api/sd/models/checkpoint.pt` akan secara otomatis dialihkan untuk membuka `models/checkpoint.pt` di drive virtual.

Pada dasarnya, semuanya bekerja persis sama seperti ketika Anda tidak membuat tautan drive virtual, tetapi kita tetap mendapatkan semua manfaat yang datang dengan drive virtual.

> Pelajari lebih lanjut tentang API `fs.link` [here](#fslink).



---

# Processor

<img src="cpu.png" class='fixed'>

Prosesor adalah CPU dari Pinokio. Ini mengikuti skema yang sama seperti yang diterapkan oleh semua CPU modern ([fetch-decode-execute cycle](https://en.wikipedia.org/wiki/Instruction_cycle#Summary_of_stages))

1. **[Fetch (Loader)](fetch):** Mesin pemuat menginstansiasi mesin status (termasuk memori serta `self`, yang merujuk ke kode itu sendiri)
2. **[Decode (Template)](decode):** Mesin templat mengambil ekspresi templat dan menginstansiasinya menggunakan keadaan saat ini yang disediakan oleh pemuat
3. **[Execute (Runner)](execute):** Pelaksana mengambil permintaan yang telah diinstansiasi dan mengeksekusinya.

## Fetch

Langkah "Fetch" menyelesaikan skrip yang diinstal secara lokal dan memuatnya ke memori.

![fetch.png](fetch.png)

### Resolve Script

Langkah pertama adalah menyelesaikan URI skrip. Ini melibatkan:

1. Memeriksa apakah URI git HTTP yang ditentukan sudah diinstal secara lokal.
2. Jika sudah diinstal, menyelesaikan jalur lokal, sehingga kita dapat mengakses file yang sebenarnya.

#### Syntax

```json
{
  "uri": <script_uri>
}
```

- `<script_uri>`: dapat berupa salah satu dari dua bentuk berikut:
  - **Absolute Path:** Jalur file absolut penuh ke file skrip yang akan dijalankan
    - Example: `C:\\pinokio\\api\\my_app\\install.json`
  - **Pinokio File System Path:** Jalur sistem file Pinokio. Alih-alih menentukan jalur file penuh, dimulai dengan `~/api`.
    - Example: `~/api/my_app/install.json`
  - **Git Path:** Skema URI terdistribusi seperti yang dijelaskan [here](#git-path). Digunakan untuk merujuk ke repositori jarak jauh yang diunduh secara lokal.
    - Example: `https://github.com/cocktailpeanut/blogger.git/index.json`

#### Example

```json
{
  "uri": "https://github.com/cocktailpeanut/blogger.git/index.json"
}
```

Berikut adalah bagaimana permintaan di atas diselesaikan menjadi file lokal:

1. Pertama cari repositori yang diunduh secara lokal di bawah `/PINOKIO_HOME/api` yang sesuai dengan git remote `https://github.com/cocktailpeanut/blogger.git`
2. Katakanlah kita memiliki repositori yang diunduh secara lokal di `/PINOKIO_HOME/api/blogger.git`. Maka skrip menyelesaikan file lokal di `/PINOKIO_HOME/api/blogger.git/index.json`.
3. Jika tidak ditemukan, itu akan memunculkan kesalahan.

> **Note**
>
> Pinokio TIDAK membuat permintaan jaringan ke jalur https.
>
> Sebaliknya, URI https hanya digunakan untuk menyelesaikan jalur lokal untuk repositori yang sudah diunduh.

#### Usage

Dalam praktiknya, sebagian besar pengguna Pinokio TIDAK akan langsung membuat permintaan panggilan "uri" secara terprogram.

Sebaliknya, skrip dapat dipicu melalui antarmuka pengguna.


### Load Script

Tahap pemuatan mengambil file skrip yang telah diselesaikan, dan benar-benar memuatnya ke memori, sehingga mesin Pinokio dapat menjalankan skrip untuk mengeksekusi perintah.

#### Script written in JSON

##### Syntax


Sebuah **script** adalah file JSON (atau JavaScript yang mengembalikan JSON) yang mengikuti sintaks berikut:

```json
{
  "daemon": <daemon>,
  "run": <rpc_requests>,
  <key>: <val>,
  <key>: <val>,
  ...
}
```

- `<rpc_requests>`: Array dari panggilan RPC yang ditulis dalam JSON
- `<deamon>`: (opsional) Jika diatur ke `true`, proses skrip TIDAK akan berhenti setelah semua permintaan RPC dalam array `<rpc_requests>` selesai dijalankan.
- `<key>`: (opsional) Selain atribut yang dipesan `daemon` dan `run`, Anda dapat menambahkan pasangan kunci/nilai khusus Anda sendiri. Pasangan kunci/nilai khusus ini dapat diakses di dalam templat sebagai variabel bernama [self](#self).
- `<val>`: (opsional) Nilai yang terkait dengan `<key>`

##### Example

Berikut adalah contoh skrip yang mengkloning repositori dan menginstal beberapa paket.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "git clone https://huggingface.co/spaces/cocktailpeanut/BRIA-RMBG-1.4 app"
    }
  }, {
    "method": "shell.run",
    "params": {
      "venv": "env",
      "path": "app",
      "message": "pip install -r requirements.txt"
    }
  }]
}
```

Dalam contoh ini, array `run` membuat 2 panggilan RPC [shell.run](#shellrun):

1. **git clone:** Menjalankan `git clone https://huggingface.co/spaces/cocktailpeanut/BRIA-RMBG-1.4 app` untuk mengkloning repositori jarak jauh ke folder `app`.
2. **install dependencies:**
    - Menjalankan `pip install -r requirements.txt`
    - Dari folder `app` (yang baru saja diunduh dari langkah sebelumnya)
    - Untuk menginstal dependensi ke lingkungan venv di jalur `env`


#### Script written in JavaScript

Anda juga dapat menulis file JavaScript untuk mengimplementasikan `script`.

Cukup tulis modul fungsi async node.js yang mengembalikan [a JSON script](#script-written-in-json):

##### Syntax

```javascript
module.exports = async (kernel) => {
  return <JSON_RUN_SCRIPT>
}
```


##### Example

```javascript
module.exports = async (kernel) => {
  return {
    "run": [
      {
        "method": "shell.run",
        "params": {
          "message": "git clone https://huggingface.co/spaces/cocktailpeanut/BRIA-RMBG-1.4 app"
        }
      },
      {
        "method": "shell.run",
        "params": {
          "venv": "env",
          "path": "app",
          "message": "pip install -r requirements.txt"
        }
      },
      (kernel.gpu === 'nvidia' ? "pip install xformers" : null)
    ]
  }
}
```

Ini berguna ketika Anda ingin secara dinamis menghasilkan skrip berdasarkan status `kernel`. 

1. Perhatikan bahwa ini adalah modul node.js.
2. Ini adalah **async function**yang mengambil variabel `kernel` yang memungkinkan Anda mengakses semua utilitas dan informasi sistem.
3. **async function** mengembalikan JSON yang mengikuti sintaks skrip Pinokio.

Perhatikan bahwa langkah terakhir dalam array **run** mengembalikan `pip install xformers` atau `null` tergantung pada variabel `kernel.gpu`:

```javascript
(kernel.gpu === 'nvidia' ? "pip install xformers" : null)
```

Ini akan memanfaatkan variabel `kernel.gpu` untuk mendeteksi GPU, dan hanya menjalankan `pip install xformers` jika GPU adalah Nvidia.

Jika tidak, itu mengembalikan `null`, yang akan diabaikan (dilewati) pada [execution stage](#execute).


---

## Decode

![decode.png](decode.png)

Skrip Pinokio tipikal mengandung ekspresi templat.

Tanpa ekspresi templat, Anda hanya akan dapat menjalankan perintah statis. Yang kita inginkan adalah dapat membentuk permintaan secara dinamis dengan cepat, sehingga setiap eksekusi dapat menjalankan alur kerja permintaan yang unik berdasarkan status saat ini dari mesin status Pinokio.

### Template Interpreter

Ekspresi templat Pinokio adalah string yang dikelilingi oleh <span v-pre>{{ }}</span>, dan diisi secara langsung saat perintah dijalankan. Contoh:

```json
{
  "method": "local.set",
  "params": {
    "name": "{{input}}"
  }
}
```

Jadi, apa yang bisa masuk ke dalam ekspresi <span v-pre>{{ }}</span>?

1. **Any JavaScript evaluation expression:**Disarankan untuk hanya menggunakan ekspresi sederhana, tetapi ekspresi apa pun yang dapat Anda jalankan di node.js dapat disertakan. Misalnya: <span v-pre>{{Buffer.from(input.images[0], "base64")}}</span>
2. **Memory variables:** Pinokio mengekspos variabel tertentu dari memori sehingga Anda dapat secara dinamis menjalankan perintah berdasarkan variabel memori ini.

Bagian berikutnya mencantumkan semua **variabel memori** yang tersedia untuk digunakan di dalam ekspresi templat skrip.

### Memory Variables

Jadi, jenis variabel apa yang tersedia di dalam ekspresi templat?

Pinokio mengekspos beberapa **variabel memori** isistem di dalam templat. Memanfaatkan variabel-variabel ini sangat penting untuk menulis skrip yang dinamis (dan berbasis status).

> Anda dapat mempelajari lebih lanjut tentang variabel memori di bagian [memory](#memory) section.

### Decode Cycle

Ekspresi templat diinstansiasi secara baru di awal setiap langkah dalam array `run` menggunakan variabel memori yang diperbarui yang tersedia pada saat parsing.

Misalnya, katakanlah kita memiliki skrip pencatatan:

```json
{
  "run": [{
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}"
    }
  }]
}
```

Karena variabel [current](#current) mengembalikan indeks langkah yang sedang dijalankan dalam array `run`,

1. Pertama akan menjalankan langkah `run[0]` dan mencetak `running instruction 0`
2. Kemudian akan menjalankan langkah berikutnya `run[1]`, and print `running instruction 1`
3. Terakhir akan menjalankan langkah terakhir `run[2]`, and print `running instruction 2`


---


## Execute

![execute.png](execute.png)

Setelah permintaan telah diinstansiasi oleh dekoder, permintaan tersebut dieksekusi.

### Script Lifecycle

Siklus hidup skrip sangat sederhana:

```json
{
  "run": [
    <RPC>,
    <RPC>,
    <RPC>,
    <RPC>,
    <RPC>,
    ...
  ]
}
```

1. Array `run` adalah daftar berurutan dari panggilan RPC.
2. Pinokio menelusuri array `run` untuk menjalankan langkah-langkah satu per satu.
3. Setiap `<RPC>` [didekode secara baru](#decode-cycle) dengan [penerjemah templat](#template-interpreter) sebelum dieksekusi.
4. Setelah setiap langkah, nilai kembalian dari setiap langkah diteruskan ke langkah berikutnya dalam bentuk [input](#input).
5. Setiap langkah dapat memanfaatkan variabel `input` yang diteruskan dari langkah sebelumnya dalam ekspresi templat mereka untuk secara dinamis membangun metode yang akan dijalankan.
6. Ketika mencapai akhir array `run` , skrip berhenti, dan semua proses yang terkait dengan skrip dikumpulkan sebagai sampah.

![run.png](run.png)


### RPC

API RPC (Remote Procedure Call) memungkinkan Anda benar-benar menulis berbagai logika untuk membuat Pinokio melakukan sesuatu.


#### syntax

```json
{
  "id": <RPC_id>,
  "when": <RPC_condition>,
  "method": <RPC_method>,
  "params": <RPC_params>,
}
```

1. `<RPC_id>`: **optional.** Tandai panggilan RPC ini dengan id `<RPC_id>`. Panggilan RPC `jump` dapat melompat ke langkah apa pun dalam array `run`.
2. `<RPC_condition>`: **optional.** Jika dievaluasi ke `true`, jalankan langkah ini. Jika tidak, lanjutkan ke langkah berikutnya.
3. `<RPC_method>`: Metode RPC yang akan dipanggil
4. `<RPC_params>`: Parameter JSON untuk diteruskan ke `<RPC_method>` sebagai muatan. Objek <RPC_params> akan tersedia sebagai nilai ekspresi templat {{input}} pada langkah berikutnya.

> Untuk mempelajari semua API RPC yang tersedia, lihat bagian [script](#script).

#### examples

##### id


```json
{
  "run": [{
    "method": "jump",
    "params": {
      "id": "{{gpu === 'nvidia' ? 'cuda' : 'cpu'}}"
    }
  }, {
    "id": "cpu",
    "method": "shell.run",
    "params": {
      "message": "pip install torch torchvision torchaudio"
    }
  }, {
    "id": "cuda",
    "method": "shell.run",
    "params": {
      "message": "pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121"
    }
  }]
}
```

Ketika skrip mulai berjalan, ia menemui instruksi `jump` yang secara dinamis melompat ke **cuda** (`run[2]`) atau **cpu** (`run[1]`) tergantung pada GPU.

##### when


```json
{
  "run": [{
    "when": "{{gpu !== 'nvidia'}}",
    "method": "shell.run",
    "params": {
      "message": "pip install torch torchvision torchaudio"
    }
  }, {
    "when": "{{gpu === 'nvidia'}}",
    "method": "shell.run",
    "params": {
      "message": "pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121"
    }
  }]
}
```

- `run[0]` dijalankan jika GPU BUKAN Nvidia. (Di mesin GPU Nvidia, langkah ini diabaikan dan langsung ke langkah berikutnya)
- `run[1]` dijalankan jika GPU adalah Nvidia.

### Daemon mode

Secara default, ketika Pinokio selesai menjalankan semua langkah di dalam array `run` , setiap proses yang terkait dengan skrip berhenti, dan apa pun yang ada di memori segera dibersihkan (Lihat [script lifecycle](#script-lifecycle)).

Namun, kadang-kadang Anda mungkin ingin **menjaga semua proses tetap berjalan** bahkan setelah interpreter Pinokio selesai mengeksekusi setiap langkah dalam array `run`.

Misalnya **bayangkan meluncurkan server web menggunakan skrip Pinokio:**

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "python server.py"
    }
  }]
}
```

`python server.py` mungkin meluncurkan server, tetapi ketika skrip selesai berjalan, semua yang terkait dengan skrip akan dimatikan secara otomatis, termasuk server.

Untuk menjaga proses server tetap berjalan, kita hanya perlu menentukan atribut tambahan: `daemon`:

```json
{
  "daemon": true,
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "python server.py"
    }
  }]
}
```

Dengan mengatur `daemon` ke `true`, Pinokio tidak akan secara otomatis mematikan semua proses yang terkait, yang berarti server akan tetap berjalan.

Satu-satunya cara untuk menghentikan server dalam kasus ini adalah dengan secara eksplisit menghentikan skrip menggunakan API [script.stop](#scriptstop) , atau melalui antarmuka tombol berhenti Pinokio.


---

# Memory

Saat skrip Pinokio dieksekusi langkah demi langkah, Anda dapat memperbarui memori sehingga dapat digunakan pada langkah-langkah berikutnya.

<img src="ram.png" class='fixed'>

## input

Sebuah `input` adalah variabel yang diteruskan dari satu panggilan RPC ke panggilan berikutnya. Tidak semua API RPC memiliki nilai kembalian, tetapi yang memiliki akan meneruskan nilai `input` ke langkah berikutnya.

![run.png](run.png)

Ada dua jenis `input`:

1. **Return values between steps:** Nilai `input` yang diteruskan ke langkah-langkah `run[1]`, ... `run[run.length-1]`. Pada dasarnya, ini adalah nilai yang diteruskan dari satu langkah ke langkah berikutnya. `run[0]` tidak dapat memiliki ini karena tidak ada langkah sebelumnya untuk `run[0]`.
2. **Initial script launch parameter:** Nilai `input` yang diteruskan ke `run[0]`.
    - Secara default, nilai ini akan menjadi `null` untuk `run[0]` karena tidak ada "langkah sebelumnya".
    - Namun, dimungkinkan untuk meneruskan nilai `input` khusus ke langkah pertama `run[0]`
      - **script.start params:** Anda dapat meluncurkan skrip secara terprogram menggunakan API [script.start](#scriptstart). Dan saat Anda memanggil metode tersebut, Anda dapat meneruskan parameter tambahan `params`. Ini akan diteruskan ke langkah pertama `run[0]` sebagai `input`.
      - **pinokio.js menu item params:** Anda dapat membangun UI item menu di [pinokio.js](#pinokiojs) dengan atribut array bernama `menu`, di mana setiap item dapat berisi atribut `href`, yang akan membuat item menu yang meluncurkan skrip di URI yang ditentukan. Anda juga dapat meneruskan objek `params` tambahan bersama dengan `href`, dan objek `params` ini akan diteruskan ke langkah pertama `run[0]` dari skrip sebagai `input` saat diluncurkan melalui item menu.

Mari kita lihat contohnya:

```json
{
  "run": [{
    "id": "run",
    "method": "gradio.predict",
    "params": {
      "uri": "http://127.0.0.1:7860",
      "path": "/answer_question_1",
      "params": [
        { "path": "https://media.timeout.com/images/105795964/750/422/image.jpg" },
        "Explain what is going on here"
      ]
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{input.data[0]}}"
    }
  }]
}
```

Dalam contoh di atas, kita:

1. Membuat permintaan ke http://127.0.0.1:7860 menggunakan API [gradio.predict](#gradiopredict) API.
2. Nilai kembalian dari [gradio.predict](#gradiopredict) diteruskan ke langkah berikutnya `log`.
3. `log` mengambil `input` dan menginstansiasi templat {{input.data[0]}} serta mencatat hasilnya ke terminal.


---

## args

args setara dengan `input` dari langkah pertama (`run[0]`).

Kadang-kadang Anda mungkin ingin meneruskan beberapa parameter saat meluncurkan skrip, dan memanfaatkan objek parameter tersebut di seluruh skrip.

Anda tidak dapat melakukan ini dengan [input](#input) karena variabel input diatur ulang untuk setiap langkah.

Mari kita lihat contohnya (file bernama `launch.json`):


```json
{
  "run": [{
    "method": "log",
    "params": {
      "json2": "{{input}}"
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{args}}"
    }
  }]
}
```

Kita dapat meluncurkan skrip ini dengan panggilan API [script.start](#scriptstart) berikut:

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "launch.json",
      "params": {
        "a": 1,
        "b": 2
      }
    }
  }]
}
```

Ini akan mencetak:

```
{"a": 1, "b": 2}
{"a": 1, "b": 2}
```

1. Baris pertama berasal dari langkah pertama, menggunakan nilai `input` yang tersedia di `run[0]`.
2. Baris kedua berasal dari langkah kedua, menggunakan nilai `args` Perhatikan bahwa nilai `input` dan `args` akan selalu sama untuk `run[0]`.



---

## local

Variabel lokal adalah setiap variabel yang diawali dengan `local.`Misalnya:

- `local.items`
- `local.prompt`


Variabel lokal diatur ulang setiap kali skrip selesai dijalankan, yang berarti jika Anda menjalankan skrip sekali, dan menjalankannya lagi, mereka akan selalu mulai dari nol.

Anda dapat mengatur nilai variabel lokal dengan API [local.set](#localset).

---

## self

`self` merujuk pada skrip itu sendiri.

Skrip `run` terlihat seperti ini:

```json
{
  "daemon": <daemon>,
  "run": <rpc_requests>,
  <key>: <val>,
  <key>: <val>,
  ...
}
```

Where:

- `<rpc_requests>`: Array dari panggilan RPC yang ditulis dalam JSON
- `<deamon>`: (opsional) Jika diatur ke `true`, , proses skrip TIDAK akan berhenti setelah semua permintaan RPC dalam array `<rpc_requests>` selesai dijalankan.
- `<key>`:(opsional) Selain atribut yang dipesan `daemon` and `run`, Anda dapat menambahkan pasangan kunci/nilai khusus Anda sendiri
- `<val>`: (opsional) Nilai yang terkait dengan `<key>`

Perhatikan bahwa Anda dapat memiliki pasangan <key>/<value> khusus apa pun dalam skrip.

Dan ketika Anda melakukannya, Anda dapat mengaksesnya menggunakan notasi `self`.

Bayangkan kita memiliki skrip berikut:

```json
{
  "cmds": {
    "win32": "dir",
    "darwin": "ls",
    "linux": "ls"
  },
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "{{self.cmds[platform]}}"
    }
  }]
}
```

Di sini, `self.cmds[platform]` akan diselesaikan menjadi:

- `dir` di Windows
- `ls`di Mac (darwin)
- `ls` di Linux

---

## uri

URI skrip saat ini

---

## cwd

Jalur dari skrip yang sedang berjalan saat ini

---

## platform

Sistem operasi saat ini. Dapat berupa salah satu dari berikut:

- `darwin`
- `linux`
- `win32`

---

## arch

Arsitektur sistem saat ini. Dapat berupa salah satu dari berikut:

- `x32`
- `x64`
- `arm`
- `arm64`
- `s390`
- `s390x`
- `mipsel`
- `ia32`
- `mips`
- `ppc`
- `ppc64`

---

## gpus

Array dari GPU yang tersedia di mesin

Example:

```json
["apple"]
```

---

## gpu

GPU pertama yang tersedia

Example:

```json
apple
```

---

## current

Variabel `current` menunjuk ke indeks dari instruksi yang sedang dieksekusi dalam array `run` Misalnya:

```json
{
  "run": [{
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}"
    }
  }]
}
```

will print:

```
running instruction 0
running instruction 1
running instruction 2
```

---

## next

Variabel `next` menunjuk ke indeks dari instruksi berikutnya yang akan dieksekusi. (`null` jika instruksi saat ini adalah instruksi terakhir dalam array `run`):

```json
{
  "run": [{
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}. next instruction is {{next}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}. next instruction is {{next}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "running instruction {{current}}. next instruction is {{next}}"
    }
  }]
}
```

Perintah di atas akan mencetak berikut:

```
running instruction 0. next instruction is 1
running instruction 1. next instruction is 2
running instruction 2. next instruction is null
```

---

## envs

Anda dapat mengakses variabel lingkungan dari proses yang sedang berjalan saat ini dengan `envs`.

Misalnya, katakanlah kita telah mengatur variabel lingkungan `SD_INSTALL_CHECKPOINT` dan `MODEL_PATH` untuk aplikasi. Kita dapat mengambilnya saat mengeksekusi skrip, seperti ini:

```json
{
  "run": [{
    "method": "fs.download",
    "params": {
      "uri": "{{envs.SD_INSTALL_CHECKPOINT}}",
      "dir": "{{envs.MODEL_PATH}}"
    }
  }]
}
```

Selain itu, kita bahkan dapat menggunakan variabel lingkungan di dalam `when`, , secara efektif menentukan apakah akan menjalankan tindakan atau tidak berdasarkan variabel lingkungan.

Misalnya, kita mungkin HANYA ingin mengunduh file jika variabel lingkungan diatur:



```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui app",
    }
  }, {
    "when": "{{envs.SD_INSTALL_CHECKPOINT}}",
    "method": "fs.download",
    "params": {
      "uri": "{{envs.SD_INSTALL_CHECKPOINT}}",
      "dir": "{{envs.MODEL_PATH}}"
    }
  }]
}
```

Dalam skrip di atas,

1. Jika variabel lingkungan `SD_INSTALL_CHECKPOINT` diatur (melalui [ENVIRONMENT](#ENVIRONMENT), atau melalui cara lain), tindakan `fs.download` akan dieksekusi dengan benar.
2. jika `SD_INSTALL_CHECKPOINT` TIDAK diatur, maka langkah kedua akan dilewati dan skrip akan selesai segera setelah langkah pertama.

---

## kernel

API JavaScript kernel

- `kernel.exists()`: memeriksa apakah jalur ada
- `kernel.script.running()`: memeriksa apakah skrip di jalur yang ditentukan sedang berjalan
- `kernel.script.local()`: mendapatkan variabel lokal dari skrip (jika sedang berjalan)

### kernel.exists

Memeriksa apakah file atau folder di jalur yang ditentukan ada:

#### syntax

```
kernel.exists(...pathChunks)
```

- `pathChunks`: sejumlah potongan jalur.
  - Potongan akan digabungkan untuk menyelesaikan jalur penuh (Secara internal menggunakan `path.resolve(...pathChunks)`dari node.js)
  - Potongan harus menyelesaikan ke jalur absolut saat digabungkan.

#### examples

##### inside a script

```json
{
  "run": [{
    "when": "{{!kernel.exists(cwd, 'env')}}",
    "method": "script.start",
    "params": {
      "uri": "install.js"
    }
  }]
}
```

Ketika penerjemah templat menemui `kernel.exists`, , ia menggabungkan semua potongan yang diberikan untuk membangun jalur penuh.

1. Pertama menyelesaikan jalur menggunakan variabel [cwd](#cwd) dan string `"env"`,yang akan menyelesaikan ke folder `env` di direktori saat ini.
2. Kemudian memeriksa apakah jalur tersebut ada.
3. Jika ada, mengembalikan `true`, jika tidak mengembalikan `false`

##### inside pinokio.js

Juga dimungkinkan untuk menggunakan metode `kernel.exists()` di dalam `pinokio.js` untuk secara dinamis membangun UI.

> Bilah sisi UI diperbarui untuk setiap langkah dalam eksekusi array run.

```json
module.exports = {
  version: "1.5",
  title: "My App",
  description: "Add description here",
  icon: "icon.png",
  menu: async (kernel) => {
    // we pass 3 chunks: __dirname, "app", and "env" ==> the chunks will be joined to construct the absolute path, and will be checked to see if the path exists.
    let installed = await kernel.exists(__dirname, "app", "env")
    if (installed) {
      // Already installed, display "start" button
      return [{
        icon: "fa-solid fa-plug",
        text: "Start",
        href: "start.js",
      }]
    } else {
      // Not installed, display "install" button
      return [{
        icon: "fa-solid fa-plug",
        text: "Install",
        href: "install.js",
      }]
    }
  }
}
```


### kernel.script.local

Mendapatkan variabel lokal dari jalur skrip yang ditentukan

#### syntax

```
kernel.script.local(...pathChunks)
```

#### example

##### using relative path

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "start.js"
    }
  }, {
    "method": "log",
    "params": {
      "text": "{{kernel.script.local(cwd, 'start.js').url}}"
    }
  }]
}
```

1. Pertama jalankan `install.js` menggunakan API `script.start`
2. Kemudian pada langkah berikutnya (panggilan API`log`), kita memeriksa `{{kernel.script.local(cwd, 'start.js')}}`
3. Jika `start.js` sedang berjalan, itu akan mengembalikan JSON yang berisi semua variabelnya sebagai pasangan kunci/nilai. Jika tidak, itu akan mengembalikan JSON kosong {}
4. Dalam kasus ini, kita mengasumsikan ada variabel lokal bernama `url`,dan dapat mendapatkan nilainya dengan `kernel.script.local(cwd, 'start.js').url` 

##### using git path


```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "https://github.com/cocktailpeanutlabs/moondream2.git/start.js"
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{kernel.script.local('https://github.com/cocktailpeanutlabs/moondream2.git/start.js')}}"
    }
  }]
}
```

1. Jika `https://github.com/cocktailpeanutlabs/moondream2.git/start.js` sedang berjalan **mengembalikan semua variabel lokal untuk skript**
2. Jika TIDAK berjalan: mengembalikan objek kosong `{}`

##### inside pinokio.js


```json
module.exports = {
  version: "1.5",
  title: "My App",
  description: "Add description here",
  icon: "icon.png",
  menu: async (kernel) => {

    // Step 1.
    // Get the `local.url` variable inside the script "start.js"
    let url = kernel.local(__dirname, "app", "start.js").url

    // Step 2.
    // If there's a local variable "url", display the "web UI" tab,
    // which links to the url => when clicked, this will open the url
    if (url) {
      return [{
        icon: "fa-solid fa-plug",
        text: "Web UI",
        href: url,
      }]
    }
    // Step 3.
    // if there is no local variable "url",
    // it means the url inside the "start.js" script is not yet ready.
    // so do NOT display the tab to open the url.
    else {
      return [{
        icon: "fa-solid fa-plug",
        text: "Start",
        href: "start.js",
      }]
    }
  }
}
```


### kernel.script.running

#### syntax

```
kernel.script.running(...pathChunks)
```

#### examples

##### 

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "install.js"
    }
  }, {
    "method": "log",
    "params": {
      "text": "{{kernel.script.running(cwd, 'install.js')}}"
    }
  }]
}
```

1. Pertama akan memulai skrip `install.js` menggunakan API `script.start`.
2. Kemudian pada langkah kedua, memeriksa apakah skrip `install.js` sedang berjalan. Dalam kasus ini kita harus meneruskan baik `cwd` (direktori saat ini) maupun `install.js` sehingga mereka dapat digabungkan untuk menghasilkan jalur absolut.

##### inside pinokio.js


```json
module.exports = {
  version: "1.5",
  title: "My App",
  description: "Add description here",
  icon: "icon.png",
  menu: async (kernel) => {

    // Step 1.
    // Get the `local.url` variable inside the script "start.js"
    let url = kernel.local(__dirname, "app", "start.js").url

    // Step 2.
    // If there's a local variable "url", display the "web UI" tab,
    // which links to the url => when clicked, this will open the url
    if (url) {
      return [{
        icon: "fa-solid fa-plug",
        text: "Web UI",
        href: url,
      }]
    }
    // Step 3.
    // if there is no local variable "url",
    // it means the url inside the "start.js" script is not yet ready.
    // so do NOT display the tab to open the url.
    else {
      return [{
        icon: "fa-solid fa-plug",
        text: "Start",
        href: "start.js",
      }]
    }
  }
}
```

---


## _

`_` adalah variabel utilitas yang memungkinkan Anda dengan mudah memanipulasi data di dalam ekspresi templat, didukung oleh [lodash](https://lodash.com/).

Example:

```json
{
  "run": [{
    "method": "log",
    "params": {
      "raw": "{{_.difference([2, 1], [2, 3])}}"
    }
  }]
}
```

will print:

```
1
```

Contoh lain, di mana kita menggunakan metode `_.sample()` untuk memilih item secara acak dari variabel `self.friends`:

```json
{
  "friends": [
    "HAL 9000",
    "Deep Blue",
    "Watson",
    "AlphaGo",
    "Siri",
    "Cortana",
    "Alexa",
    "Google Assistant",
    "OpenAI",
    "Tesla Autopilot",
    "IBM Watson",
    "Boston Dynamics",
    "IBM Deep Blue",
    "Microsoft Tay",
    "IBM DeepMind",
    "Amazon Rekognition",
    "OpenAI GPT-3"
  ],
  "run": [{
    "method": "log",
    "params": {
      "raw": "random friend: {{_.sample(self.friends)}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "random friend: {{_.sample(self.friends)}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "random friend: {{_.sample(self.friends)}}"
    }
  }]
}
```

Skrip di atas mencetak item yang dipilih secara acak, misalnya:

```
random friend: IBM DeepMind
random friend: HAL 9000
random friend: Amazon Rekognition
```

---

## os

Pinokio mengekspos [node.js os module](https://nodejs.org/api/os.html) melalui variabel `os`.

Misalnya, kita dapat menggunakan variabel `os` untuk secara dinamis mengetahui platform tempat skrip berjalan dan mungkin membentuk perintah berdasarkan platform tersebut. Contoh:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "{{os.platform() === 'win32' ? 'dir' : 'ls'}}"
    }
  }]
}
```

Skrip di atas:

1. Menjalankan `dir` di Windows
2. Menjalankan `ls` di sistem operasi non-Windows (Mac, Linux)

---

## path

The [Node.js path module](https://nodejs.org/api/path.html)

### examples

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "cd {{path.resolve(cwd, 'env')}}"
    }
  }]
}
```



---

# Script 

<img src="keyboard.png" class='fixed'>

Skrip Pinokio adalah markup deklaratif yang dapat menjalankan perintah shell, bekerja dengan file, membuat permintaan jaringan, dan hampir segala sesuatu yang Anda butuhkan untuk menginstal dan menjalankan APA SAJA di komputer secara otomatis.

Ini ditulis dalam JSON, dan juga dapat ditulis dalam JavaScript (yang mengembalikan JSON yang dihasilkan) jika Anda perlu membuatnya berubah secara dinamis.


---

## fs

- [fs.write](#fswrite)
- [fs.read](#fsread)
- [fs.rm](#fsrm)
- [fs.copy](#fscopy)
- [fs.download](#fsdownload)
- [fs.link](#fslink)
- [fs.open](#fsopen)
- [fs.cat](#fscat)

### fs.write

#### syntax

API `fs` menyediakan cara sederhana untuk menulis `json`, `text`, atau `buffer` ke sistem file.

```json
{
  "method": "fs.write",
  "params": {
    "path": <path>,
    <type>: <data>
  }
}
```

- `<path>`: jalur file untuk ditulis (lihat [distributed file URI](#distributed-file-uri))
- `<type>`: `"json"`, `"json2"`, `"text"`, atau `"buffer"`. `<data>` diperlakukan sebagai tipe yang ditentukan oleh nilai `<type>` saat menulis ke file.
- `<data>`:data yang akan ditulis ke file.

#### return value

none

#### examples

##### Writing JSON

Berikut adalah contoh sederhana untuk menulis JSON ke `items.json`

```json
{
  "method": "fs.write",
  "params": {
    "path": "items.json",
    "json": {
      "names": [ "alice", "bob", "carol" ]
    }
  }
}
```

Ini akan menghasilkan file bernama `items.json` yang terlihat seperti ini:

```json
{"names":["alice","bob","carol"]}
```

<br>

##### Writing Multi-line JSON 

Tipe `json` menulis seluruh JSON dalam **satu baris**. Jika kita ingin menulis **multiline JSON**, gunakan tipe `json2`:

```json
{
  "method": "fs.write",
  "params": {
    "path": "items.json",
    "json2": {
      "names": [ "alice", "bob", "carol" ]
    }
  }
}
```

Ini akan menghasilkan `items.json` yang terlihat seperti ini:

```json
{
  "names": [
    "alice",
    "bob",
    "carol"
  ]
}
```

<br>

##### Writing text

```json
{
  "method": "fs.write",
  "params": {
    "path": "items.csv",
    "text": "alice,bob,carol"
  }
}
```

Ini akan menghasilkan `items.csv` yang terlihat seperti ini:

```
alice,bob,carol
```

<br>

##### Writing buffer


Mengonversi string base64 ke Buffer dan menulis ke `img.png`:

```json
{
  "method": "fs.write",
  "params": {
    "path": "img.png",
    "buffer": "{{Buffer.from(input.images[0], 'base64')}}"
  }
}
```

---

### fs.read

#### syntax

API `fs` menyediakan cara sederhana untuk membaca dari file.

```json
{
  "method": "fs.read",
  "params": {
    "path": <path>,
    "encoding": <encoding>
  }
}
```

- `<path>`: jalur file untuk dibaca (lihat [distributed file URI](#distributed-file-uri))
- `<encoding>`: pengkodean data untuk dibaca. Bisa salah satu dari berikut ("buffer" jika tidak ditentukan)
    - "ascii"
    - "base64"
    - "base64url"
    - "hex"
    - "utf8"
    - "utf-8"
    - "binary"


> Secara internal, API memanggil metode fs.readFile dari node.js:
>
> **fs.readFile(params.path, params.encoding)**

#### return value

- `input`: the file content


#### examples

Contoh (membaca `img.png` dan mencetak string yang dikodekan base64):

```json
{
  "run": [{
    "method": "fs.read",
    "params": {
      "path": "img.png",
      "encoding": "base64"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "data:image/png;base64,{{input}}"
    }
  }]
}
```

---

### fs.rm

#### syntax

API `fs.rm` menghapus `file` atau `folder` di jalur yang ditentukan

```json
{
  "method": "fs.rm",
  "params": {
    "path": <path>
  }
}
```

- `<path>`: jalur file untuk ditulis (lihat [distributed file URI](#distributed-file-uri))

#### return value

none


#### examples

example: Menghapus folder `app` di direktori saat ini.

```json
{
  "run": [{
    "method": "fs.rm",
    "params": {
      "path": "app"
    }
  }]
}
```

---

### fs.copy

#### syntax

API `fs.copy` menyalin file atau folder di `src` ke `dest`

```json
{
  "method": "fs.copy",
  "params": {
    "src": <source_path>,
    "dest": <destination_path>
  }
}
```

- `<source_path>`: jalur sumber file untuk disalin (lihat [distributed file URI](#distributed-file-uri))
- `<destination_path>`: jalur tujuan file untuk disalin (lihat [distributed file URI](#distributed-file-uri))

#### return value

none


#### examples

example: Menyalin `hello.txt` ke `world.txt`

```json
{
  "run": [{
    "method": "fs.copy",
    "params": {
      "src": "hello.txt",
      "dest": "world.txt"
    }
  }]
}
```

example: Menyalin folder `app` ke folder baru `api` secara rekursif

```json
{
  "run": [{
    "method": "fs.copy",
    "params": {
      "src": "app",
      "dest": "api"
    }
  }]
}
```

---

### fs.download

API `fs.download` mengunduh file ke jalur atau direktori yang ditentukan. Jika jalur tidak ada, itu dibuat terlebih dahulu jika memungkinkan.

#### syntax

```json
{
  "method": "fs.download",
  "params": {
    "uri": <uri>,
    <type>: <path>
  }
}
```

- `<uri>`: URL file untuk diunduh. Bisa berupa:
  - a url
  - Array dari URL
- `<type>`: bisa berupa `"path"` atau `"dir"`
- `<path>`: jalur tujuan. 
  - Jika `<type>` adalah `"path"`: jalur file untuk diunduh sebagai (lihat [distributed file URI](#distributed-file-uri))
  - Jika `<type>` adalah `"dir"`: jalur direktori untuk mengunduh file ke dalamnya. Nama file jarak jauh akan dipertahankan. (lihat [distributed file URI](#distributed-file-uri))

#### return value

none


#### examples

##### download file as path

example: Download `https://via.placeholder.com/600/92c952` ke file bernama `placeholder.png`

```json
{
  "run": [{
    "method": "fs.download",
    "params": {
      "url": "https://via.placeholder.com/600/92c952",
      "path": "placeholder.png"
    }
  }]
}
```

##### download file into dir

example: Download file di `https://huggingface.co/stabilityai/sdxl-turbo/resolve/main/sd_xl_turbo_1.0.safetensors?download=true` ke dalam folder `models`

```json
{
  "run": [{
    "method": "fs.download",
    "params": {
      "url": "https://huggingface.co/stabilityai/sdxl-turbo/resolve/main/sd_xl_turbo_1.0.safetensors?download=true",
      "dir": "models"
    }
  }]
}
```

##### download files into dir

example: Mengunduh beberapa file ke dalam direktori


```json
{
  "run": [{
    "method": "fs.download",
    "params": {
      "uri": [
        "https://huggingface.co/justimyhxu/GRM/blob/main/grm_u.pth",
        "https://huggingface.co/cocktailpeanut/sv3/blob/main/sv3d_p.safetensors"
      ],
      "dir": "app/checkpoints"
    }
  }]
}
```

---

### fs.link

API `fs.link` menyediakan cara mudah untuk menyimpan data di luar repositori melalui mekanisme yang disebut **Pinokio Virtual Drive**.

Drive virtual memungkinkan Anda menyimpan data di luar aplikasi dan merujuknya dari aplikasi **tanpa mengubah apapun**. Berguna untuk banyak hal, seperti:

1. Menyimpan file yang tetap ada di beberapa instalasi (Mirip dengan Volume Docker)
2. Berbagi file di antara beberapa aplikasi (seperti file model AI `.safetensor`)
3. Menyimpan semua file pustaka (seperti PyTorch) secara deduplikasi

> **Pelajari lebih lanjut tentang Drive Virtual [here](#virtual-drives)**

Berikut adalah operasi yang didukung oleh API `fs.link`:

1. [folder linking](#_1-folder-linking): menautkan jalur folder apa pun dalam repositori saat ini ke jalur drive virtual yang sesuai
2. [peer linking](#_2-peer-linking): secara opsional, Anda dapat membuat drive bersama di antara beberapa aplikasi dengan mendeklarasikannya sebagai **peer drives**. Ini bekerja sama seperti **folder linking**, kecuali itu pertama-tama memeriksa apakah sudah ada drive peer yang ada sebelum membuat satu. Jika sudah ada, drive peer yang ditemukan digunakan alih-alih membuat yang baru.
3. [venv linking](#_3-venv-linking): metode tautan khusus, yang secara otomatis menautkan setiap paket Python yang diinstal di dalam lingkungan venv ke jalur drive yang sesuai.
    - Berguna untuk menghemat ruang disk dengan secara otomatis mendeduplikasi paket yang berlebihan (seperti PyTorch, dll.) di beberapa aplikasi.

#### 1. folder linking

![link_folder.png](link_folder.png)

Anda dapat menautkan folder ke mitra drive virtual dengan:

```json
{
  "method": "fs.link",
  "params": {
    "drive": {
      <drive_folder_path>: <actual_folder_path>,
      <drive_folder_path>: <actual_folder_path>,
      ...
    }
  }
}
```

Setiap panggilan `fs.link` membuat drive virtual yang ditujukan untuk repositori saat ini, lalu menautkan jalur virtual yang ditentukan ke mitra jalur aktual.

- `<drive_folder_path>`: jalur relatif dalam jalur drive virtual untuk dibuat
- `<actual_folder_path>`: jalur folder relatif aktual dalam repositori ini.
  - Harus berupa **folder path** (tidak ada jalur file)
  - Bisa berupa **string** atau **array**
  - Ketika array digunakan, semua jalur dalam array `<actual_folder_path>` akan berubah menjadi tautan simbolik yang menunjuk ke jalur drive virtual `<drive_folder_path>` yang sesuai.

Berikut adalah contoh:

```json

// /PINOKIO_HOME/api/APP1/install.json

{
  "method": "fs.link",
  "params": {
    "drive": {
      "checkpoints": "app/models/checkpoints",
      "clip": "app/models/clip",
      "vae": "app/models/vae"
    }
  }
}
```

1. Panggilan `fs.link` pertama-tama membuat drive virtual untuk repositori saat ini (`/PINOKIO_HOME/api/APP1`)
2. Kemudian menggabungkan semua file di dalam `app/models/checkpoints`, `app/models/clip`, `app/models/vae` ke dalam folder drive virtual yang sesuai (`checkpoints`, `clip`, `vae`)
3. Terakhir, membuat tautan simbolik untuk menautkan jalur aktual ke jalur drive virtual:
    - dari `app/models/checkpoints`, `app/models/clip`, dan `app/models/vae` ke 
    - ke jalur drive virtual yang dibuat untuk repositori ini di `checkpoints`, `clip`, dan `vae` masing masing.

Mari kita lalui setiap langkah satu per satu.

> **NOTE**
>
> Bagian berikut hanya menjelaskan bagaimana API `fs.link` bekerja secara internal, dan bukan sesuatu yang perlu Anda lakukan sendiri. Semua langkah ini ditangani secara otomatis oleh API `fs.link`.
> 
> Baca saja untuk memahami apa yang sebenarnya terjadi saat Anda menjalankan API `fs.link`.

##### Step 1. Drive Creation

`fs.link` pertama-tama membuat drive virtual untuk repositori saat ini. Folder unik untuk repositori saat ini dibuat di bawah `/PINOKIO_HOME/drive/drives/peers`.

Berikut adalah contoh:

```
/PINOKIO_HOME
  /drive
    /drives
      /peers  
        /d1711553147861       <= virtual drive
```


##### Step 2. Create virtual drive folders

Langkah berikutnya adalah membuat folder drive virtual dari kunci di bawah `params.drive`, dalam hal ini:

- `checkpoints`
- `clip`
- `vae`

WKita berakhir dengan drive virtual di jalur berikut:

```
/PINOKIO_HOME
  /drive
    /drives
      /peers  
        /d1711553147861       <= virtual drive
          /checkpoints
          /clip               
          /vae
```

##### Step 3. Merge Files into Drives

Selanjutnya, jika ada file yang sudah ada di dalam folder aplikasi, kita perlu menggabungkannya ke dalam folder drive virtual, karena kita akan mengubah folder ini menjadi tautan simbolik.

> Penggabungan diperlukan, karena jika tidak, semua file tersebut akan hilang selama proses, karena folder asli akan berubah menjadi tautan simbolik pada langkah berikutnya.:

Pinokio menggunakan algoritma penggabungan untuk menggabungkan file di jalur:

- `/PINOKIO_HOME/api/APP1/app/models/checkpoints`
- `/PINOKIO_HOME/api/APP1/app/models/clip`
- `/PINOKIO_HOME/api/APP1/app/models/vae`

ke dalam folder drive virtual:

- `/PINOKIO_HOME/drive/drives/peers//d1711553147861/checkpoints`
- `/PINOKIO_HOME/drive/drives/peers//d1711553147861/clip`
- `/PINOKIO_HOME/drive/drives/peers//d1711553147861/vae`

Pada akhir langkah ini, folder aplikasi asli akan kosong, dan semua file sekarang akan berada di folder drive virtual.

##### Step 4. Create Links

Terakhir, kita menyelesaikan proses dengan menautkan folder aplikasi ke folder drive yang sesuai:

```
/PINOKIO_HOME/api/APP1/app/models/checkpoints => /PINOKIO_HOME/drive/drives/peers//d1711553147861/checkpoints
/PINOKIO_HOME/api/APP1/app/models/clip        => /PINOKIO_HOME/drive/drives/peers//d1711553147861/clip
/PINOKIO_HOME/api/APP1/app/models/vae         => /PINOKIO_HOME/drive/drives/peers//d1711553147861/vae
```


Aplikasi akan bekerja persis sama seperti sebelumnya, karena ketika aplikasi mencoba mengakses folder aplikasi, mereka akan dialihkan oleh tautan simbolik ke folder drive virtual.

Sekarang jika kita mengunduh file bernama `sd_xl_turbo_1.0_fp16.safetensors` ke `/PINOKIO_HOME/api/APP1/app/models/checkpoints`, file aktual akan disimpan di folder drive virtual yang ditautkan seperti ini:


```
/PINOKIO_HOME
  /api
    /APP1
      /app
        /models
          /checkpoints => symbolic liink to /drive/drives/peers/d1711553147861/checkpoints
    /APP2
    /APP3
    ...
  /drive
    /drives
      /peers
        /d1711553147861
          /checkpoints
            sd_xl_turbo_1.0_fp16.safetensors
        ...
  /logs
  /bin
  /cache
```

Namun Anda masih akan dapat mengakses file `sd_xl_turbo_1.0_fp16.safetensors` seolah-olah berada di dalam `/PINOKIO_HOME/api/APP1/app/models/checkpoints` berkat sistem tautan simbolik.

#### 2. peer linking

![link_peer.png](link_peer.png)

Sekarang, bagaimana jika kita ingin berbagi satu drive virtual di antara beberapa aplikasi? Misalnya, katakanlah kita memiliki **3 aplikasi Stable Diffusion yang berbeda** bernama `Stable-Diffusion-WebUI`, `ComfyUI`, dan `Fooocus`, dan semuanya menggunakan file model AI yang sama.

**Bagaimana kita bisa membuat drive virtual sehingga dapat dibagikan oleh ketiga aplikasi tersebut?**

Kita dapat mencapai ini dengan mendeklarasikan **peers** saat membuat drive virtual dengan `fs.link`:


```json
{
  "method": "fs.link",
  "params": {
    "drive": {
      <drive_folder_path>: <actual_folder_path>,
      <drive_folder_path>: <actual_folder_path>,
      ...
    },
    "peers": <peers>
  }
}
```

- `<peers>`: array dari URI repositori git

Satu-satunya perbedaan dari [plain folder linking](#_1-folder-linking) adalah adanya array`peer`.

Ketika array `peers` dideklarasikan, API `fs.link` menjalankan logika berikut terlebih dahulu SEBELUM mencoba membuat folder drive virtualnya sendiri:

1. Melakukan loop melalui array `peers` dan untuk setiap peer memeriksa apakah sudah ada drive virtual yang dibuat.
2. Jika drive virtual ditemukan untuk peer, gunakan drive tersebut alih-alih membuat drive baru.
2. Jika tidak ada drive virtual yang ditemukan untuk salah satu repositori git yang ditentukan dalam array `peers` buat drive virtual menggunakan metode [folder linking method](#_1-folder-linking).

Mari kita lihat contoh spesifik, di mana kita akan menulis skrip untuk `fooocus`, `stable-diffusion-webui`, and `comfyui` sehingga mereka semua mendeklarasikan satu sama lain sebagai peer:

**Install script in https://github.com/cocktailpeanutlabs/fooocus.git**

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "git clone https://github.com/lllyasviel/Fooocus app"
    }
  }, {
    "method": "fs.link",
    "params": {
      "drive": {
        "checkpoints": "app/models/checkpoints",
        "clip": "app/models/clip",
        "clip_vision": "app/models/clip_vision",
        "configs": "app/models/configs",
        "controlnet": "app/models/controlnet",
        "diffusers": "app/models/diffusers",
        "embeddings": "app/models/embeddings",
        "gligen": "app/models/gligen",
        "hypernetworks": "app/models/hypernetworks",
        "inpaint": "app/models/inpaint",
        "loras": "app/models/loras",
        "prompt_expansion": "app/models/prompt_expansion",
        "style_models": "app/models/style_models",
        "unet": "app/models/unet",
        "upscale_models": "app/models/upscale_models",
        "vae": "app/models/vae",
        "vae_approx": "app/models/vae_approx"
      },
      "peers": [
        "https://github.com/cocktailpeanutlabs/automatic1111.git",
        "https://github.com/cocktailpeanutlabs/comfyui.git"
      ]
    }
  }]
}
```

**Install script in https://github.com/cocktailpeanutlabs/automatic1111.git**


```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui app"
    }
  }, {
    "method": "fs.link",
    "params": {
      "drive": {
        "checkpoints": "app/models/Stable-diffusion",
        "vae": "app/models/VAE",
        "loras": [
          "app/models/Lora",
          "app/models/LyCORIS"
        ],
        "upscale_models": [
          "app/models/ESRGAN",
          "app/models/RealESRGAN",
          "app/models/SwinIR"
        ],
        "embeddings": "app/embeddings",
        "hypernetworks": "app/models/hypernetworks",
        "controlnet": "app/models/ControlNet"
      },
      "peers": [
        "https://github.com/cocktailpeanutlabs/comfyui.git",
        "https://github.com/cocktailpeanutlabs/fooocus.git"
      ]
    }
  }]
}
```

**Install script in https://github.com/cocktailpeanutlabs/comfyui.git**

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "git clone https://github.com/comfyanonymous/ComfyUI.git app"
    }
  }, {
    "method": "fs.link",
    "params": {
      "drive": {
        "checkpoints": "app/models/checkpoints",
        "clip": "app/models/clip",
        "clip_vision": "app/models/clip_vision",
        "configs": "app/models/configs",
        "controlnet": "app/models/controlnet",
        "embeddings": "app/models/embeddings",
        "loras": "app/models/loras",
        "upscale_models": "app/models/upscale_models",
        "vae": "app/models/vae"
      },
      "peers": [
        "https://github.com/cocktailpeanutlabs/automatic1111.git",
        "https://github.com/cocktailpeanutlabs/fooocus.git"
      ]
    }
  }]
}
```

Masing-masing dari ketiga skrip ini mendeklarasikan dua lainnya sebagai **peers**:

![peers.png](peers.png)

Jadi, bagaimana ini bekerja dalam praktik?

1. Ketika salah satu dari ketiga skrip ini dijalankan untuk pertama kalinya, tidak akan ada "drive peer" yang sudah ada, sehingga drive virtual baru akan dibuat untuk repositori tersebut.
2. Kemudian jika Anda menjalankan salah satu skrip lainnya, itu akan pertama-tama menjalankan pemeriksaan `peers` untuk menemukan peer yang sudah ada.
3. Karena drive virtual peer sudah dibuat pada langkah 1, drive virtual yang dibuat pada langkah 1 akan digunakan saat menjalankan sisa [fs.link folder linking](#_1-folder-linking), alih-alih membuat drive baru.



#### 3. venv linking

![link_venv.png](link_venv.png)

Salah satu kasus penggunaan yang paling sering ditemui adalah menangani paket berlebihan yang diinstal ke lingkungan `venv` di beberapa aplikasi.

Bayangkan skenario berikut di mana kita memiliki 3 aplikasi berbeda **APP1**, **APP2**, dan **APP3**, masing-masing dengan lingkungan `venv` independennya sendiri:


```
/PINOKIO_HOME
  /api
    /APP1
      requirements.txt
      app.py
      /venv
        /lib
          /python3.10
            /site-packages
              /torch
              /accelerate
              /xformers
    /APP2
      requirements.txt
      app.py
      /venv
        /lib
          /python3.10
            /site-packages
              /torch
              /accelerate
              /xformers
    /APP3
      requirements.txt
      app.py
      /venv
        /lib
          /python3.10
            /site-packages
              /torch
              /accelerate
              /xformers
```

1. SEMUA aplikasi ini memiliki paket berlebihan yang sama yang diinstal (`torch`, `accelerate`, `xformers`, dll.)
2. Namun ini adalah cara kerja venv. Inti dari venv adalah untuk mengisolasi lingkungan, sehingga setiap lingkungan tidak seharusnya tahu tentang lingkungan lain di mesin yang sama.
3. Akan sangat baik untuk memanfaatkan lingkungan terisolasi yang kita dapatkan dari venv, sambil menghilangkan redundansi, sehingga kita bisa menghemat ruang disk.


Dan di sinilah `venv linking` masuk.

Untuk kasus penggunaan khusus ini, ada cara otomatis untuk membuat drive virtual, hanya dengan satu baris.

```json
{
  "method": "fs.link",
  "params": {
    "venv": <venv_path>
  }
}
```

- `<venv_path>`: Jalur folder venv untuk membuat tautan drive virtual.

Ini akan:

1. Melihat semua paket pip yang diinstal ke dalam venv di `<venv_path>`
2. Secara otomatis membuat drive virtual untuk setiap versi unik dari paket yang diinstal
3. Secara otomatis menggabungkan file paket di dalam `<venv_path>` ke jalur drive virtual
4. Secara otomatis membuat tautan simbolik dari semua folder di dalam folder site-packages `<venv_path>` asli yang menunjuk ke folder drive virtual yang dibuat secara otomatis.

Berbeda dengan metode **folder linking** yang membuat drive virtual unik untuk setiap repositori, ada drive pip terpusat tunggal yang diorganisir sebagai berikut:

```
/PINOKIO_HOME
  /drive
    /drives
      /pip
        /accelerate
          /0.20.3
          /0.21.0
          /0.28.0
        /torch
          /2.1.0
          /2.2.2
        ...
```

Pada dasarnya, setiap versi unik dari pustaka unik yang diinstal memiliki jalur folder uniknya sendiri.

Ketika Anda memanggil `fs.link` pada jalur lingkungan venv, berikut adalah yang terjadi:

1. Pinokio memindai folder venv yang ditentukan untuk menemukan semua paket yang diinstal
2. Kemudian untuk setiap paket di venv, itu mencari `/PINOKIO_HOME/drive/drives/pip/<package_name>/<version>` untuk memeriksa apakah sudah ada di drive virtual
3. Jika sudah ada, gunakan yang itu saja
4. Jika TIDAK ada, buat folder versi pustaka (misalnya `/PINOKIO_HOME/drive/drives/pip/torch/2.3.0`), pindahkan semua file ke drive, dan buat tautan simbolik

Dengan cara ini, setiap jalur pustaka di venv hanyalah tautan simbolik ke jalur drive yang dibuat.

Berikut adalah seperti apa hasil akhirnya untuk contoh 3 aplikasi awal dari atas:

```
/PINOKIO_HOME
  /drive
    /drives
      /pip
        /accelerate
          /0.20.3
          /0.21.0
          /0.28.0
        /torch
          /2.1.0
          /2.2.2
        /xformers
          /0.0.25
          /0.0.24
        ...
  /api
    /APP1
      requirements.txt
      app.py
      /venv
        /lib
          /python3.10
            /site-packages
              /torch          => link to /PINOKIO_HOME/drive/drives/pip/torch/2.2.2
              /accelerate     => link to /PINOKIO_HOME/drive/drives/pip/accelerate/0.28.0
              /xformers       => link to /PINOKIO_HOME/drive/drives/pip/xformers/0.0.25
    /APP2
      requirements.txt
      app.py
      /venv
        /lib
          /python3.10
            /site-packages
              /torch          => link to /PINOKIO_HOME/drive/drives/pip/torch/2.2.2
              /accelerate     => link to /PINOKIO_HOME/drive/drives/pip/accelerate/0.28.0
              /xformers       => link to /PINOKIO_HOME/drive/drives/pip/xformers/0.0.25
    /APP3
      requirements.txt
      app.py
      /venv
        /lib
          /python3.10
            /site-packages
              /torch          => link to /PINOKIO_HOME/drive/drives/pip/torch/2.2.2
              /accelerate     => link to /PINOKIO_HOME/drive/drives/pip/accelerate/0.28.0
              /xformers       => link to /PINOKIO_HOME/drive/drives/pip/xformers/0.0.25
```

1. Perhatikan bahwa folder `/torch`, `/accelerate`, and `xformers` emuanya menunjuk ke folder drive virtual bersama. Ini sudah menghemat banyak ruang disk dengan menghilangkan redundansi.
2. Pada saat yang sama, setiap aplikasi bekerja PERSIS sama seperti sebelumnya karena ini adalah tautan simbolik, dan semuanya berperilaku seolah-olah paket pip ini benar-benar disimpan di folder site-packages venv masing-masing aplikasi (tetapi pada kenyataannya mereka hanyalah tautan simbolik yang menunjuk ke drive virtual pip bersama)

---

### fs.open

#### syntax

API `fs.open` membuka penjelajah file untuk jalur yang diberikan

```json
{
  "method": "fs.open",
	"params": {
		"path": "<path>",
    "mode": <mode>
	}
}
```

- `<path>`: jalur file untuk dibuka di penjelajah file
- `<mode>`: (opsional) bisa berupa `view` or `open`. Jika tidak ditentukan, itu dibuka dalam mode `view`.
  - `view`: membuka jalur file di penjelajah file
  - `open`: membuka file di jalur file

#### return value

none


#### example

Membuka folder di penjelajah file

```json
{
  "method": "fs.open",
	"params": {
		"path": "outputs"
	}
}
```

Membuka file (dengan aplikasi apa pun yang menjadi penangan default)

```json
{
  "method": "fs.open",
	"params": {
		"path": "outputs",
    "mode": "open"
	}
}
```


---

### fs.cat

#### syntax

API `fs.cat` mencetak isi file

```json
{
  "method": "fs.cat",
	"params": {
		"path": "<path>"
	}
}
```

- `<path>`: jalur file untuk dicetak di terminal

#### return value

none




---

## jump

Secara default, Pinokio melangkah melalui semua permintaan dalam array `run` dan berhenti di akhir.

Namun, Anda dapat mengimplementasikan pengulangan, yang memungkinkan Anda membangun berbagai alur kerja abadi yang menarik.

#### syntax

```json
{
  "method": "jump",
  "params": {
    <key>: <value>,
    "params": <params>
  }
}
```

- `<key>`: bisa berupa `"index"` atau `"id"`
  - `index`: melompat ke posisi indeks dalam array `run`
  - `id`: melompat ke posisi yang ditandai sebagai `id`
- `<value>`
  - Jika `<key>` adalah "index", melompat ke posisi `<value>` yang ditentukan dalam array `run` (Misalnya jika `"index": 3`, melompat ke `run[3]`).
  - Jika `<key>` adalah "id", melompat ke langkah yang ditandai dengan id `<value>`.
- `<params>`: (opsional) Kadang-kadang Anda mungkin ingin meneruskan argumen ke langkah berikutnya. Nilai `<params>` akan tersedia sebagai `"input"` di dalam langkah berikutnya saat menggunakan ekspresi templat.

#### return value

none


#### examples

##### jump to index

```json
{
  "run": [{
    "method": "jump",
    "params": {
      "index": 2
    }
  }, {
    "method": "log",
    "params": {
      "raw": "hello"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "world"
    }
  }]
}
```

This will print:

```
world
```

##### jump to id

```json
{
  "run": [{
    "method": "jump",
    "params": {
      "id": "w"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "hello"
    }
  }, {
    "id": "w",
    "method": "log",
    "params": {
      "raw": "world"
    }
  }]
}
```

This will print:

```
world
```

##### jump with params

```json
{
  "run": [{
    "method": "jump",
    "params": {
      "id": "w",
      "params": {
        "answer": 42
      }
    }
  }, {
    "method": "log",
    "params": {
      "raw": "hello"
    }
  }, {
    "id": "w",
    "method": "log",
    "params": {
      "raw": "the meaning of life, the universe, and everything: {{input.answer}}"
    }
  }]
}
```

Skrip di atas akan:

1. Pertama menemui langkah `jump` yang melompat ke `id` "w", yang kebetulan merupakan langkah terakhir dalam array `run` (`run[2]`).
2. Selain melompat, itu akan meneruskan `params` dari `{ "answer": 42 }`.
3. Pada langkah terakhir `params` yang diteruskan dari langkah sebelumnya akan tersedia sebagai variabel `input`, dan ekspresi templat `{{input.answer}}` akan dievaluasi menjadi 42

Jadi itu akan mencetak:

```
the meaning of life, the universe, and everything: 42
```

##### loop

Anda dapat menggunakan API jump untuk melakukan pengulangan.

```json
{
  "run": [{
    "id": "start",
    "method": "local.set",
    "params": {
      "counter": "{{local.counter ? local.counter+1 : 1}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "{{'' + local.counter + ' is ' + (local.counter % 2 === 0 ? 'even' : 'odd')}}"
    }
  }, {
    "method": "jump",
    "params": {
      "id": "{{local.counter < 20 ? 'start' : 'end'}}"
    }
  }, {
    "id": "end",
    "method": "log",
    "params": {
      "raw": "finished!"
    }
  }]
}
```

1. Mengatur `local.counter` ke 1
2. Mencetak apakah itu genap atau ganjil
3. Melompat kembali ke `start` jika `local.counter` kurang dari 20
4. Jika tidak, melompat ke `end`.

---

## gradio

### gradio.predict

#### syntax

```json
{
  "method": "gradio.predict",
  "params": {
    "uri": <uri>,
    "path": <path>,
    "params": <params>
  }
}
```

- `<uri>`: gradio endpoint uri
- `<path>`: gradio endpoint route
- `<params>`: the params array to pass to the gradio function

#### return value

- `input`: The return value from the gradio function

#### examples

Mari kita buat permintaan ke titik akhir gradio:

```json
{
  "run": [{
    "method": "gradio.predict",
    "params": {
      "uri": "http://127.0.0.1:7860",
      "path": "/answer_question_1",
      "params": [
        { "path": "https://media.timeout.com/images/105795964/750/422/image.jpg" },
        "Explain what is going on here"
      ]
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{input.data[0]}}"
    }
  }]
}
```

Jika titik akhir mengembalikan `{ "data": ["A man is drinking coffee"] }`, skrip akan mencetak:

```
A man is drinking coffee.
```

---

## hf

API untuk mengakses [huggingface-cli](https://huggingface.co/docs/huggingface_hub/en/guides/cli)

### hf.download

Mengunduh file dari HuggingFace

#### syntax

```json
{
  "method": "hf.download",
  "params": {
    "path": <executing folder path (default is the current path)>,
    "_": [<arg1>, <arg2>, ...],
    <kwarg1>: <val1>,
    <kwarg2>: <val2>,
    ...
  }
}
```

Ini setara dengan:

```
huggingface-cli download <arg1> <arg2> --<kwarg1> <val1> --<kwarg2> <val2>
```

#### example

```json
{
  "method": "hf.download",
  "params": {
    "path": "app/models",
    "_": ["adept/fuyu-8b", "model-00001-of-00002.safetensors"],
    "local-dir": "fuyu"
  }
}
```

Skrip di atas setara dengan:


```
huggingface-cli download adept/fuyu-8b model-00001-of-00002.safetensors --local-dir fuyu
```

---

## local

- [local.set](#localset)

### local.set

Mengatur nilai pada jalur objek (bisa berupa jalur kunci, dan jalur kunci juga bisa mencakup indeks array)

#### syntax

```json
{
  "method": "local.set",
  "params": {
    <key>: <val>,
    ...
  } 
}
```

Mengatur atribut variabel `local` untuk `<key>` sebagai `<val>`.

1. Variabel lokal akan tersedia dari memori selama skrip berjalan.
2. Ketika skrip selesai berjalan, variabel lokal akan hilang.

#### return value

none


#### examples

##### simple key/val

Perintah berikut mengatur variabel lokal `local.name.first` dan `local.animal`:

```json
{
  "run": [{
    "method": "local.set",
    "params": {
      "name": "Alice",
      "animal": "dog"
    }
  }, {
    "method": "log",
    "params": {
      "text": "{{local.name + ' ' + local.animal}}"
    }
  }]
}
```

Ini akan mengatur variabel lokal `name` dan `animal`, dan akan mencetak:

```
Alice dog
```

---

## json

- [json.set](#jsonset)
- [json.rm](#jsonrm)
- [json.get](#jsonget)

### json.set

Mengatur nilai pada jalur objek (bisa berupa jalur kunci, dan jalur kunci juga bisa mencakup indeks array)

#### syntax

```json
{
  "method": "json.set",
  "params": {
    <filepath1>: {
      <key_path1>: <value1>,
      <key_path2>: <value2>
    }
  }
}
```

Di mana `<key_path1>`, `<key_path2>`, ... adalah nilai yang dipisahkan oleh titik `(.)` di mana setiap komponen bisa berupa:

- an array index
- a key in JSON

Beberapa contoh jalur kunci:

- `config`
- `config.api_key`
- `config.0.key`


#### return value

none

#### examples

##### Create a new JSON

Dengan asumsi tidak ada file `config.json` di folder saat ini,

```json
{
  "method": "json.set",
  "params": {
    "config.json": {
      "a": 1,
      "b": 2
    }
  }
}
```

Harus membuat file bernama `config.json` dan mengatur nilainya seperti ini:

```json
{
  "a": 1,
  "b": 2
}
```

##### Updating an existing JSON

Katakanlah file `config.json` sudah memiliki konten berikut:

```json
{
  "a": 1,
  "b": 2
}
```

Katakanlah kita ingin mengatur `a` menjadi 3, dan menambahkan atribut tambahan bernama `c` yang nilainya 10:

```json
{
  "method": "json.set",
  "params": {
    "config.json": {
      "a": 3,
      "c": 10
    }
  }
}
```

Ini akan mengatur `a` menjadi 3 dan `c` menjadi 10, menghasilkan file `config.json`:

```json
{
  "a": 3,
  "b": 2,
  "c": 10
}
```

Perhatikan bahwa atribut `b` tidak disentuh.


##### Updating a deep JSON

Katakanlah `config.json` terlihat seperti berikut:

```json
{
  "api": {
    "key": "1234"
  },
  "endpoint": {
    "port": "11343"
  }
}
```

Kita ingin mengubah nilai `api.key` menjadi `xxxxx`, dan `endpoint.port` menjadi `4200`. Kita dapat mencapai ini dengan:


```json
{
  "method": "json.set",
  "params": {
    "config.json": {
      "api.key": "xxxx",
      "endpoint.port": 4200
    }
  }
}
```

##### Updating a deep JSON with array

Katakanlah `config.json` terlihat seperti berikut:

```json
{
  "numbers": [1,2,3,4]
}
```

Kita ingin mengubah item terakhir dari `4` menjadi `100`. Kita dapat melakukan ini dengan:


```json
{
  "method": "json.set",
  "params": {
    "config.json": {
      "numbers.3": 100
    }
  }
}
```

---


### json.rm

Menghapus atribut dari JSON

#### syntax

```json
{
  "method": "json.rm",
  "params": {
    <filepath1>: [<key_path1>, <key_path2>, ...],
    <filepath2>: [<key_path1>, <key_path2>, ...]
  }
}
```

Dimana `<key_path1>`, `<key_path2>`, ... adalah nilai yang dipisahkan oleh titik `(.)` di mana setiap komponen bisa berupa:

- an array index
- a key in JSON

Some example key paths:

- `config`
- `config.api_key`
- `config.0.key`


#### return value

none

#### examples

##### Simple

Katakanlah `config.json` terlihat seperti ini:

```json
{
  "api_key": "sk_dfsfdsfdsf",
  "port": "11343"
}
```

Jika kita ingin menghapus kunci `api_key`, kita dapat menjalankan:

```json
{
  "method": "json.rm",
  "params": {
    "config.json": ["api_key"]
  }
}
```

Setelah menjalankan ini, file `config.json` akan terlihat seperti ini:


```json
{
  "port": "11343"
}
```

##### Advanced

Katakanlah `config.json` terlihat seperti ini:

```json
{
  "a": {
    "b": {
      "c": 1,
      "d": 2
    }
  },
  "e": 2
}
```

Jika kita ingin menghapus kunci `a.b.c`, kita dapat menjalankan

```json
{
  "method": "json.rm",
  "params": {
    "config.json": ["a.b.c"]
  }
}
```

Setelah menjalankan ini, file `config.json` akan terlihat seperti ini:


```json
{
  "a": {
    "b": {
      "d": 2
    }
  },
  "e": 2
}
```

---

### json.get

Menetapkan isi file JSON ke variabel lokal:

#### syntax

```json
{
  "method": "json.get",
  "params": {
    <key1>: <JSON_file_path1>,
    <key2>: <JSON_file_path2>,
    ...
  }
}
```

Ketika skrip ini dijalankan, `local.<key1>` diatur ke nilai dari `<JSON_file_path1>`, dan `local.<key2>` diatur ke nilai dari `<JSON_file_path2>`.


#### return value

none

#### examples

Katakanlah file `config.json` terlihat seperti ini:

```json
{
  "api_key": "sk_sdfsdfdfsdfdsf"
}
```

Ketika kita menjalankan skrip berikut:

```json
{
  "run": [{
    "method": "json.get",
    "params": {
      "config": "config.json"
    }
  }, {
    "method": "shell.run",
    "params": {
      "message": "python app.py",
      "env": {
        "OPENAI_API_KEY": "{{local.config.api_key}}"
      }
    }
  }]
}
```

1. Langkah pertama menetapkan isi `config.json` ke variabel lokal `local.config`.
2. Langkah kedua memanfaatkan nilai dari `{{local.config.api_key}}`. 



---

## log

#### syntax

```json
{
  "method": "log",
  "params": {
    <type>: <data>
  }
}
```

- `<type>`: tipe data untuk dicetak. Bisa salah satu dari berikut:
  - "raw": mencetak teks mentah
  - "text": sama seperti "raw"
  - "json": mencetak JSON satu baris
  - "json2": mencetak JSON dalam beberapa baris
- `<data>`: data untuk dicetak.

#### return value

none


#### examples

#### printing raw text

```json
{
  "run": [{
    "method": "local.set",
    "params": {
      "hello": "world"
    }
  }, {
    "method": "log",
    "params": {
      "text": "{{local.hello}}"
    }
  }]
}
```

will print:

```
world
```

##### printing JSON

Meneruskan atribut `json` (bukan `raw`) akan mencetak JSON

```json
{
  "run": [{
    "method": "local.set",
    "params": {
      "hello": "world"
    }
  }, {
    "method": "log",
    "params": {
      "json": "{{local}}"
    }
  }]
}
```

will print:

```json
{"hello":"world"}
```

##### printing multiline JSON

Meneruskan atribut `json2` akan mencetak JSON, tetapi dalam beberapa baris:

```json
{
  "run": [{
    "method": "local.set",
    "params": {
      "hello": "world",
      "bye": "world"
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{local}}"
    }
  }]
}
```

akan mencetak objek dalam beberapa baris:

```json
{
  "hello": "world"
  "bye": "world"
}
```

---

## net

#### syntax


```json
{
  "method": "net",
  "params": {
    "url": <url>,
    "method": <method>,
    "headers": <request_headers>,
    "data": <request_data>
  }
}
```

- `<url>`: URL titik akhir
- `<request_headers>`: objek header permintaan HTTP
- `<data>`: request body
- `<method>`: bisa berupa "get", "post", "delete", atau "put"

API `net` secara internal menggunakan pustaka [axios](https://github.com/axios/axios) jadi untuk referensi lengkap API, lihat dokumentasi Axios [here](https://axios-http.com/docs/req_config)

Secara internal, skrip JSON di atas memanggil perintah axios berikut:

```javascript
let response = await axios({
  "url": <url>,
  "method": "get"|"post"|"delete"|"put",
  "headers": <request headers>,
  "data": <request body>,
}).then((res) => {
  return res.data
})
```
#### return value

- `input`: Nilai kembalian dari panggilan fungsi `axios()` dari bagian sebelumnya

#### examples

```json
{
  "run": [{
    "method": "net",
    "params": {
      "url": "http://127.0.0.1:7860/sdapi/v1/txt2img",
      "method": "post",
      "data": {
        "cfg_scale": 7,
        "steps": 30,
        "prompt": "a pencil drawing of a bear"
      }
    }
  }, {
    "method": "fs.write",
    "params": {
      "path": "img.png",
      "buffer": "{{Buffer.from(input.images[0], "base64")}}"
    }
  }]
}
```

---

## notify

Menampilkan popup notifikasi push secara terprogram.

#### syntax

```json
{
  "method": "notify",
  "params": {
    "html": <html>,
    "href": <href>,
    "target": <target>
  }
}
```

- `<html>`: Konten HTML untuk ditampilkan di popup notifikasi. Bisa berupa HTML apa saja
- `<href>`: URL untuk dibuka. Bisa berupa situs web eksternal atau URL skrip
- `<target>`: **optional** dibuka di jendela saat ini jika tidak ditentukan. Jika diatur ke `_blank`, membuka peramban eksternal

#### return value

none

#### examples

##### Basic message

```json
{
  "run": [{
    "method": "notify",
    "params": {
      "html": "simple message"
    }
  }]
}
```

##### Full HTML

Anda bahkan dapat menyertakan elemen HTML penuh, seperti gambar

```json
{
  "run": [{
    "method": "notify",
    "params": {
      "html": "<div><img src='https://www.reactiongifs.com/r/2012/06/homer_lurking.gif'/><p>This is an example</p></div>"
    }
  }]
}
```

##### Notify + Start new script

Anda dapat menampilkan notifikasi, dan memulai skrip baru saat diklik.

```json
{
  "run": [{
    "method": "notify",
    "params": {
      "html": "Click to run index.json",
      "href": "./index.json"
    }
  }]
}
```

##### Notify + Open an external browser

Anda dapat menampilkan notifikasi, dan meluncurkan peramban eksternal saat diklik. Hanya perlu mengatur `href`, dan mengatur `target` ke `_blank`:

```json
{
  "run": [{
    "method": "notify",
    "params": {
      "html": "Click to open https://github.com",
      "href": "https://github.com",
      "target": "_blank"
    }
  }]
}
```

---

## script

- [script.download](#scriptdownload)
- [script.start](#scriptstart)
- [script.stop](#scriptstop)
- [script.return](#scriptreturn)

---

### script.download


Mengunduh skrip dari URI git

#### syntax

```json
{
  "method": "script.download",
  "params": {
    "uri": <uri>,
    "hash": <commit>,
    "branch": <branch>,
    "pull": <should_pull>,
  }
}
```

- `<uri>`: URI git untuk diunduh
- `<commit>`: (optional) hash commit git untuk beralih setelah mengunduh
- `<branch>`: (optional) cabang git untuk beralih setelah mengunduh
- `<should_pull>`: (optional) jika diatur ke `true`, selalu jalankan `git pull` sebelum menjalankan kode (jika ada pembaruan yang dibuat ke cabang jarak jauh)

Ini akan mengunduh URI git yang ditentukan ke folder yang dihasilkan secara otomatis.

Nama folder unduhan secara otomatis diturunkan dari URL repositori.

#### return value

none

---

### script.start

#### syntax

```json
{
  "method": "script.start",
  "params": {
    "uri": <uri>,
    "hash": <commit>,
    "branch": <branch>,
    "pull": <should_pull>,
    "params": {
      "a": "hello",
      "b": "world"
    }
  }
}
```

- `<uri>`: jalur skrip untuk mulai dijalankan
- `<commit>`: (optional) hash commit git untuk beralih setelah mengunduh
- `<branch>`: (optional) cabang git untuk beralih setelah mengunduh
- `<should_pull>`: (optional) jika diatur ke `true`, selalu jalankan`git pull` sebelum menjalankan kode (jika ada pembaruan yang dibuat ke cabang jarak jauh)
- `<params>`: parameter untuk diteruskan ke skrip. Parameter akan tersedia sebagai:
  - `<args>`: di seluruh skrip
  - `<params>`: pada metode pertama

#### return value

- `input`: jika skrip yang dipanggil mengembalikan respons dengan `script.return`, nilai ini akan diatur sebagai `input`.

#### examples

##### local script call

Katakanlah kita ingin memanggil `callee.json` dari `index.json`.

`index.json`:

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "callee.json",
      "params": {
        "a": "hello",
        "b": "world"
      }
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{input}}"
    }
  }]
}
```

and the `callee.json`:

```json
{
  "run": [{
    "method": "log",
    "params": {
      "json2": "{{input}}"
    }
  }, {
    "method": "log",
    "params": {
      "text": "{{args.a + ' ' + args.b}}"
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{args}}"
    }
  }, {
    "method": "script.return",
    "params": {
      "response": "{{args.a + ' + ' + args.b}}"
    }
  }]
}
```

This will print:

```
{
  "a": "hello",
  "b": "world"
}
hello world
{
  "a": "hello",
  "b": "world"
}
{
  "response": "hello + world"
}
```

ini dipanggil dengan `params` dari `{ "a": "hello", "b": "world" }`:

1. Pada langkah pertama, BAIK `input` maupun `args` akan menjadi `{ "a": "hello", "b": "world" }`
    - `input` adalah parameter yang diteruskan dari langkah sebelumnya secara langsung, yang berarti nilai `input` akan berbeda untuk setiap langkah.
    - `args` adalah parameter yang diteruskan ke skrip itu sendiri, yang berarti `args` (jika ada), akan memiliki nilai yang sama sepanjang eksekusi skrip.
2. Pada langkah kedua, `args` masih tersedia sebagai nilai yang sama, sehingga mencetak `hello world`
3. Pada langkah ketiga, `args` tetap sama lagi, sehingga mencetak objek `args` yang sama
4. Langkah terakhir (`script.return`) mengembalikan nilai `{ "response": "hello + world" }`
5. Kemudian `index.json` asli melanjutkan ke langkah berikutnya dengan nilai kembalian diatur ke `input`, sehingga metode `log` mencetak `{ "response": "hello + world" }`

karena:

1. `args` akan menjadi `{ "a": "hello", "b": "world" }` sepanjang eksekusi skrip `callee.json`
2. Nilai `input`

##### remote script call

"Skrip jarak jauh" BUKAN berarti membuat permintaan ke server jarak jauh.

Skrip jarak jauh hanya berarti skrip yang diunduh dari server jarak jauh. Dalam hal ini, `uri` bisa berupa skema URI git yang menunjuk ke file. Misalnya `https://github.com/cocktailpeanutlabs/comfyui.git/install.js`.

Berikut adalah contohnya. Katakanlah kita memiliki skrip di `/PINOKIO_HOME/api/myapp/install.json`:

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "https://github.com/cocktailpeanutlabs/torch.git/install.js",
      "branch": "main",
      "params": {
        "venv": "{{path.resolve(cwd, 'env')}}"
      }
    }
  }]
}
```

Ketika skrip ini berjalan, berikut adalah yang terjadi:

1. Pertama, secara internal Pinokio menjalankan [script.download](#scriptdownload) untuk mengkloning repositori di https://github.com/cocktailpeanutlabs/torch.git
2. Kemudian beralih ke cabang git `main`.
3. Lalu memulai skrip [install.js](https://github.com/cocktailpeanutlabs/torch/blob/main/install.js) dengan `params` dari `{ "venv": "{{path.resolve(cwd, 'env')}}" }`, yang diselesaikan menjadi folder `env` dari skrip saat ini
    - Perhatikan bahwa `cwd` adalah jalur dari skrip asli: `/PINOKIO_HOME/api/myapp` (bukan jalur untuk repositori yang baru saja diunduh)
    - Ini berarti `params` aktual yang diteruskan akan terlihat seperti `{ "venv": "/PINOKIO_HOME/api/myapp/install.json" }`

---

### script.stop

#### syntax

```json
{
  "run": [{
    "method": "script.stop",
    "params": {
      "uri": <uri>
    }
  }]
}
```

- `<uri>`: jalur file (atau array dari jalur file). Skrip di jalur tersebut akan dihentikan.

#### return value

none


#### examples

##### stop one script

```json
{
  "run": [{
    "method": "script.stop",
    "params": {
      "uri": "https://github.com/cocktailpeanutlabs/moondream2.git/start.js"
    }
  }]
}
```

##### stop multiple scripts

```json
{
  "run": [{
    "method": "script.stop",
    "params": {
      "uri": [
        "https://github.com/cocktailpeanutlabs/moondream2.git/start1.js"
        "https://github.com/cocktailpeanutlabs/moondream2.git/start2.js"
      ]
    }
  }]
}
```

---

### script.return

#### syntax

`index.json`:

```json
{
  "run": [{
    "method": "script.start",
    "params": {
      "uri": "add.json",
      "params": {
        "a": 1,
        "b": 2,
      }
    }
  }, {
    "method": "log",
    "params": {
      "json2": "{{input.response}}"
    }
  }]
}
```

and the `callee.json`:

```json
{
  "run": [{
    "method": "script.return",
    "params": {
      "response": "{{args.a + args.b}}"
    }
  }]
}
```

Will print:

```
3
```

#### return value

none

> Perhatikan bahwa `script.return` sendiri TIDAK memiliki nilai kembalian karena fungsinya adalah mengembalikan nilai ke skrip pemanggil.

---


## shell

- [shell.run](#shellrun)

### shell.run

#### syntax

Perintah `shell.run` memulai shell instan, menjalankan perintah yang ditentukan, dan menutup shell.

```json
{
  "method": "shell.run",
  "params": {
    "message": <message>,
    "path": <path>,
    "env": <env>,
    "venv": <venv_path>,
    "conda": <conda_config>,
    "on": <shell_event_handler>,
    "sudo": <sudo>,
    "cache": <cache>
  }
}
```

- `<message>`: Pesan untuk dimasukkan ke dalam shell. Bisa berupa string atau array.
  - **string** => memasukkan pesan tersebut.
  - **array** => memasukkan pesan dalam array secara berurutan.
    - Misalnya `"message": ["pip install -r requirements.txt", "pip install torch"]` akan secara internal menjalankan: `pip install -r requirements.txt && pip install torch`
- `<path>` **(optional)**: Jalur dari mana sesi shell dimulai (bisa berupa jalur relatif atau absolut).
  - **When NOT specified:** shell dimulai dari jalur yang sama dengan skrip yang sedang berjalan.
  - **When specified:** sesi shell dimulai dari jalur yang ditentukan
- `<env>` **(optional)**: Pasangan kunci/nilai variabel lingkungan.
  - Ketika pasangan kunci/nilai ditentukan, nilai lingkungan khusus diatur.
  - Ketika TIDAK ditentukan, shell menggunakan lingkungan default
- `<venv_path>` **(optional)**: Sintaks deklaratif untuk secara otomatis membuat atau mengaktifkan lingkungan venv di jalur yang ditentukan.
  - **When NOT specified (default):** Tidak membuat atau mengaktifkan venv dan menjalankan sesi shell secara normal.
  - **When specified:** Membuat venv di jalur yang ditentukan jika belum ada, atau jika sudah ada, mengaktifkan venv yang ada di jalur yang ditentukan, dan menjalankan sesi shell di venv tersebut.
  - Shell secara otomatis membuat lingkungan venv di jalur tersebut jika belum ada, lalu secara otomatis mengaktifkan lingkungan sebelum menjalankan perintah yang ditentukan oleh atribut `message` .
- `<conda_config>` **(optional)**: Sintaks deklaratif untuk mendefinisikan lingkungan conda yang akan diaktifkan untuk sesi shell ini. Bisa berupa objek atau string.
  - **When NOT specified (default):** Secara default, Pinokio menginstal beberapa modul esensial di lingkungan `base` conda yang diisolasi untuk Pinokio (Bahkan jika Anda memiliki conda yang diinstal secara global di sistem Anda, Pinokio TIDAK akan menggunakannya dan menggunakan conda terisolasi yang built-in di Pinokio).
  - **When specified:** `<conda_config>` bisa berupa **string** atau **object**.
    - **string:** `<conda_config>` diinterpretasikan sebagai jalur tempat lingkungan conda disimpan. Contoh: jika `"conda": "conda_env"`, shell akan mengaktifkan lingkungan conda di jalur `conda_env`.
    - **object:** Dalam beberapa kasus, Anda mungkin ingin cara yang lebih canggih untuk membuat/mengaktifkan lingkungan conda secara deklaratif. Ketika `<conda_config> adalah **object** alih alih **string**, aturan berikut berlaku:
      - `path`: Sama seperti ketika `<conda_config>` adalah string. Diinterpretasikan sebagai jalur tempat lingkungan conda disimpan. (Contoh: jika `"conda": "conda_env"`, shell akan mengaktifkan lingkungan conda di jalur `conda_env`).
      - `name`: Nama lingkungan conda untuk diaktifkan. Berbeda dengan aktivasi berdasarkan jalur, lingkungan yang dibuat/diaktifkan dengan cara ini disimpan secara terpusat di bawah folder `PINOKIO_HOME/bin/miniconda`.
      - `skip`: Jika diatur ke `true`, JANGAN mengaktifkan lingkungan APA PUN (Secara default ini diatur ke `false`, sehingga setiap shell mengaktifkan lingkungan `base` global Pinokio setiap kali kecuali Anda menentukan dengan atribut `params.conda`).
      - `python`: Versi Python untuk diinstal di dalam lingkungan (Default adalah `python=3.10` jika tidak ditentukan)

  - Shell secara otomatis membuat lingkungan conda di jalur tersebut jika belum ada, lalu secara otomatis mengaktifkan lingkungan sebelum menjalankan perintah yang ditentukan oleh atribut `message`.
- `<shell_event_handler>` **(optional)**: Penangan peristiwa untuk shell. Dapat digunakan untuk mengurai terminal saat menjalankan `shell.run`. Hasil yang diurai dapat diteruskan ke panggilan API berikutnya dalam array `run` sebagai variabel `input`.
  - **if specified:** Shell terus berjalan hingga pola yang ditentukan terpenuhi.
    - Anda dapat memiliki beberapa item dalam array `<shell_event_handler>` Peristiwa pertama yang cocok akan menangani peristiwa tersebut dan melanjutkan ke langkah berikutnya. Objek penangan peristiwa dapat memiliki atribut berikut:
      - `event`: String ekspresi reguler untuk dicocokkan.
      - `kill`, `done`, or `break`: Menjelaskan perilaku saat kecocokan `event` terjadi. Baik membunuh proses shell dan melanjutkan, menjaga proses berjalan dan melanjutkan, atau berhenti dan tidak melanjutkan.
        - Jika `done: true` diatur, jaga shell dan proses terkait tetap berjalan dan lanjutkan ke langkah berikutnya (Berguna saat Anda menggunakan shell untuk meluncurkan proses yang perlu terus berjalan, seperti server web)
        - Jika `kill: true` diatur, bunuh sesi shell dan semua proses yang terkait dengan sesi shell sebelum melanjutkan ke langkah berikutnya.
        - Jika `break: true` diatur, hentikan shell dan tampilkan layar biru (layar tampilan kesalahan) dengan pola peristiwa yang cocok disorot. Misalnya, jika Anda ingin berhenti dan menghentikan skrip dari melanjutkan saat shell menemui "Exception", Anda dapat menentukan `{ event: "/exception/i", break: true }`
        - JIka `break: false` diatur, abaikan pola peristiwa yang ditentukan secara eksplisit. Misalnya, secara default `/Error:/` ditangkap, tetapi jika Anda ingin skrip mengabaikan saat terminal menemui pola `Error: not critical` Anda dapat menentukan `{ event: "/error: not critical/i", break: false }`.
  - **if NOT specified (default):** Shell berakhir hanya ketika mencapai prompt terminal berikutnya (ketika semua perintah selesai dijalankan, yang akan memicu prompt untuk ditampilkan lagi di akhir). 
- `<sudo>`: **(optional)** Jalankan dalam mode admin saat diatur ke `true`.
  - Di Mac dan Linux, itu menjalankan perintah dengan `sudo <message>`
  - Di Windows, itu menjalankan perintah dalam mode administrator
- `<cache>`: **(optional)** cache path
  - Subfolder berikut akan dihasilkan di bawah folder cache, yang akan diisi secara terprogram saat aplikasi berjalan:
    - `HF_HOME`: Cache HuggingFace. Digunakan untuk menyimpan file model yang diunduh dari HuggingFace.
    - `TORCH_HOME`: Cache hub PyTorch. Digunakan untuk menyimpan file model yang diunduh dari hub PyTorch
    - `GRADIO_TEMP_DIR`: Cache Gradio. Digunakan untuk menyimpan file yang diproses oleh Gradio

#### return value

- `input`:
  - `id`: The internal shell ID
  - `stdout`: The raw shell content
  - `event`: Jika panggilan `shell.run` memiliki parser shell`on` yang dilampirkan, nilai kembalian akan memiliki atribu `event` , yang merupakan objek kecocokan ekspresi reguler dari pola pertama yang cocok dalam `<shell_event_handler>`.

**Example:**

When running:

```json
{
  "daemon": true,
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "python app.py",
      "venv": "env",
      "on": [{
        "event": "/http:\/\/[0-9.:]+/",
        "done": true
      }]
    }
  }, {
    "method": "local.set",
    "params": {
      "url": "{{input.event[0]}}"
    }
  }, {
    "method": "log",
    "params": {
      "raw": "Running on {{local.url}}"
    }
  }]
}
```

Langkah pertama akan mengembalikan `input` sebagai objek berikut:

```json
{
  "id": "8e04df87-9b97-4e80-8e77-9224fcb0204f",
  "stdout": "\r\nThe default interactive shell is now zsh.\r\nTo update your account to use zsh, please run `chsh -s /bin/zsh`.\r\nFor more details, please visit https://support.apple.com/kb/HT208050.\r\n<<PINOKIO SHELL>> eval \"$(conda shell.bash hook)\" && conda deactivate && conda deactivate && conda deactivate && conda activate base && source /Users/x/pinokiomaster/api/comfyui.git/app/env/bin/activate /Users/x/pinokiomaster/api/comfyui.git/app/env && python main.py --force-fp16\r\n** ComfyUI startup time: 2024-04-06 22:53:40.865398\r\n** Platform: Darwin\r\n** Python version: 3.10.12 (main, Jul  5 2023, 15:02:25) [Clang 14.0.6 ]\r\n** Python executable: /Users/x/pinokiomaster/api/comfyui.git/app/env/bin/python\r\n** Log path: /Users/x/pinokiomaster/api/comfyui.git/app/comfyui.log\r\n\r\nPrestartup times for custom nodes:\r\n   0.0 seconds: /Users/x/pinokiomaster/api/comfyui.git/app/custom_nodes/ComfyUI-Manager\r\n\r\nTotal VRAM 65536 MB, total RAM 65536 MB\r\nForcing FP16.\r\nSet vram state to: SHARED\r\nDevice: mps\r\nVAE dtype: torch.float32\r\nUsing sub quadratic optimization for cross attention, if you have memory or speed issues try using: --use-split-cross-attention\r\n### Loading: ComfyUI-Manager (V2.7.2)\r\n### ComfyUI Revision: 1969 [02409c30] | Released on '2024-02-12'\r\n\r\nImport times for custom nodes:\r\n   0.1 seconds: /Users/x/pinokiomaster/api/comfyui.git/app/custom_nodes/ComfyUI-Manager\r\n\r\nStarting server\r\n\r\nTo see the GUI go to: http://127.0.0.1:8188",
  "event": [
    "http://127.0.0.1:8188"
  ]
}
```

- As a result, the `local.url` will be set to `{{input.event[0]}}` which evaluates to `http://127.0.0.1:8188`.
- And finally the last `log` step will print:

```
Running on http://127.0.0.1:8188
```


#### examples

##### message

Anda dapat meneruskan satu pesan (string), atau beberapa pesan (array):

###### Single message

Jika atribut `message` adalah string tunggal, itu hanya memasukkan baris tersebut ke shell.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "venv": "env",
      "message": "pip install -r requirements.txt"
    }
  }]
}
```

###### Multiple messages

Jika atribut `message` dalah array, itu menjalankan perintah secara berurutan.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "venv": "env",
      "message": [
        "pip install -r requirements.txt",
        "pip install torch gradio"
      ]
    }
  }]
}
```

##### path

Atribut jalur digunakan untuk menentukan jalur dari mana shell dimulai.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "path": "app",
      "message": "python app.py"
    }
  }]
}
```

Dalam contoh ini, shell dimulai dari folder `app` pada dasarnya menjalankan Python untuk file `app/app.py`.

##### env

Atribut lingkungan dapat digunakan untuk menyisipkan variabel lingkungan khusus saat memulai shell.


```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "env": {
        "PYTORCH_ENABLE_MPS_FALLBACK": "1"
      },
      "message": "python app.py"
    }
  }]
}
```

Dalam contoh ini, variabel lingkungan `PYTORCH_ENABLE_MPS_FALLBACK` diatur ke `"1"` sebelum menjalankan `python app.py`.


##### venv

Atribut venv digunakan untuk secara deklaratif mengaktifkan lingkungan venv hanya dengan 1 baris.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "venv": ".env",
      "message": "python app.py"
    }
  }]
}
```

Dengan hanya satu baris di atas, itu baik membuat venv di jalur `.env` (jika belum ada), dan mengaktifkan lingkungan untuk sesi shell tertentu ini.

Pada dasarnya, ketika `.env` sudah ada, itu setara dengan:

```
source .env/bin/activate
python app.py
```

Dan ketika `.env` tidak ada, itu setara dengan:

```
python -m venv .env
source .env/bin/activate
python app.py
```

Tapi Anda tidak perlu khawatir tentang semua ini karena dengan hanya satu baris `"venv": ".env"` ini ditangani secara otomatis.

Perhatikan bahwa lingkungan venv bersifat sementara untuk panggilan `shell.run` jadi ketika sesi shell itu berakhir, venv tidak lagi aktif.

For example:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "venv": "env1",
      "message": "python app.py"
    }
  }, {
    "method": "shell.run",
    "params": {
      "venv": "env2",
      "message": "python app.py"
    }
  }]
}
```

Dalam contoh di atas, `shell.run` pertama berjalan di lingkungan `env1` sedangkan `shell.run` kedua berjalan di lingkungan `env2` Kedua sesi shell ini sepenuhnya independen satu sama lain.

##### conda

The conda attribute

###### 1. default is base

Secara default, jika Anda tidak menentukan atribut `conda` dalam `shell.run`, itu akan secara otomatis mengaktifkan lingkungan `base` yang diisolasi oleh Pinokio.

> Bahkan jika Anda memiliki conda yang diinstal secara global, itu TIDAK akan menggunakan lingkungan base di seluruh sistem Anda, tetapi menggunakan lingkungan base Pinokio sendiri. Ini untuk memastikan semuanya bekerja sama persis untuk setiap pengguna di setiap sistem.

Misalnya, berikut akan secara otomatis mengaktifkan lingkungan `base` Pinokio sebelum memulai shell (yang dapat Anda temukan di `/PINOKIO_HOME/bin/miniconda`):

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "python app.py"
    }
  }]
}
```

###### 2. specifying custom conda environment path

Anda juga dapat membuat dan/atau mengaktifkan lingkungan conda khusus di jalur tertentu:

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "conda": "conda_env",
      "message": "python app.py"
    }
  }]
}
```

Skrip di atas akan:

1. Pertama periksa apakah ada lingkungan conda di jalur `conda_env` (relatif terhadap folder saat ini)
2. Jika ada, aktifkan lingkungan tersebut
3. Jika tidak ada lingkungan conda di sana, buat lingkungan conda di lokasi tersebut dan aktifkan.
4. Terakhir mulai sesi shell dan jalankan perintah `python app.py`


###### 3. specifying custom conda environment by name

Anda juga dapat membuat/mengaktifkan lingkungan conda berdasarkan nama. Dalam kasus ini Anda perlu menggunakan sintaks `object` alih-alih menggunakan `string`.

Perbedaannya adalah, alih-alih menyimpan lingkungan conda di jalur tertentu, lingkungan akan disimpan di dalam `/PINOKIO_HOME/bin/miniconda`.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "conda": {
        "name": "conda_env",
      },
      "message": "python app.py"
    }
  }]
}
```

> Menulis skrip yang membuat lingkungan conda khusus berdasarkan nama tidak direkomendasikan, karena potensi masalah bentrokan nama. Jika Anda benar-benar harus menggunakan conda, buat lingkungan conda khusus menggunakan jalur sebagai gantinya.


###### 4. skip activating any conda environment

Biasanya Anda mungkin tidak ingin melakukan ini, tetapi Anda bisa menghindari opsi default untuk mengaktifkan lingkungan `base` conda jika Anda mau.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "conda": {
        "skip": true
      },
      "message": "python app.py"
    }
  }]
}
```


###### 5. custom conda environment with custom python

Anda dapat membuat lingkungan conda khusus dengan versi Python khusus menggunakan atribut `conda.python`:


```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "conda": {
        "path": "custom_python_conda_env",
        "python": "python=3.11"
      },
      "message": "python app.py"
    }
  }]
}
```



##### on

Atribut `on` memungkinkan Anda mengimplementasikan parser shell secara real-time.

1. Pantau konten shell secara real-time
2. Ketika salah satu peristiwa yang ditentukan cocok, lanjutkan ke langkah berikutnya bersama dengan pola yang cocok sebagai `input.event`
3. Selain itu, tentukan apakah akan membunuh proses shell (`kill`) atau menjaganya tetap berjalan (`done`)

###### 1. keep the shell process running and move on

```json
{
  "daemon": true,
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "python app.py",
      "venv": "env",
      "on": [{
        "event": "/http:\/\/[0-9.:]+/",
        "done": true
      }]
    }
  }, {
    "method": "local.set",
    "params": {
      "url": "{{input.event[0]}}"
    }
  }]
}
```

Explanation:

1. **method:** Jalankan perintah dengan `shell.run` yang memulai server web (`python app.py`)
2. **venv:** Shell secara otomatis diaktifkan ke venv di jalur `env` (relative path).
3. **on:**  mengambil array dari beberapa peristiwa yang mungkin (Dalam kasus ini hanya satu peristiwa).
    - **event** Shell terus berjalan hingga ekspresi reguler `/http:\/\/[0-9.:]+/`,
    - **done:** Since `done: true` diatur, perilakunya adalah melanjutkan ke panggilan RPC berikutnya sambil menjaga proses shell tetap berjalan. Ini diperlukan karena kita ingin proses `python app.py` terus berjalan (ini adalah server web).
        - Nilai kembalian dari metode ini adalah `{ id, stdout, event }` where:
          - `id`: the id of the terminal
          - `stdout`: the full content of the terminal
          - `event`: the regular expression match object (see https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match).
4. Di langkah berikutnya `local.set`, variabel `input` yang diteruskan dari langkah sebelumnya berisi atribut `{ id, stdout, event }`.
    - Atribut `input.event` adalah array kecocokan ekspresi reguler dari langkah sebelumnya (lihat https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match).
    - Kita menggunakan `input.event[0]` untuk mengatur variabel lokal `local.url`.

###### 2. kill the shell process and move on

Example:

```json
{
  "daemon": true,
  "run": [{
    "method": "shell.run",
    "params": {
      "message": "python app.py",
      "venv": "env",
      "on": [{
        "event": "/http:\/\/[0-9.:]+/",
        "kill": true
      }]
    }
  }, {
    "method": "local.set",
    "params": {
      "url": "{{input.event[0]}}"
    }
  }]
}
```

Sama seperti kasus `done: true` tetapi dalam kasus ini `kill: true` diatur, sehingga ketika kecocokan `event` terjadi, sesi shell serta semua proses yang terkait dengannya dimatikan sebelum melanjutkan ke langkah berikutnya.


###### 3. stop the shell and display an error screen


Example:

```json
// break.js
module.exports = {
  run: [{
    method: "shell.run",
    params: {
      message: "{{platform === 'win32' ? 'dir' : 'ls'}}",
      on: [{
        event: "/break.*js/",
        break: true
      }]
    }
  }]
}
```

Above script:

1. Menjalankan "dir" (di Windows) atau "ls" (di Linux atau Mac)
2. Jika menemui pola `/break.*js/`, itu berhenti dengan layar biru berikut dengan peristiwa yang cocok `break.js` disorot:

![break.png](break.png)



#### sudo

Jalankan perintah shell dalam mode admin.

```json
{
  "run": [{
    "method": "shell.run",
    "params": {
      "sudo": true,
      "message": "reg add HKLM\\SYSTEM\\CurrentControlSet\\Control\\FileSystem /v LongPathsEnabled /t REG_DWORD /d 1 /f",
    }
  }]
}
```

Dalam kasus ini, kita mencoba mengatur nilai registri, yang perlu dijalankan dalam mode admin, dan kita dapat dengan mudah meneruskan opsi `sudo: true` untuk mencapai ini.

---

# Custom Script

Bagian sebelumnya membahas beberapa metode API bawaan yang tersedia langsung dari kotak.

Tetapi Anda bahkan dapat menulis metode JavaScript kustom Anda sendiri yang dapat dipanggil menggunakan sintaks JSON-RPC yang sama. Ada dua langkah untuk menulis API Anda sendiri:

1. Tulis kelas JavaScript dengan logika kustom Anda sendiri.
2. Panggil kelas JavaScript melalui skrip.

## Quickstart

### 1. Write an API in JavaScript

File JavaScript adalah tempat semua logika ditulis. Ini harus mengikuti konvensi berikut:

```javascript
// api.js
// The class name can be anything, it doesn't matter
const fs = require('fs')
class API {
  // req: the request object, where the request.params contains the arguments passed in from an external script
  // ondata: can be used to print to the terminal
  // kernel: direct access to the kernel
  async custom_method(req, ondata, kernel) => {
    // Do stuff here. Here's an example
    let res = await fetch(req.params.url).then((res) => {
      return res.json()
    })
    await fs.promises.writeFile("result.json", JSON.stringify(res))
  }
}
module.exports = API
```

### 2. Call the API from Script

Sekarang setelah kita menulis logika, kita dapat memanggilnya dari skrip Pinokio mana pun. Sintaksnya adalah sintaks JSON-RPC yang sama.

```json
{
  "method": <method_name>,
  "uri": <file_path>,
  "params": <params>
}
```

Perbedaannya dalam kasus ini adalah, kita memiliki atribut `uri` tambahan.

- `<method_name>`: The method name to callNama metode untuk dipanggil
- `<file_path>`: Jalur file yang berisi kelas API
- `<params>: TParameter untuk diteruskan ke kelas API melalui `req.params`

Misalnya, untuk memanggil metode `custom_method()` dalam kelas `API` di atas, kita dapat melakukan:

```json
{
  "run": [{
    "uri": "api.js",
    "method": "custom_method",
    "params": {
      "url": "https://jsonplaceholder.typicode.com/todos/1"
    }
  }]
}
```

Ini akan memanggil `custom_method()` dari kelas `API` di dalam file `api.js`.

Ini akan meneruskan `https://jsonplaceholder.typicode.com/todos/1` melalui params, sehingga `req.params.url` akan menjadi `https://jsonplaceholder.typicode.com/todos/1`.

## Example

### Writing a browser automation API

Katakanlah Anda ingin menulis API yang menerima URL dan membuka URL tersebut di peramban secara otomatis.

Kita dapat menggunakan variabe `kernel.playwright` untuk menggunakan [Playwright](https://playwright.dev/) yang disertakan dalam kernel Pinokio. Mari kita buat file`browser.js` :

```javascript
// browser.js
class Browser {
  async open(req, ondata, kernel) {
    let { firefox } = kernel.playwright
    const browser = await firefox.launch({ headless: false, });
    const context = await browser.newContext({ viewport: null })
    const page = await context.newPage()
    await page.goto(req.params.url)
  }
}
module.exports = Browser
```

Sekarang kita dapat memanggil ini dari skrip:

```json
{
  "run": [{
    "uri": "browser.js",
    "method": "open",
    "params": {
      "url": "https://pinokio.computer"
    }
  }]
}
```

Ini akan meneruskan `req.params.url` sebagai `https://pinokio.computer` ke metode `open()`dalam kelas `browser.js` yang secara otomatis meluncurkan peramban Firefox dan menavigasi ke URL `req.params.url`.

---

# UI

API RPC memungkinkan Anda menjalankan sesuatu secara otomatis. Tetapi kita juga memerlukan antarmuka pengguna untuk berinteraksi dengannya.

<img src="monitor.png" class='fixed'>

Sama seperti `skrip`, Anda dapat menulis UI hanya menggunakan JSON (atau JavaScript).

## components

Untuk setiap proyek, Anda hanya perlu memikirkan dua komponen UI:

1. **shortcut:** Ditampilkan di halaman utama.
2. **app:** Tata letak UI yang sebenarnya.

### shortcut

![ui0.png](ui0.png)

### app

![ui1.png](ui1.png)

## pinokio.js

Membangun UI hanya membutuhkan satu file bernama `pinokio.js`. Cukup tempatkan file bernama `pinokio.js` di folder root proyek.

File `pinokio.js` mendeskripsikan keduanya:

1. **Shortcut UI**
2. **App UI**

> **Bagaimana jika tidak ada file `pinokio.js`?**
>
> Dalam kasus ini, Pinokio akan berusaha sebaik mungkin untuk menghasilkan UI minimal untuk Anda:
>
> 1. UI pintasan hanya akan menampilkan nama folder sebagai judulnya, dan ikon default.
> 2. UI aplikasi akan menampilkan semua file `js` atau `json` di dalam folder root proyek.

Namun, dalam kebanyakan kasus, Anda akan ingin menulis file `pinokio.js` sederhana untuk membangun UI kustom Anda sendiri.


### syntax

```javascript
module.exports = {
  "version": <script_schema_version>,
  "title": <title>,
  "icon": <icon>,
  "description": <description>,
  "menu": <menu>,
  "pre": <pre>,
  "start": <start>
}
```

- `<script_schema_version>`: Versi skema yang digunakan (**versi terbaru adalah `"2.0"`**)
- `<title>`: Judul aplikasi
- `<description>`: Deskripsi aplikasi
- `<icon>`: Jalur file gambar ikon (contoh `icon.png`, `icon.jpeg`, `icon.gif`, `icon.webp`, dll)
- `<menu>`: **Array** dari item tab, atau **async function** yang mengambil `kernel` dan `info` sebagai argumen dan mengembalikan array item tab yang sama. Setiap item dalam array dapat memiliki atribut berikut:
    - `text`: Teks untuk ditampilkan pada tab.
    - `icon`: Jalur file ikon untuk ditampilkan pada tab.
    - `href`: URL untuk dibuka di tab.
    - `params` (optional): Parameter kueri untuk diteruskan ke tab.
      - Jika diteruskan ke skrip, `params`akan tersedia sebagai variabel `input` di dalam langkah pertama dari skrip `run`.
    - `popout` (optional):Membuka tautan `href` di peramban eksternal alih-alih Pinokio jika diatur ke `true`
    - `menu` (optional): Jika ditentukan, membuat menu bersarang. Menu bersarang mengikuti spesifikasi yang sama seperti menu tingkat atas (dengan atribut `text`, `icon`, `href`, `params`, and `popout`)
    - `default` (optional): Jika ditentukan, item tab ini secara otomatis dipilih secara default. Ketika atribut `href` adalah URL skrip, pemilihan juga berarti skrip akan secara otomatis dimulai. Ini dapat digunakan untuk mengimplementasikan skrip yang dieksekusi secara otomatis.
- `<pre>`: (optional) ika skrip memerlukan instalasi program pihak ketiga yang tidak dapat dengan mudah diinstal melalui skrip, Anda dapat menentukan array `pre` untuk memberikan tautan unduhan kepada pengguna sebelum instalasi dimulai. Setiap item dalam array `pre` dapat memiliki atribut berikut:
    - `text`: Teks untuk ditampilkan untuk item tersebut.
    - `icon`: Jalur file ikon untuk ditampilkan untuk item tersebut.
    - `description`: Deskripsi.
    - `href`: URL untuk dibuka.
    - `fs`: Membuka file di penjelajah file atau aplikasi default.
      - Jika diatur ke `"open"`, membuka file
      - Jika diatur ke `"view"`, membuka di penjelajah file
      - Jika diatur ke `true`, sama seperti `"view"`. Membuka di penjelajah file.
     
- `<start>`: Deklarasi skrip mulai. 
    - Types: bisa berupa `string` atau `object`.
      - string: `url`
      - object: dapat memiliki atribut berikut:
        - `url`: url
        - `params`: Parameter untuk diteruskan ke URL
  

---

### examples

#### Prerequisite apps

Katakanlah sebuah aplikasi membutuhkan [Ollama](https://ollama.com) untuk berjalan.

Kita dapat mengarahkan pengguna untuk menginstal Ollama sebelum menginstal aplikasi, menggunakan sintaks `<pre>` dalam `pinokio.js`:

```javascript
module.exports = {
  version: "2.0",
  title: "LLM App",
  pre: [{
    icon: "ollama.png",
    title: "Ollama",
    description: "Get up and running with large language models.",
    href: "https://ollama.com/"
  }],
  ...
}
```

Ketika ini diunduh, pengguna akan ditunjukkan layar Prasyarat berikut SEBELUM layar instalasi:

![prerequisites.png](prerequisites.png)

#### Static menu

Berikut adalah skrip UI untuk menghasilkan UI peluncur minimal:

```javascript
module.exports = {
  version: "2.0",
  title: "Test Launcher",
  description: "This is for testing a test launcher",
  icon: "icon.png",
  menu: [{
    icon: "fa-brands fa-google",  // see https://fontawesome.com/icons/google?f=brands&s=solid
    text: "Open Google",
    href: "https://google.com",
  }, {
    icon: "fa-brands fa-discord",
    text: "Open Discord in New Window",
    href: "https://discord.gg/TQdNwadtE4",
    popout: true    // "popout": true => opens the link in an external browser instead of as a Pinokio tab.
  }]
}
```

#### Dynamic menu

TMenu bilah sisi secara otomatis dirender ulang setiap kali langkah dalam skrip yang sedang berjalan selesai.

Ini berarti Anda dapat menulis file `pinokio.js` sehingga secara otomatis menampilkan item yang relevan secara real-time.

![dynamicmenu.gif](dynamicmenu.gif)

Misalnya, ketika aplikasi sedang berjalan, Anda mungkin ingin menampilkan tautan untuk membuka UI web yang sebenarnya. Atau ketika aplikasi tidak berjalan, Anda mungkin ingin menampilkan tombol "Mulai" sebagai gantinya.

Kita dapat mencapai rendering menu dinamis jenis ini dengan menggunakan fungsi alih-alih array. Alih-alih menetapkan array `menu` statis, atur `menu` sebagai fungsi `async` yang mengambil `kernel` dan `info` sebagai argumen.

Anda dapat menggunakan variabel `info` ntuk mendapatkan berbagai jenis informasi status tentang file dan skrip:

- `info.local(filepath)`: Mendapatkan objek variabel lokal dari skrip yang berjalan di `filepath`.
- `info.running(filepath)`: Mendapatkan status berjalan dari skrip dit `filepath`.
- `info.exists(filepath)`: Memeriksa apakah file ada di `filepath`.
- `info.path(filepath)`: Mendapatkan jalur absolut dari `fileapth`.

Lihat contoh di bawah ini, di mana itu memanfaatkan API `info` ntuk menentukan apakah skrip `install.json` atau `start.json` sedang berjalan, dan jika ya, mendapatkan variabel lokal di memori, dll.


```javascript
const path = require("path")
module.exports = {
  version: "2.0",
  title: "InvokeAI",
  description: "Generative AI for Professional Creatives",
  icon: "icon.jpeg",
  menu: async (kernel, info) => {
    /**********************************************************************************************
      info memiliki 4 metode (di mana `filepath` bisa berupa jalur relatif atau absolut):
        - info.local(filepath): Mendapatkan objek variabel lokal dari skrip yang berjalan di `filepath`.
        - info.running(filepath): Mendapatkan status berjalan dari skrip di `filepath`.
        - info.exists(filepath): Memeriksa apakah file ada di `filepath`.
        - info.path(filepath): Mendapatkan jalur absolut dari `filepath`.
    **********************************************************************************************/
    let installing = info.running("install.json")
    let installing = info.running("install.json")
    let installed = info.exists("app/env")
    if (installing) {
      return [{ icon: "fa-solid fa-plug", text: "Installing...", href: "install.json" }]
    } else if (installed) {
      let running = info.running("start.json")
      if (running) {
        let memory = info.local("start.json")
        if (memory && memory.url) {
          return [
            { icon: "fa-solid fa-rocket", text: "Web UI", href: memory.url },
            { icon: "fa-solid fa-terminal", text: "Terminal", href: "start.json" },
            { icon: "fa-solid fa-rotate", text: "Update", href: "update.json" },
          ]
        } else {
          return [
            { icon: "fa-solid fa-terminal", text: "Terminal", href: "start.json" },
            { icon: "fa-solid fa-rotate", text: "Update", href: "update.json" },
          ]
        }
      } else {
        return [{
          icon: "fa-solid fa-power-off",
          text: "Start",
          href: "start.json",
        }, {
          icon: "fa-solid fa-rotate", text: "Update", href: "update.json"
        }, {
          icon: "fa-solid fa-plug", text: "Reinstall", href: "install.json"
        }, {
          icon: "fa-solid fa-broom", text: "Factory Reset", href: "reset.json"
        }]
      }
    } else {
      return [
        { icon: "fa-solid fa-plug", text: "Install", href: "install.json" },
        { icon: "fa-solid fa-rotate", text: "Update", href: "update.json" }
      ]
    }
  }
}
```

Berdasarkan status aplikasi yang ditentukan, fungsi`menu` dinamis dapat menghasilkan item menu.

1. Memeriksa apakah file/folder ada di jalur: `info.exists()`
2. Memeriksa apakah skrip di jalur yang ditentukan sedang berjalan:`info.running()`
3. Mendapatkan objek variabel lokal untuk skrip di jalur yang ditentukan: `info.local()`

---

#### Nested menu

Anda dapat menyusun array `menu` ke dalam `menu` (up to level 2)

![nestedmenu.gif](nestedmenu.gif)

```javascript
module.exports = {
  title: "Test Launcher",
  description: "This is for testing a test launcher",
  icon: "icon.png",
  menu: [{
    icon: "fa-solid fa-download",
    text: "Download Models",
    menu: [
      { text: "Download by URL", icon: "fa-solid fa-download", href: "download.html?raw=true" },
      { text: "SDXL", icon: "fa-solid fa-download", href: "download-sdxl.json", mode: "refresh" },
      { text: "SDXL Turbo", icon: "fa-solid fa-download", href: "download-turbo.json", mode: "refresh" },
      { text: "Stable Video XT", icon: "fa-solid fa-download", href: "download-svd-xt.json", mode: "refresh" },
      { text: "Stable Video", icon: "fa-solid fa-download", href: "download-svd.json", mode: "refresh" },
      { text: "Stable Video XT 1.1", icon: "fa-solid fa-download", href: "download-svd-xt-1.1.json", mode: "refresh" },
      { text: "LCM LoRA", icon: "fa-solid fa-download", href: "download-lcm-lora.json", mode: "refresh" },
      { text: "SD 1.5", icon: "fa-solid fa-download", href: "download-sd15.json", mode: "refresh" },
      { text: "SD 2.1", icon: "fa-solid fa-download", href: "download-sd21.json", mode: "refresh" },
      { text: "Playground2.5 fp16", icon: "fa-solid fa-download", href: "download-playground-fp16.json", mode: "refresh" },
      { text: "Playground2.5", icon: "fa-solid fa-download", href: "download-playground.json", mode: "refresh" },

    ]
  }]
}
```

---

#### Auto-execution

Menggunakan atribut `default` dimungkinkan untuk mengimplementasikan skrip yang dieksekusi secara otomatis.

Misalnya, katakanlah kita menginginkan perilaku berikut:

- Jalankan `install.js` jika `app/env` tidak ada.
- Jalankan `start.js` Jika `app/env` ada, dan `start.js` belum berjalan.

```javascript
module.exports = {
  title: "Auto Launcher",
  icon: "icon.png",
  menu: async (kernel, info) => {
    if (info.exists("app/env")) {
      // already installed. select the "start.js", automatically running `start.js`
      return [{
        text: "Install",
        href: "install.js"
      }, {
        default: true,
        text: "Start",
        href: "start.js"
      }]
    } else {
      // not installed yet. select the install.js tab.
      return [{
        default: true,
        text: "Install",
        href: "install.js"
      }, {
        text: "Start",
        href: "start.js"
      }]
    }
  }
}
```

---

# ENVIRONMENT

Meskipun memungkinkan untuk menyesuaikan perilaku skrip dengan langsung memodifikasi file skrip, ini tidak diinginkan.

Kita menginginkan cara untuk menyesuaikan perilaku aplikasi TANPA menyentuh kode. Kita dapat mencapai ini melalui `ENVIRONMENT`.

## Before

Katakanlah Anda ingin menulis skrip yang secara otomatis mengunduh model AI ke direktori yang ditentukan (misalnya `models`). Skrip tersebut mungkin terlihat seperti ini:

```json
{
  "run": [{
    "method": "fs.download",
    "params": {
      "uri": "https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/resolve/main/sd_xl_base_1.0.safetensors",
      "dir": "app/models/Stable-diffusion"
    }
  }]
}
```

Masalahnya adalah, untuk mengubah perilaku skrip ini, pengguna akhir perlu mengedit URI menggunakan editor file.

Bagaimana jika Anda ingin membiarkan pengguna akhir memodifikasi `uri`?

---

## After

Jika Anda ingin menulis skrip yang dapat dengan mudah disesuaikan oleh pengguna, Anda mungkin ingin membuat file bernama `_Environment` (Harus diawali dengan `_`).

Berikut adalah contoh file `_ENVIRONMENT` :

```
#####################################################################################################################
#
# SD_INSTALL_CHECKPOINT
# -- Hapus bidang ini jika Anda tidak ingin mengunduh checkpoint secara otomatis saat menginstal
# - Ganti URL dengan tautan checkpoint lain jika Anda menginginkan checkpoint yang berbeda
#
#
#####################################################################################################################
SD_INSTALL_CHECKPOINT=https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/resolve/main/sd_xl_base_1.0.safetensors
```

Letakkan file ini di dalam root skrip, bersama dengan `pinokio.js`dan `download.json`, seperti ini:

```
pinokio.js
download.json
_ENVIRONMENT
```

Kemudian kita dapat memodifikasi file `download.json` seperti ini:

```json
{
  "run": [{
    "method": "fs.download",
    "params": {
      "uri": "{{env.SD_INSTALL_CHECKPOINT}}",
      "dir": "app/models/Stable-diffusion"
    }
  }]
}
```

---

## Custom Install Screen

Ketika Anda mempublikasikan repositori ini, saat pengguna menginstal skrip, mereka akan ditunjukkan layar instalasi kustom berikut:

![custom_install.png](custom_install.png)

Dengan antarmuka yang ramah pengguna, pengguna dapat menyesuaikan URL mana yang akan digunakan saat pertama kali menginstal aplikasi.

---

## Configure Menu

Juga, setelah instalasi selesai, mereka akan dapat mengakses editor ENVIRONMENT yang sama di bawah menu **Configure** :

![configure.png](configure.png)

---

## How it works
Ketika pengguna mengunduh repositori skrip ini, berikut adalah yang terjadi:

1. File `ENVIRONMENT` baru (perhatikan bahwa tidak ada prefiks `_` ) dibuat dengan mewarisi dari file template `_ENVIRONMENT`.
2. Mulai dari titik ini, `_ENVIRONMENT` TIDAK digunakan.
3. File `ENVIRONMENT`digunakan untuk menyimpan konfigurasi aplikasi ke depannya.
4. Pengguna dapat mengedit konfigurasi baik dengan LANGSUNG mengedit file `ENVIRONMENT` , atau dengan mengedit melalui menu `Configure`.

___

## Isolated Environment for Each App

ariabel lingkungan ini bukanlah sesuatu yang dibuat khusus HANYA untuk Pinokio. Mereka didukung secara internal oleh sistem [Environment variable system](https://en.wikipedia.org/wiki/Environment_variable) yang banyak diadopsi..


Ini berarti kita dapat menggunakan file `ENVIRONMENT` tidak hanya untuk menyesuaikan perilaku skrip tetapi juga APA SAJA yang terjadi di dalam aplikasi. Kapan ini akan berguna?

Seringkali, aplikasi memiliki cara mereka sendiri untuk dikonfigurasi. Misalnya, semua aplikasi berbasis [Gradio](https://www.gradio.app/) memungkinkan Anda [menyesuaikan perilaku aplikasi melalui variabel lingkungan](https://www.gradio.app/main/guides/environment-variables). Secara tradisional, menjalankan aplikasi ini secara kustom melibatkan salah satu dari:

1. Mengubah variabel lingkungan SECARA GLOBAL.
2. Atau menjalankan perintah shell lingkungan seperti `export GRADIO_SERVER_PORT=8080`

Keduanya tidak ideal.

- GPembaruan variabel lingkungan global buruk karena Anda mungkin ingin mempertahankan lingkungan kustom yang berbeda untuk setiap aplikasi individu.
- Harus menjalankan perintah `export` itu merepotkan dan TIDAK ramah pengguna. Anda seharusnya tidak perlu menyentuh terminal.

Untungnya, file `ENVIRONMENT` Pinokio menangani ini secara otomatis.

Katakanlah kita ingin membiarkan pengguna menyesuaikan `GRADIO_SERVER_PORT` dan `GRADIO_TEMP_DIR`. Yang perlu Anda lakukan untuk mengaktifkan ini adalah mengatur nilai-nilai tersebut di file `_ENVIRONMENT` (atau file `ENVIRONMENT` jika pengguna mencoba menyesuaikan ini di sisi mereka):
```
GRADIO_SERVER_PORT=8080
GRADIO_TEMP_DIR=./cache/GRADIO
```

Variabel-variabel ini akan segera tersedia untuk diedit di menu `Configure` , dan setiap kali menjalankan skrip apa pun dari repositori, variabel lingkungan kustom ini akan secara otomatis diterapkan.


---

# Customization

## File System

Tempatkan file kustom di bawah folder `PINOKIO_HOME/web` Anda seperti berikut:

```
~/pinokio
  /web
    config.json       # configure app chrome UI (close button, etc)
    /public           # Static Files
      browser.css     # Custom CSS for App Browser Page
      ...
    /views            # template files
      index.ejs       # home page template file
```


1. `index.ejs`: Ini adalah file template halaman utama. Template ini dapat menampilkan semua aplikasi yang terinstal dengan cara apa pun yang Anda inginkan.
2. `browser.css`: Jika Anda ingin menyesuaikan gaya halaman aplikasi, Anda dapat mengganti tema default dengan menimpa atribut CSS di `browser.css`.

## Home Page

![customize_home.png](customize_home.png)

Untuk menyesuaikan halaman utama, Anda dapat menulis `index.ejs` kustom Anda sendiri. File template dapat menampilkan aplikasi yang terinstal menggunakan atribut berikut:

- `kernel`: API kernel
- `agent`: **"electron"** (berjalan sebagai aplikasi) atau **"web"** (berjalan sebagai server)
- `items`: Array dari item aplikasi yang terinstal
  - `icon`: Nilai `icon` di `pinokio.js`
  - `name`: Nilai `name` di `pinokio.js`
  - `description`: Nilai `description` di `pinokio.js`
  - `path`: Jalur folder
  - `url`: URL aplikasi. Buka URL ini untuk mengunjungi halaman aplikasi.
  - `browse_url`: URL aplikasi TANPA berjalan (Bahkan jika `PINOKIO_SCRIPT_DEFAULT` diatur ke **true**, itu tidak akan berjalan otomatis)
  - `running`: `true` (jika sedang berjalan) atau `false`
  - `running_scripts`: Array dari skrip yang sedang berjalan. Setiap item terdiri dari atribut berikut:
    - `path`: Jalur file dari skrip yang sedang berjalan
    - `name`: Nama file

Anda dapat melakukan ini dengan menambahkan file `/web/views/index.ejs` Anda sendiri. Berikut adalah contohnya:

```html
<html>
  <body>
    <header class='grabbable'></header>
    <main>
      <% items.forEach((item) => { %>
        <% if (item.running) { %>
          <a class='item running' data-browse-url="<%=item.browse_url%>" data-href="<%=item.url%    >" onclick="dblclick(event)">
            <img src="<%=item.icon%>"/>
            <div class='name'><%=item.name%></div>
          </a>
        <% } else { %>
          <a class='item' data-browse-url="<%=item.browse_url%>" data-href="<%=item.url%>" data-    name="<%=item.name%>" data-description="<%=item.description%>" data-path="<%=item.path%>"     onclick="dblclick(event)">
            <% if (item.icon) { %>
              <img src="<%=item.icon%>"/>
            <% } else { %>
              <img src="icon.png"/>
            <% } %>
            <div class='name'><%=item.name%></div>
          </a>
        <% } %>
      <% }) %>
    </main>
  </body>
</html>
---

---

## App Page

Setiap halaman aplikasi juga dapat disesuaikan.

Berbeda dengan halaman utama, yang dapat sepenuhnya disesuaikan dengan HTML Anda sendiri, halaman aplikasi saat ini hanya memungkinkan kustomisasi CSS.

Anda dapat melakukan ini dengan menambahkan file `/web/public/browser.css` Anda sendiri. Berikut adalah contohnya:

```css
body {
  background: firebrick !important;
  color: gold !important;
}
aside {
  background: transparent !important;
}
nav {
  background: none !important;
}
.header-item.btn {
  color: gold !important;
}
.btn2 {
  color: gold !important;
}
```

![theme.png](theme.png)

---

## Title Bar 


Anda dapat menyesuaikan `color` dan `symbolColor` bilah judul (Lihat https://www.electronjs.org/docs/latest/tutorial/custom-title-bar#custom-window-controls)

Cukup tentukan atribut tersebut di dalam file `web/config.json`

```json
{
  "color": "rgba(255,255,255,0)",
  "symbolColor": "white"
}
```

---

## Terminal

![customize_xterm.png](customize_xterm.png)

Anda dapat sepenuhnya menyesuaikan terminal dengan mengatur atribut `xterm` di file `web/config.json`:



```json
{
  "color": "rgba(255,255,255,0)",
  "symbolColor": "white",
  "xterm": {
    "fontSize": 20,
    "theme": {
      "foreground": "#637d75",
      "background": "#0f1610",
      "cursor": "#73fa91",

      "black": "#112616",
      "brightBlack": "#3c4812",

      "red": "#7f2b27",
      "brightRed": "#e08009",

      "green": "#2f7e25",
      "brightGreen": "#18e000",

      "yellow": "#717f24",
      "brightYellow": "#bde000",

      "blue": "#2f6a7f",
      "brightBlue": "#00aae0",

      "magenta": "#47587f",
      "brightMagenta": "#0058e0",

      "cyan": "#327f77",
      "brightCyan": "#00e0c4",

      "white": "#647d75",
      "brightWhite": "#73fa91"

    }
  }
}
```
