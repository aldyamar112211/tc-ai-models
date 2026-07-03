# TC AI Models

Kumpulan model AI open-source yang dipakai fitur **Upscale Gambar** di TC Mobile.

Semua model di sini bersumber dari proyek open-source publik (Real-ESRGAN, Real-CUGAN, dkk),
dikonversi ke format yang bisa dijalankan langsung di HP (on-device inference).
Repo ini terpisah dari source code utama TC Mobile, murni sebagai tempat host file model
supaya ukuran aplikasi tetap kecil (model didownload sesuai kebutuhan user, bukan dibundel di APK).

## Sumber model

| Model | Sumber asli |
|---|---|
| Real-ESRGAN x4 / anime | [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) |
| Real-ESRGAN v2/v3 anime | [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) |
| Nomos8kSC | [Phhofm/models](https://github.com/Phhofm/models) |
| SourceBook | [tumuyan/SourceBook-Dataset](https://github.com/tumuyan/SourceBook-Dataset) |
| MoeSR | luoyily (komunitas) |
| Real-CUGAN | [bilibili/ailab](https://github.com/bilibili/ailab) |

Model diambil ke [Releases](../../releases) repo ini, bukan disimpan langsung di source tree.
