
Simulasi Interaktif Penyearah Terkontrol 1 Fasa (Konsep Thyristor)

Aplikasi web simulasi interaktif berbasis front-end untuk menghitung, menganalisis, dan memvisualisasikan parameter keluaran pada Penyearah Setengah Gelombang Terkontrol 1 Fasa dengan beban resistif murni (R). Proyek ini dirancang untuk menjembatani pemahaman teori matematika elektronika daya dengan visualisasi dunia nyata.
[KLIK DI SINI UNTUK MENCOBA SIMULASI SECARA LIVE](https://graha-learner.github.io/simulasi-thyristor/)

Latar Belakang Teori

Penyearah terkontrol menggunakan komponen SCR (Silicon Controlled Rectifier) atau Thyristor untuk mengubah tegangan AC menjadi DC, di mana momen mulainya konduksi dapat diatur melalui sudut picu (α).
Simulasi ini mengintegrasikan perhitungan matematis utama untuk menentukan performa penyearah:

1. Tegangan DC Rata-rata (Vdc)

Menghitung nilai tegangan rata-rata yang dihasilkan pada beban berdasarkan sudut picu α:
Vdc = (Vm / 2π) * (1 + cos α)

2. Tegangan Efektif RMS (Vrms)

Menghitung nilai efektif tegangan keluaran yang mengalir ke beban:
Vrms = Vm * Akar[ (π - α + 0.5 * sin 2α) / 4π ]

3. Rasio Daya Terhantar (P / P_maks)

Mengukur persentase daya yang berhasil disalurkan ke beban dibandingkan dengan daya maksimum saat keran SCR dibuka penuh (0°):
P / P_maks = (π - α + 0.5 * sin 2α) / π
Catatan: Nilai sudut picu (α) dalam perhitungan kalkulus di atas wajib dikonversi ke dalam satuan Radian.

🛠️ Fitur Utama Aplikasi

• Input Dinamis: Pengguna dapat memasukkan nilai Tegangan Puncak (Vm) dalam Volt dan Sudut Picu (α) dari 0° hingga 180°.
• Kalkulator Instan: Menghitung nilai Vdc, Vrms, dan persentase daya secara real-time saat nilai input diubah.
• Analogi visual: Mempermudah visualisasi kendali daya menggunakan parameter matematis yang akurat.

Proyek ini dikembangkan sebagai bentuk portofolio akademis dan penerapan praktis teknik elektronika daya.
