# Selamat Datang di Github IT BBSPJPPI!
<img src="../assets/8.png" alt="greeni" width="200">

Tempat ini digunakan sebagai wadah untuk meletakkan kode proyek internal BBSPJPPI (non-SPBE).

## Repository Rules

Setiap repository minimal **WAJIB** mengikuti aturan berikut:

### 1. Feature Branching
- Gunakan branch utama: `main`
- Setiap pengembangan fitur/modul baru dilakukan di branch terpisah  
  Contoh: `fitur/login`, `fitur/etl`
- Merge ke `main` hanya melalui Pull Request yang akan di review ke @givxl33t

### 2. Automated Deployment Pipeline
- Setiap repository harus memiliki pipeline CI/CD
- Pipeline minimal mencakup:
  - Build
  - Test
  - Deploy otomatis
- Pipeline berjalan otomatis saat ada perubahan ke branch `main`

## Goal
Menjaga kualitas kode, konsistensi workflow, dan proses deployment yang cepat serta andal.
