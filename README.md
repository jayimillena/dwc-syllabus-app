# Laravel Syllabus Generator — Starter Scaffold


## Requirements


- PHP >= 8.1
- Composer
- Laravel 10 (recommended)
- ext-zip, ext-xml, ext-mbstring enabled


Install PHPWord:


```bash
composer require phpoffice/phpword
```


---


## Installation (short)


1. Create a new Laravel project (or use existing):


```bash
composer create-project laravel/laravel syllabus-app
cd syllabus-app
```


2. Add PHPWord:


```bash
composer require phpoffice/phpword
```


3. Place your template `OVPAA-Form-005-SYLLABUS-Template.docx` into `storage/app/templates/`.


4. Copy the files below into the matching locations.


5. Run migration:


```bash
php artisan migrate
```


6. Make storage link (for downloads if needed):


```bash
php artisan storage:link
```


7. Serve app:


```bash
php artisan serve
```