<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

In addition, [Laracasts](https://laracasts.com) contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

You can also watch bite-sized lessons with real-world projects on [Laravel Learn](https://laravel.com/learn), where you will be guided through building a Laravel application from scratch while learning PHP fundamentals.

## Agentic Development

Laravel's predictable structure and conventions make it ideal for AI coding agents like Claude Code, Cursor, and GitHub Copilot. Install [Laravel Boost](https://laravel.com/docs/ai) to supercharge your AI workflow:

```bash
composer require laravel/boost --dev

php artisan boost:install
```

Boost provides your agent 15+ tools and skills that help agents build Laravel applications while following best practices.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
# 🚗 Vehicle Rental Web Application

A web-based vehicle rental management system developed as a group project for the **Software Engineering** course. This application facilitates online vehicle reservations for tenants, streamlines appointment execution for field workers, and enables administrators to manage fleets, registration forms, and payment approvals efficiently.

---

## 👥 Team Members

| No | Full Name | Student ID | Role | GitHub Account |
| :--- | :--- | :--- | :--- | :--- 
| 1 | Muhamad Alfaizi Absaeni | `001202500035` | Database & QA Testing | [@alfaiziabsaeni-art](https://github.com/alfaiziabsaeni-art) |
| 2 | Sadam Rivaldi Saputro | `001202500062` | Backend Developer | [@sadamrs](https://github.com/sadamrs) |
| 3 | Farrel Manggala Akbar Irawan | `001202500028` | Frontend Developer (Tenant / Public Page) | [@Aluphie](https://github.com/farrelmanggala0-oss) |
| 4 | Kevin Linanta | `001202500092` | Frontend Developer (Admin & Field Worker Page) | [@Kevin]([https://github.com/username4](https://github.com/vinnlieee)) |

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
