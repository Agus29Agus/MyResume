## Tentang Aplikasi
```
Aplikasi Personal Page ini berguna untuk anda yang sedang mencoba membuat sebuah CV dalam bentuk website laravel
```

## Tahapan instalasi :
#### Via Git
```bash
git clone https://github.com/Agus29Agus/MyResume.git
```

### Setup
1. Jalankan Perintah di terminal directory anda
```bash
composer install
```

2. Copy file .env dari .env.example
```bash
cp .env.example .env
```

3. Generate key
```bash
php artisan key:generate
```

4. Run Server
```bash
php artisan serve
```
5. Go to the url
```bash
http://localhost:8000/personal.page
```
## Edit
Edit your personal page on
```
resources > views > personalpage.blade.php
```

## License

[MIT license](https://opensource.org/licenses/MIT)

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
