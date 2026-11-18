# 🚗 Vehicle Rental Web Application

A web-based vehicle rental management system developed as a group project for the **Software Engineering** course. This application facilitates online vehicle reservations for tenants, streamlines appointment execution for field workers, and enables administrators to manage fleets, registration forms, and payment approvals efficiently.

---

## 👥 Team Members

| No | Full Name | Student ID | Role | GitHub Account |
| :--- | :--- | :--- | :--- | :--- 
| 1 | Muhamad Alfaizi Absaeni | `001202500035` | Database & QA Testing | [@alfaiziabsaeni-art](https://github.com/alfaiziabsaeni-art) |
| 2 | Sadam Rivaldi Saputro | `001202500062` | Backend Developer | [@sadamrs](https://github.com/sadamrs) |
| 3 | Farrel Manggala Akbar Irawan | `001202500028` | Frontend Developer (Tenant / Public Page) | [@Aluphie](https://github.com/farrelmanggala0-oss) |
| 4 | Kevin Linanta | `Student ID 4` | Frontend Developer (Admin & Field Worker Page) | [@username4](https://github.com/username4) |

---

## 🛠️ Tech Stack

* **Backend Framework:** Laravel (PHP)
* **Authentication:** Laravel Breeze (Multi-role middleware: `tenant`, `admin`, `fieldworker`)
* **Frontend:** Blade Templates, Tailwind CSS / Bootstrap *(adjust as needed)*
* **Database:** MySQL
* **Version Control:** Git & GitHub

---

## ✨ Key Features

### 👤 Tenant (Customer)
* **Authentication & Registration Form:** Account login/registration and tenant registration form submission.
* **Vehicle Catalog:** Browse available vehicles with detailed specifications and daily rental rates.
* **Appointment Booking:** Schedule vehicle rental appointments (`makeAppointment`) with automated schedule conflict validation.
* **Payment & Receipt:** Submit rental payments, view booking history, and generate digital rental receipts.

### 🛡️ Admin
* **Admin Dashboard:** Overview of fleet status, appointments, and incoming payments.
* **Vehicle Management:** Full CRUD operations for vehicle data, pricing, and unit status.
* **Registration Form Management:** Manage, edit, and validate tenant registration form records.
* **Appointment & Payment Approval:** Oversee scheduled appointments and approve or reject tenant payments.

### 🔧 Field Worker
* **Vehicle Availability Check:** Inspect real-time vehicle readiness and unit availability.
* **Appointment Execution:** View assigned schedules and process/complete vehicle handover appointments (`doAppointment`).

---

## ⚙️ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/alfaiziabsaeni-art/vehicle-rental-web.git](https://github.com/alfaiziabsaeni-art/vehicle-rental-web.git)
   cd vehicle-rental-web
