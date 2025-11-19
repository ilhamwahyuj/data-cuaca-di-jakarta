# Data cuaca di jakarta

# 🌤️ Aplikasi Data Cuaca Jakarta – Open-Meteo API

Aplikasi web sederhana yang dibuat menggunakan **HTML**, **JavaScript**, dan **Tailwind CSS** untuk menampilkan data cuaca per jam di Jakarta.
Aplikasi ini mengambil data cuaca secara real-time dari **Open-Meteo API**, memprosesnya, dan menampilkannya dalam bentuk tabel yang rapi dan responsif.

---

## 🚀 Fitur Utama

* Mengambil data prakiraan cuaca secara langsung dari Open-Meteo
* Menampilkan dua kolom data:

  * **time** (waktu pengukuran)
  * **temperature_2m** (suhu per jam dalam °C)
* Menampilkan **10 data pertama** agar lebih mudah dibaca
* Tampilan modern menggunakan **Tailwind CSS**
* Responsif dan dapat diakses melalui browser tanpa instalasi tambahan
* Tidak memerlukan backend (sepenuhnya berjalan di sisi client)

---

## 🛠️ Teknologi yang Digunakan

* **HTML5**
* **JavaScript (Fetch API)**
* **Tailwind CSS (CDN)**
* **Open-Meteo Weather API**

---

## 📦 Cara Kerja Aplikasi

1. Aplikasi mengirim request HTTP ke API Open-Meteo.
2. API mengembalikan data cuaca per jam dalam format JSON.
3. JavaScript mengambil data **time** dan **temperature_2m** dari respons API.
4. Aplikasi membuat baris tabel secara dinamis menggunakan DOM Manipulation.
5. Tabel menampilkan 10 data pertama dengan tampilan yang bersih dan mudah dibaca.

---

## 📍 API Endpoint yang Digunakan

```
https://api.open-meteo.com/v1/forecast?latitude=-6.2&longitude=106.8&hourly=temperature_2m
```

---

## 📄 Lisensi

Proyek ini bersifat open-source dan dapat digunakan untuk keperluan pembelajaran maupun proyek pribadi.
