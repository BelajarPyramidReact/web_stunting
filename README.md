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
  <img src="./assets/homepage.jpg" alt="Stunting App Preview">
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

## 💫 System Design

Dokumentasi desain sistem untuk Aplikasi Monitoring Stunting

### 🎯 Overview

<table>
  <tr>
    <td width="50%">
      <img src="https://via.placeholder.com/800x400" alt="System Overview" style="width:100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </td>
    <td width="50%" valign="top">
      <h4>Key Components</h4>
      <ul>
        <li>🔐 Authentication System</li>
        <li>📊 Data Management</li>
        <li>📈 Analytics Engine</li>
        <li>🔄 Real-time Updates</li>
      </ul>
    </td>
  </tr>
</table>

### 📊 System Flow

<div align="center">
  <img src="./assets/stunting_system_design.png" alt="System Flow" style="max-width: 800px; width: 100%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
</div>

### 🔄 Use Cases

<table>
  <tr>
    <td width="60%">
      <img src="./assets/stunting_usecase.png" alt="Use Case Diagram" style="width:100%; border-radius: 8px;">
    </td>
    <td width="40%" valign="top">
      <h4>Actor: Petugas Kesehatan</h4>
      <ul>
        <li>✍️ Pendaftaran Anak</li>
        <li>📏 Pengukuran Antropometri</li>
        <li>📋 Manajemen Riwayat Kesehatan</li>
        <li>📊 Analisis & Pelaporan</li>
      </ul>
    </td>
  </tr>
</table>

### 🔄 Activity Flows

<div class="grid grid-cols-2 gap-4">
  <div class="flow-card">
    <h4>📝 Pendaftaran Anak</h4>
    <img src="./assets/stunting_activity_1.png" alt="Activity - Registration">
  </div>
  <div class="flow-card">
    <h4>📏 Pengukuran Antropometri</h4>
    <img src="./assets/stunting_activity_2.png" alt="Activity - Antropometri">
  </div>
  <div class="flow-card">
    <h4>🏥 Riwayat Kesehatan</h4>
    <img src="/assets/stunting_activity_3.png" alt="Activity - Health History">
  </div>
  <div class="flow-card">
    <h4>📊 Analisis Data</h4>
    <img src="/assets/stunting_activity_4.png" alt="Activity - Data Analysis">
  </div>
</div>

### 🔄 Sequence Flows

<details>
<summary>📝 Pendaftaran Anak</summary>
<img src="/assets/stunting_sequence_1.png" alt="Sequence - Registration">
</details>

<details>
<summary>📏 Pengukuran Antropometri</summary>
<img src="/assets/stunting_sequence_2.png" alt="Sequence - Antropometri">
</details>

<details>
<summary>🏥 Riwayat Kesehatan</summary>
<img src="/assets/stunting_sequence_3.png" alt="Sequence - Health">
</details>

<details>
<summary>📊 Grafik Pertumbuhan</summary>
<img src="/assets/stunting_sequence_4.png" alt="Sequence - Graph">
</details>

### 📦 Data Model

<table>
  <tr>
    <td width="50%">
      <h4>Contoh Class Diagram</h4>
      <img src="./assets/stunting_class_1.png" alt="Class Diagram" style="width:100%;">
    </td>
    <td width="50%">
      <h4>Class Diagram Aplikasi Pendataan Stunting</h4>
      <img src="./assets/stunting_class_2.png" alt="ERD" style="width:100%;">
    </td>
  </tr>
</table>

### 🎨 UI/UX Design

<div class="grid grid-cols-2 gap-4">
  
  <div class="design-card">
    <h4>📝 Form Pendaftaran</h4>
    <img src="./assets/stunting_wireframe_1.png" alt="UI - Registration">
    <ul>
      <li>✨ Multi-step form</li>
      <li>🔄 Real-time validation</li>
      <li>📸 Photo upload</li>
    </ul>
  </div>
  
  <div class="design-card">
    <h4>📏 Antropometri</h4>
    <img src="./assets/stunting_wireframe_2.png" alt="UI - Antropometri">
    <ul>
      <li>📈 Interactive charts</li>
      <li>🔄 Real-time updates</li>
      <li>📊 Progress tracking</li>
    </ul>
  </div>
  
  <div class="design-card">
    <h4>🏥 Riwayat Kesehatan</h4>
    <img src="./assets/stunting_wireframe_3.png" alt="UI - Health History">
    <ul>
      <li>📅 Timeline view</li>
      <li>🔍 Advanced search</li>
      <li>📑 Document management</li>
    </ul>
  </div>
</div>

### 🔗 Data Relationships

```mermaid
graph LR
    PK[Petugas Kesehatan] --1:N--> A[Anak]
    A --1:N--> PA[Pengukuran Antropometri]
    A --1:1--> RK[Riwayat Kesehatan]
    RK --1:N--> I[Imunisasi]
```

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