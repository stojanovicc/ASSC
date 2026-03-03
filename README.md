# 🏆 ASSC – Aplikacija Studentski Sportski Centar 

Full-stack web aplikacija za upravljanje treninzima, takmičenjima, timovima i članarinama u okviru studentskog sportskog centra.

---

## 📌 Project Overview

ASSC (Aplikacija Studentskog Sportskog Centra) je web sistem koji omogućava digitalizaciju rada sportskog centra kroz jedinstvenu platformu sa više korisničkih uloga.

Sistem omogućava:

- Upravljanje treninzima
- Prijavu na takmičenja
- Formiranje timova
- Evidenciju članarina
- Role-based pristup funkcionalnostima

---

## 🏗️ System Architecture

Aplikacija je implementirana kao client-server sistem:

- **Backend:** ASP.NET Core (REST API)
- **Frontend:** React (Single Page Application)
- **Database:** Microsoft SQL Server
- **ORM:** Entity Framework Core
- **Authentication:** ASP.NET Core Identity
- **Authorization:** Role-based access control

---

## 👥 User Roles

### 👤 Visitor
- Pregled sportova
- Pregled trenera
- Pregled takmičenja

### 🎓 Student
- Registracija i prijava
- Izmena profila
- Zakazivanje treninga
- Otkazivanje treninga
- Prijava na takmičenje
- Odustajanje od takmičenja
- Učlanjivanje u tim
- Ispisivanje iz tima
- Plaćanje članarine
- Pregled istorije uplata

### 🏋️ Trainer
- Dodavanje termina treninga
- Ažuriranje treninga
- Brisanje treninga
- Pregled studenata koji su zakazali trening
- Formiranje timova
- Pregled članova tima

### 🏢 Employee
- Dodavanje takmičenja
- Izmena takmičenja
- Pregled prijavljenih studenata
- Dodavanje članarina
- Evidencija uplata
- Pregled studenata koji su platili članarinu

---

## 🔐 Security

- ASP.NET Core Identity
- Role-based authorization (Student / Trainer / Employee)
- Zaštićeni API endpointi
- Validacija podataka na backend-u

---

## 🧰 Technologies

### Backend
- C#
- ASP.NET Core Web API
- Entity Framework Core
- ASP.NET Core Identity

### Frontend
- React
- JavaScript
- React Hooks (useState, useEffect)

### Database
- Microsoft SQL Server

---

## ⚙️ Running the Application

### 🔹 Backend

```bash
cd backend
dotnet restore
dotnet run

---

## 👩‍💻 Autori
- Anđela Stojanović
- Anastasija Trajković
