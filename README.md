sentiment analysis pejabat vs influencer bencana banjir sumatra

📊 Sentimen Publik: Pejabat vs Influencer
Analisis Persepsi Digital terhadap Zulkifli Hasan dan Ferry Irawan dalam masa penangganan korban banjir sumatra 2025

Zulkifli Hasan: Menteri Perdagangan, tokoh politik senior (Partai PAN)
Ferry Irawan: Influencer & figur media sosial (Pendiri malaka project)
Melalui pendekatan berbasis data, proyek ini bertujuan memahami bagaimana masyarakat digital merespons kedua tokoh dalam masa penangganan korban banjir sumatra 2025

🔍 Metodologi
Sumber Data:
Data dikumpulkan melalui web scraping dari komentar di platform media sosial (Tiktok, Instagram, YouTube) dan situs berita daring (Masa Bencana Banjir Sumatra 2025).
Pendekatan Analisis:
Menggunakan metode lexicon-based sentiment analysis yang dikhususkan untuk bahasa Indonesia, dengan referensi utama:
InSet (Indonesian Sentiment Lexicon) oleh Fajri Koto
Penyesuaian manual untuk entitas bernama dan frasa kontekstual terkait kedua tokoh
Klasifikasi Sentimen:
Setiap komentar diklasifikasikan sebagai Positif, Negatif, atau Netral berdasarkan skor selisih antara kata positif dan negatif yang muncul.
Praproses Teks:
Termasuk normalisasi, penghapusan noise (URL, mention, emoji), dan stemming menggunakan library Sastrawi.

📁 Struktur Proyek
.
├── data/                   
├── scraping/               # Script untuk mengumpulkan komentar dari sumber publik
├── preprocessing/          # Pembersihan dan normalisasi teks bahasa Indonesia
├── analysis/               # Skrip analisis sentimen (lexicon-based)
├── visualization/          # Word cloud, bar chart, dan distribusi sentimen
├── presentation/           # Slide presentasi (PDF/PPTX) –
└── README.

🛠️ Teknologi yang Digunakan
Python 3.x
Library: pandas, requests, BeautifulSoup, Sastrawi, matplotlib, wordcloud
Lexicon: InSet (positive.tsv & negative.tsv)

🌱 Tujuan & Nilai Proyek
Meningkatkan literasi data dalam memahami opini publik
Menunjukkan penerapan NLP untuk konteks lokal (bahasa Indonesia)
Menjadi referensi terbuka bagi praktisi data pemula yang ingin belajar end-to-end sentiment analysis
📣 Ingin Bertanya & beri masukan?
Silakan buka issue atau kirim DM di LinkedIn! Saya terbuka untuk diskusi tentang metodologi, etika scraping, atau pengembangan model sentimen untuk bahasa Indonesia.
my linkidin : www.linkedin.com/in/abdullah-azzam-taufiq-alammar-83ab4224b 
