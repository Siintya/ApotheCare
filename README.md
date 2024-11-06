# ApotheCare
ApotheCare is a modern online pharmacy platform built with Laravel. Designed to offer a seamless experience for both customers and pharmacy administrators, ApotheCare ensures that essential medicines are just a few clicks away.

## How to install Laravel 11 on Ubuntu 20.04
1. Install PHP & Composer
    Sebelum membuat aplikasi Laravel, pastikan telah menginstal PHP dan Composer, jika belum menginstal PHP dan Composer, perintah berikut akan menginstal PHP, Composer:
    ```bash
    /bin/bash -c "$(curl -fsSL https://php.new/install/linux)"
    ```
2. Instal Laravel 11 dengan `composer create-project`
    Gunakan perintah berikut untuk membuat proyek Laravel 11 secara langsung:
    ```bash
    composer create-project --prefer-dist laravel/laravel apps "11.*"
    ```
3. Verifikasi Versi Laravel di Proyek
    Setelah instalasi selesai, masuk ke direktori proyek dan verifikasi versi Laravel:
    ```bash
    cd apps
    php artisan --version
    ```
    The results! `Laravel Framework 11.30.0`