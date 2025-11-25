# 🛡️ Anti Porn Filter List

**Filter List untuk memblokir situs pornografi – kompatibel dengan Brave Browser, uBlock Origin, AdGuard, dan sistem penyaring konten lainnya.**

Proyek ini menyediakan daftar blokir untuk menjaga keamanan keluarga, sekolah, kantor, dan jaringan publik dari akses ke situs-situs dewasa.
Filter disusun dengan rapi, ringan, dan mudah digunakan.

---

## ✨ Fitur Utama

* 🔒 **Memblokir ribuan situs pornografi internasional & lokal**
* ⚡ **Ringan dan efisien**, tidak membebani performa browser
* 🧩 **Kompatibel dengan berbagai platform**

  * uBlock Origin
  * AdGuard
  * AdBlock / AdBlock Plus
  * Brave Browser 
   
* 📦 **Format murni ABP / AdBlock Syntax (`$doc`)**
* 🔄 **Update berkala** penambahan domain baru

---

## 📥 Cara Menggunakan

### **uBlock Origin / AdGuard /  Brave**

Tambahkan URL berikut pada bagian **Custom Filter List**:

```
https://cdn.jsdelivr.net/gh/richie3011/pornshield-blocklist@refs/heads/main/adult_blocklist.txt
```
---

## 🔐 Rekomendasi Penggunaan

Filter ini dirancang agar **melengkapi sistem DNS Family Filter** seperti *Clean Browsing – Family Filter*, *AdGuard DNS Family*, serta layanan DNS penyaring konten lainnya.

Untuk perlindungan maksimal pada browser, sangat direkomendasikan juga menggunakan **ekstensi adblocker** seperti:

* **AdGuard Extension**
* **uBlock Origin**

Kombinasi DNS Family Filter + AdBlock Extension akan memberikan keamanan terbaik karena mampu memblokir konten dewasa di tingkat DNS sekaligus mencegah akses melalui browser.

---

## 🛠️ Kontribusi

Kontribusi sangat terbuka!
Anda dapat membantu dengan:

* Mengirim domain baru
* Menghapus domain salah deteksi
* Mengurangi duplikasi
* Membersihkan struktur list

Gunakan **Issue** atau **Pull Request** untuk kontribusi.

---

## ⚠️ Disclaimer

* Blocklist ini dibuat untuk **perlindungan** dan **pencegahan akses konten dewasa**.
Tidak ditujukan untuk sensor politik, pelacakan, atau aktivitas yang melanggar hukum.

* > Filter regex dalam daftar ini **mungkin tidak bekerja optimal di Brave Browser**.  
> Hal ini karena Brave menggunakan bahasa Rust untuk implementasi AdBlock-nya, sehingga beberapa regex kompleks bisa tidak dikenali.Saat ini syntax $doc bekerja optimal di Brave browser 

---

## ⭐ Dukung Proyek Ini

Jika repo ini bermanfaat, mohon berikan **star ⭐ di GitHub** agar proyek terus berkembang.
