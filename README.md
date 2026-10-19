# GRC E-commerce

GRC Material Hub — katalog material, estimator kebutuhan, panduan teknis, dan permintaan penawaran melalui WhatsApp.

## Prinsip deployment

Proyek ini ditargetkan **Rp0** untuk tahap awal:

- Repository: GitHub
- Hosting publik: GitHub Pages
- Frontend: HTML/CSS/JavaScript statis
- Order/quotation awal: WhatsApp
- AI Companion: mode pengetahuan tertanam/rule-based pada GitHub Pages; mendukung chat teks, pembacaan jawaban melalui Speech Synthesis, dan input suara jika browser mendukung Web Speech API
- Basis pengetahuan awal: `knowledge/muria-arch-ai-knowledge.json` (GRC/GFRC, kerawangan custom, data penawaran, harga, finishing, kubah, lisplang, pemasangan, perawatan, dan batas keselamatan)
- Literatur rujukan awal: GRCA technical publications/FAQs/technical notes dan PCI MNL-128 serta ANSI/PCI 128-24; tautan ada dalam basis pengetahuan
- Mode versi ini tidak memakai model AI cloud dan tidak menyimpan percakapan ke server. Jawaban dibentuk dari basis pengetahuan tertanam; pertanyaan di luar cakupan harus dikonfirmasi tim Muria-Arch.
- Tidak bergantung pada Hatchable untuk hosting publik
- Tidak memerlukan VPS, database berbayar, atau API AI berbayar

## GitHub Pages

Repository ini disiapkan untuk GitHub Pages. Setelah workflow dibuat, aktifkan:

**Settings → Pages → Build and deployment → Source: GitHub Actions**

URL proyek setelah aktif:

https://yudi8377.github.io/GRC-E-commerce/

## Data commerce

Form permintaan penawaran membuat Order ID dan pesan WhatsApp terstruktur. Tahap berikutnya dapat menambahkan penyimpanan lead/order menggunakan layanan gratis atau backend open-source, tetapi tidak menjadi syarat untuk website publik versi Rp0.

## Catatan aset

Visual pada versi GitHub saat ini menggunakan ilustrasi SVG generik agar tidak membawa aset pihak ketiga tanpa verifikasi lisensi. Foto produk/proyek berlisensi dapat ditambahkan kemudian.
