# OBE System Migration – Internship Project

This repository showcases the work I contributed during my internship at **PT. iGS Indonesia Groups** (Feb – Jul 2024). The main objective was to migrate an existing Outcome-Based Education (OBE) system from a web platform into a functional Android application.

---

## Project Scope

- **Backend Development**: Built RESTful APIs using Laravel.
- **Data Cleaning**: Normalized and refactored messy MySQL datasets from legacy systems.
- **Android App Migration**: Collaborated with Android developer team to shift web functionalities into mobile format.
- **Deployment**: Hosted the Laravel backend on a cloud environment for integration testing.

---

## My Role

As a backend engineer, I was responsible for:

- Building APIs
- Cleaning and restructuring the database
- Connecting backend to the Android app
- Deploying the Laravel project to shared hosting

---

## Tech Stack

- Laravel (PHP), MySQL
- Postman (API testing)
- Android Studio (Kotlin)
- Firebase (used in the Android build)
- GitHub (version control)

---

## Documentation

### Backend Preview (API Endpoints)

#### Screen 1: Authentication
- `POST /login`

#### Screen 2: Home Page
- `GET /user`
- `GET /halaman-utama-nama`
- `GET /halaman-utama-profile`

#### Screen 3: Course
- `GET /matkul`
- `GET /matkul/{id_matkul}/{id_pengampu}`

#### Screen 4: RPS & Evaluation Details
- `GET /detailrps/minggu/{id_matkul}`
- `GET /evaluasi/{id_matkul}/{id_detailrps}/{id_evaluasi}`
- `GET /subcpmk/{id_detailrps}`
- `POST /evaluasi`
- `PUT /evaluasi/{id_evaluasi}`
- `DELETE /evaluasi/{id_evaluasi}`

#### Screen 5: Student Assessment
- `GET /mahasiswa-by-matkul/{id_matkul}`
- `GET /evaluasi-mahasiswa-detail/{id_user}`
- `POST /evaluasi-mahasiswa-detail/{id_user}/{id_matkul}`
- `PUT /evaluasi-mahasiswa-detail/{id_user}/{id_matkul}/{id_evaluasimhs}`
- `DELETE /evaluasi-mahasiswa-detail/{id_user}/{id_matkul}/{id_evaluasimhs}`
- `POST /evaluasi_mahasiswa_hitung/{id_matkul}/{id_user}/{id_evaluasimhs}/{id_pengampu}`

#### Screen 6: CPL
- `GET /matkul-cpl/{userId}`
- `GET /total_cpl/{id_user}`

---

### Android UI (OBE App)  
![Android UI](assets/android_ui.png)

### Database ERD  
![Database ERD](assets/database_erd.png)

### Workflow  
![Workflow](assets/workflow.png)

---

## Disclaimer

This repository only contains documentation and non-sensitive assets. The source code cannot be published due to company policy and intellectual property protection.
