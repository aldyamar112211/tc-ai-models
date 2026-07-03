# TC AI Models

Kumpulan model AI open-source yang dipakai fitur **Upscale Gambar** di TC Mobile,
sebuah aplikasi komunitas Roblox non-komersial.

Repo ini terpisah dari source code utama TC Mobile, murni sebagai tempat host file model
supaya ukuran aplikasi tetap kecil. Model didownload sesuai kebutuhan user, bukan dibundel di APK.

## Asal file

File `.bin`/`.param` (format NCNN) dan `.mnn` di [Releases](../../releases) repo ini diambil dari
aplikasi Android open-source [tumuyan/RealSR-NCNN-Android](https://github.com/tumuyan/RealSR-NCNN-Android),
yang mengompilasi dan mengemas ulang model-model di bawah ini ke format NCNN/MNN siap pakai di HP.
Kami tidak melakukan konversi sendiri dari bobot model aslinya, kredit proses konversi ke NCNN
sepenuhnya milik tumuyan.

## Kredit model asli

Setiap model berikut adalah hasil kerja tim/individu di bawah ini. Tanpa mereka, fitur ini tidak akan ada.

| Model di app | Model asli | Pembuat | Sumber |
|---|---|---|---|
| Upscale Foto 4x | Real-ESRGAN x4plus | xinntao | [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) |
| Upscale Foto Cepat | realesr-general-x4v3 | xinntao | [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) |
| Upscale Foto HD Detail | 4xNomos8kSC | Phhofm | [Phhofm/models](https://github.com/Phhofm/models) (CC BY 4.0) |
| Perjelas Scan Buku/Teks | SourceBook 2x | tumuyan | [SourceBook-Dataset](https://github.com/tumuyan/SourceBook-Dataset) |
| Upscale Anime | Real-ESRGAN x4plus-anime | xinntao | [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) |
| Upscale Anime (Ringan) | RealESRGANv2-animevideo | xinntao | [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) |
| Upscale Anime Cepat | realesr-animevideov3 | xinntao | [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) |
| Upscale Ilustrasi/Artwork | MoeSR ESRGAN jp_Illustration | luoyily / TeamMoeAI | tidak ada repo resmi publik, model diambil apa adanya dari kemasan tumuyan |
| Upscale Anime Pro | Real-CUGAN | bilibili/ailab | [bilibili/ailab](https://github.com/bilibili/ailab) (MIT License) |

**Catatan lisensi:** 4xNomos8kSC berlisensi CC BY 4.0, kredit ke Phhofm wajib disertakan
(tabel di atas berfungsi sebagai atribusi tersebut). Real-CUGAN berlisensi MIT.
Model lain dari xinntao/Real-ESRGAN berlisensi BSD 3-Clause.

## Skala kecil, non-komersial

Aplikasi TC Mobile adalah proyek komunitas Roblox, tidak didistribusikan lewat Play Store,
dan tidak dikomersialkan. Repo ini dibuat untuk memudahkan hosting file model saja.
Kalau ada pemilik model yang keberatan filenya dipakai di sini, silakan buka issue,
akan langsung ditindaklanjuti.
