# Laravel Syllabus Generator — Starter Scaffold

![Laravel](https://img.shields.io/badge/Laravel-10-red?style=flat-square)
![PHP](https://img.shields.io/badge/PHP-8.1-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

**Author:** Jared Web Studio  
**Developer:** Jay Millena  
**Created:** November 1, 2025  
**Location:** Daraga, Albay, Philippines  

---

## Overview

Laravel Syllabus Generator is a starter scaffold for educators to generate, manage, and download syllabi efficiently. Using **Laravel 10** and **PHPWord**, this system leverages pre-defined DOCX templates for easy syllabus creation, helping start-ups or educational institutions streamline their document workflow.

---

## Features

- Generate syllabi from DOCX templates  
- Upload and manage templates easily  
- Download syllabi in Word format  
- Lightweight and easy to deploy  
- Quick setup for Laravel projects  

---

## Tech Stack

![Laravel](https://img.shields.io/badge/Laravel-10-red?style=flat-square)
![PHP](https://img.shields.io/badge/PHP-8.1-blue?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-8.0-lightblue?style=flat-square)
![PHPWord](https://img.shields.io/badge/PHPWord-1.0-orange?style=flat-square)
![Composer](https://img.shields.io/badge/Composer-2.6-blue?style=flat-square)

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/laravel-syllabus-generator.git
cd laravel-syllabus-generator
```

2. Install PHP dependencies:

```bash
composer install
```

3. Place your template:

- Add `OVPAA-Form-005-SYLLABUS-Template.docx` into `storage/app/templates/`.

4. Copy scaffold files into their corresponding locations.

5. Set up environment:

```bash
cp .env.example .env
php artisan key:generate
```

6. Run migrations:

```bash
php artisan migrate
```

7. Create storage link (for downloads):

```bash
php artisan storage:link
```

8. Serve the application:

```bash
php artisan serve
```

Visit [http://localhost:8000](http://localhost:8000) to use the app.

---

## Contribution

Contributions are welcome! You can:

- Report issues  
- Suggest features  
- Fork and improve the system  

Please respect the license and do not copy proprietary assets.

---

## License

MIT License — free to use, modify, and distribute for personal or educational purposes, excluding proprietary assets.

---

## Contact

**Developer:** Jay Millena  
**Organization:** Jared Web Studio  
**Location:** Daraga, Albay, Philippines