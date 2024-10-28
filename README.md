<div align="center">
  <h1>🌱 Aplikasi Monitoring Stunting</h1>
  <p>
    <a href="https://github.com/BelajarPyramidReact/web_stunting/stargazers">
      <img alt="GitHub stars" src="https://img.shields.io/github/stars/BelajarPyramidReact/web_stunting?style=for-the-badge">
    </a>
    <a href="https://github.com/BelajarPyramidReact/web_stunting/network">
      <img alt="GitHub forks" src="https://img.shields.io/github/forks/BelajarPyramidReact/web_stunting?style=for-the-badge">
    </a>
    <a href="https://github.com/BelajarPyramidReact/web_stunting/issues">
      <img alt="GitHub issues" src="https://img.shields.io/github/issues/BelajarPyramidReact/web_stunting?style=for-the-badge">
    </a>
  </p>
  <div align="center">
  <img src="https://via.placeholder.com/800x400" alt="Stunting App Preview">
</div>
  <p>Solusi modern untuk monitoring dan pendataan kasus stunting berbasis web 🚀</p>
</div>


## ✨ Fitur Utama

<table>
  <tr>
    <td>
      <h3>📝 Pendataan Anak</h3>
      <ul>
        <li>Manajemen data anak komprehensif</li>
        <li>Form pendaftaran interaktif</li>
        <li>Pencarian & filter data</li>
      </ul>
    </td>
    <td>
      <h3>📊 Antropometri</h3>
      <ul>
        <li>Tracking pertumbuhan real-time</li>
        <li>Visualisasi grafik interaktif</li>
        <li>Export laporan PDF</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <h3>🏥 Riwayat Kesehatan</h3>
      <ul>
        <li>Pencatatan imunisasi</li>
        <li>Tracking vaksinasi</li>
        <li>Histori kesehatan lengkap</li>
      </ul>
    </td>
    <td>
      <h3>📈 Analisis & Laporan</h3>
      <ul>
        <li>Dashboard analitik</li>
        <li>Laporan berkala</li>
        <li>Statistik pertumbuhan</li>
      </ul>
    </td>
  </tr>
</table>

## 🏗️ Arsitektur

Proyek ini menggunakan repository dengan dua submodule utama:

```
web_stunting/
├── web_stunting_be/     # Backend service (Python Pyramid)
└── web_stunting_fe/     # Frontend app (React)
```

### 🔧 Tech Stack

<table>
  <tr>
    <td>Frontend</td>
    <td>Backend</td>
    <td>Database</td>
  </tr>
  <tr>
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
    </td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
      <img src="https://img.shields.io/badge/Pyramid-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen">
    </td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
    </td>
  </tr>
</table>

## 🚀 Quick Start

### Clone Repository & Submodules

```bash
# Clone main repository
git clone https://github.com/BelajarPyramidReact/web_stunting.git

# Initialize and update submodules
cd web_stunting
git submodule init
git submodule update
```

### Backend Setup

```bash
cd web_stunting_be

# Create virtual environment
python -m venv env
source env/bin/activate  # Linux/Mac
env\Scripts\activate     # Windows

# Install dependencies
pip install -e .

# Configure database
alembic upgrade head

# Run development server
pserve development.ini
```

### Frontend Setup

```bash
cd web_stunting_fe

# Install dependencies
npm install

# Run development server
npm run dev
```

## 🌐 API Documentation

<details>
<summary>📚 Available Endpoints</summary>

Untuk melihat koleksi lengkap JSON Postman, kunjungi [tautan ini](https://drive.google.com/file/d/1vwPRItBOWfLd9sPXDddndqM4LwjHuov_/view?usp=sharing).

</details>

---

<div align="center">
  Thank You For Your Contributtions
</div>
