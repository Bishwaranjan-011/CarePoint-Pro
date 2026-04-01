# 🏥 CarePoint PRO - Hospital Management System

A full-stack **Hospital Management System** built using **.NET Web API** and **React.js**. This application helps manage patients, doctors, and appointments with a modern UI and efficient backend.

---

## 🚀 Features

### 🔐 Authentication

* Secure login system (JWT-based)
* Role-based access (Admin)

---

### 👨‍⚕️ Doctors Management

* View all doctors
* Add new doctors
* Filter/search doctors by name or specialization

---

### 🧑‍🤝‍🧑 Patients Management

* Register new patients
* View patient list
* Search/filter patients by name
* Delete patient records

---

### 📅 Appointments

* Create appointments
* View appointment list
* Track appointment trends (analytics graph)
* Fix/Schedule appointments
* Filter appointments by date or patient

---

### 📊 Dashboard (Analytics)

* Total Doctors count
* Total Patients count
* Total Appointments count
* Appointment trends visualization
* Quick action panel

---

### 🎯 Additional Features

* Responsive UI design
* Clean and modern dashboard layout
* Real-time data updates
* Error handling (API + UI)
* Search and filter functionality

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Bootstrap
* Axios
* Lucide Icons

### Backend

* ASP.NET Core Web API
* Entity Framework Core
* SQL Server

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/hospital-management-system.git
cd hospital-management-system
```

---

### 2️⃣ Backend Setup (.NET API)

```bash
cd HospitalAPI
dotnet restore
dotnet run
```

* Update your **connection string** in `appsettings.json`
* Apply migrations if needed:

```bash
dotnet ef database update
```

---

### 3️⃣ Frontend Setup (React)

```bash
cd frontend
npm install
npm run dev
```

---

## 🔗 API Endpoints

### Patients

* `GET /api/Patients` → Get all patients
* `POST /api/Patients` → Add new patient
* `DELETE /api/Patients/{id}` → Delete patient

### Doctors

* `GET /api/Doctors`
* `POST /api/Doctors`

### Appointments

* `GET /api/Appointments`
* `POST /api/Appointments`

---

## 📸 Screenshots

### Dashboard

* Shows analytics and trends
 <img width="1365" height="630" alt="image" src="https://github.com/user-attachments/assets/f445d93d-c877-47e4-bb93-644ad1940dd8" />

### Patients Page

* Patient registry with search & delete
 <img width="1365" height="633" alt="image" src="https://github.com/user-attachments/assets/d776046d-0e3b-406a-9a21-5b06cd45915a" />


### Doctors Page

* Doctor management with filtering
 <img width="1365" height="624" alt="image" src="https://github.com/user-attachments/assets/09c42bd9-f2de-4490-aa34-c8c349c9daca" />


### Appointment Page
* Fixing Appointments
<img width="1365" height="627" alt="image" src="https://github.com/user-attachments/assets/c118ea58-97f4-413a-8308-ed7125f282bb" />

---

## 🔒 Authentication Note

* Some APIs require JWT token
* Store token in `localStorage` and send via headers:

```js
Authorization: Bearer <token>
```


---

## 👨‍💻 Author

**Bishwa Ranjan Das**

---

## ⭐ Conclusion

This project demonstrates a complete **CRUD-based full-stack application** with real-world features like authentication, filtering, analytics, and API integration.

---

👉 If you like this project, give it a ⭐ on GitHub!
