# AIPedia

**[aipedia.ai.id](https://aipedia.ai.id)** — berita, tutorial, dan analisis AI berbahasa Indonesia.

AIPedia menulis untuk pembaca Indonesia yang butuh memahami AI secara praktis: bukan
kumpulan siaran pers, tapi penjelasan yang bisa dipakai. Setiap artikel ditulis dalam
Bahasa Indonesia, memakai contoh dari konteks lokal (Rupiah, regulasi Indonesia, data
transaksi dan dokumen berbahasa Indonesia), dan menyertakan bagian **Referensi** di akhir.

## Kategori

| Kategori | Isi | URL |
|---|---|---|
| Berita | Perkembangan dan peristiwa AI | https://aipedia.ai.id/news |
| Tools | Ulasan dan perbandingan alat AI | https://aipedia.ai.id/tools |
| Tutorial | Panduan langkah demi langkah | https://aipedia.ai.id/tutorials |
| Agents | Sistem agentik dan orkestrasi | https://aipedia.ai.id/agents |
| Models | Model, arsitektur, dan inferensi | https://aipedia.ai.id/models |
| Developers | Implementasi API, evaluasi, keamanan | https://aipedia.ai.id/developers |
| Insights | Analisis dan opini berbasis bukti | https://aipedia.ai.id/insights |
| Learn | Dasar-dasar AI untuk pemula | https://aipedia.ai.id/learn |

## Feed dan endpoint publik

- Sitemap: https://aipedia.ai.id/sitemap.xml
- RSS: https://aipedia.ai.id/rss.xml
- `llms.txt`: https://aipedia.ai.id/llms.txt
- `robots.txt`: https://aipedia.ai.id/robots.txt

Konten boleh diindeks mesin pencari. Pelatihan model AI tidak diizinkan — lihat
[`robots.txt`](https://aipedia.ai.id/robots.txt) untuk deklarasi *Content-Signal*.

## Standar editorial

Kebijakan redaksi lengkap: https://aipedia.ai.id/editorial-policy

Ringkasnya:

- Setiap artikel punya bagian **Referensi** dengan tautan ke sumber primer.
- Klaim angka dan tanggal harus bisa dilacak ke sumbernya; yang belum terverifikasi
  ditandai sebagai batasan, bukan diklaim sebagai fakta.
- Artikel yang menyebut produk pihak ketiga tidak disponsori kecuali dinyatakan jelas.
- Koreksi ditulis terbuka di artikel yang bersangkutan.

## Teknis

Situs berjalan di Cloudflare Workers dengan CMS EmDash (D1 + R2), dibangun dengan Astro.
Rute artikel: `/posts/{slug}`. Semua halaman memakai `lang="id"`, canonical absolut, dan
data terstruktur `Organization`, `WebSite`, `BlogPosting`, serta `BreadcrumbList`.

## Kontak

- Koreksi dan masukan: https://aipedia.ai.id/contact
- Kebijakan privasi: https://aipedia.ai.id/privacy-policy
- Ketentuan: https://aipedia.ai.id/terms
