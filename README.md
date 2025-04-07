# CapstoneModul2
# Analisis Segmentasi Listing Airbnb di Bangkok

📊 Proyek analisis bisnis dan data yang bertujuan untuk mengeksplorasi segmentasi listing Airbnb di Bangkok berdasarkan **harga** dan **tingkat okupansi**, dengan tujuan menghitung Potential Lost dan Opportunity Cost, beserta Return of Investement (ROI) memberikan **rekomendasi strategis** bagi pemilik properti dan tim regional Airbnb.

---

## 📁 Ringkasan Proyek

Proyek ini menganalisis dataset listing Airbnb di Bangkok dengan pendekatan segmentasi untuk mengidentifikasi peluang pendapatan dan potensi kerugian (revenue lost). Analisis difokuskan dari sudut pandang **pemilik properti (host)**, serta memberikan wawasan strategis untuk meningkatkan performa listing.

---

## 🎯 Tujuan

- Melakukan segmentasi listing berdasarkan **harga** dan **okupansi**.
- Mengidentifikasi wilayah (neighbourhood) dengan **kerugian pendapatan tertinggi**.
- Memberikan insight untuk **mengurangi potential lost**.
- Mendukung **pengambilan keputusan bisnis Airbnb** secara data-driven.

---

## 🔍 Segmentasi

Listing dibagi menjadi tiga segmen utama:

| Nama Segmen               | Deskripsi                                      |
|---------------------------|-----------------------------------------------|
| Low Price - Low Occupancy | Harga rendah dan okupansi rendah              |
| Low Price - High Occupancy| Harga rendah namun okupansi tinggi            |
| High Price - High Occupancy| Harga tinggi dan okupansi tinggi (ideal)    |

---

## 📊 Analisis Utama

- **Uji Hipotesis**: Menganalisis pengaruh harga terhadap potential lost pada 3 segmen.
- **Risk Zone per Wilayah**: Menyoroti 10 wilayah dengan kerugian rata-rata dan total tertinggi.
- **Dashboard Tableau**: Visualisasi interaktif untuk menyampaikan insight kepada stakeholder.

---

## 🧰 Tools yang Digunakan

- Python (Pandas, Seaborn, Matplotlib, SciPy)
- Jupyter Notebook (VsCode)
- Tableau Public
- GitHub

---

## 📂 Struktur Repository

```bash
├── data/
│   └── airbnb_bangkok_listings.csv
├── notebooks/
│   └── Airbnb Analysis.ipynb
├── dashboards/
│   └── https://public.tableau.com/views/DistribusiListingperSegmen/Dashboard2?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
├── PPT/
│   └── https://www.canva.com/design/DAGj06L5qSg/EQf5ZNmApmgQzIxV-h1Bew/edit
├── README.md
