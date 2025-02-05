# 🚀 Maelyn API  

**Maelyn API** adalah layanan **REST API** yang dirancang untuk mendukung pengembangan aplikasi modern dengan berbagai fitur canggih. Kami menyediakan akses ke **data terkini, pemrosesan AI,** dan **integrasi mudah** untuk berbagai platform seperti **Bot WhatsApp, Discord, Telegram, dan lainnya.**  

## 🔹 Fitur Utama  
- ✅ **Akses cepat & stabil**  
- ✅ **Berbagai endpoint bermanfaat**  
- ✅ **Gratis hingga 20 permintaan/hari**  
- ✅ **Paket Premium untuk akses tanpa batas**  
- ✅ **Dukungan untuk berbagai bahasa pemrograman**  

## 📌 Penggunaan  
Untuk mulai menggunakan **Maelyn API**, daftarkan akun dan dapatkan **API Key** Anda di website resmi kami:  

🔗 **[Maelyn API - Daftar Sekarang](https://maelyn.tech)**  

## 📦 Instalasi via npm  
Kami menyediakan paket **npm** untuk memudahkan integrasi dengan **Node.js**. Anda bisa menginstalnya dengan perintah berikut:  

```sh
npm install maelyn.js
```

🔧 Contoh Penggunaan Geminichat API

Gunakan API ini untuk mengakses fitur AI dari Geminichat:
```javascript
const Maelyn = require('maelyn.js');

const api = new Maelyn('YOUR-APIKEY'); // Ganti dengan API Key Anda

api.get('geminichat', { q: 'Apa itu Maelyn API?' })
  .then(response => {
    console.log(response); // Menampilkan respons dari AI
  })
  .catch(error => {
    console.error(error); // Menangani error jika terjadi
  });
```
📤 Upload File ke CDN

Anda bisa mengunggah file ke CDN Maelyn tanpa memerlukan API Key:
```javascript
const Maelyn = require('maelyn.js');

const api = new Maelyn(); // Tidak memerlukan API key untuk upload file

api.uploadFile('path/to/your/file.jpg')  // Ganti dengan path file yang ingin diunggah
  .then(response => {
    console.log('File berhasil diunggah:', response); // Menampilkan URL file
  })
  .catch(error => {
    console.error('Gagal mengunggah file:', error.message); // Menangani error
  });
```
📦 Lihat di npmjs.com [maelyn.js](https://www.npmjs.com/package/maelyn.js)

📞 Dukungan & Bantuan
Jika Anda mengalami kendala atau memiliki pertanyaan, silakan hubungi tim kami:
📢 Channel WhatsApp : [Join Sekarang](https://s.id/MaelynChannel)

📢 Gunakan Maelyn API sekarang dan tingkatkan proyek Anda! 🚀
