# Semart Skeleton

[![Build Status](https://travis-ci.org/KejawenLab/SemartSkeleton.svg?branch=master)](https://travis-ci.org/KejawenLab/SemartSkeleton)
[![Coverage Status](https://coveralls.io/repos/github/KejawenLab/SemartSkeleton/badge.svg?branch=master)](https://coveralls.io/github/KejawenLab/SemartSkeleton?branch=master)
[![PHPStan](https://img.shields.io/badge/style-level%20max-brightgreen.svg?style=flat-square&label=phpstan)](https://github.com/phpstan/phpstan)

## Tentang

**Semart Skeleton** adalah sebuah skeleton atau boilerplate atau kerangka awal untuk memulai sebuah proyek. Dibangun dengan menggunakan framework [Symfony](https://symfony.com) dan berbagai bundle serta diramu oleh Developer yang telah berpengalaman lebih dari **8 tahun** menggunakan Symfony.


Ditujukan untuk memudahkan Developer dalam mengerjakan proyek tanpa perlu dipusingkan dengan berbagai pengaturan-pengaturan yang bersifat rutinitas dan berulang.
Memiliki beberapa fitur dasar seperti pengaturan user, group, menu dan hak akses yang dapat diatur dengan mudah melalui menu yang telah kami siapkan.

## Fitur Semart Skeleton

- Pengaturan User

- Pengaturan Group

- Pengaturan Menu

- Pengaturan Hak Akses

- Pengaturan Aplikasi

- SQL Editor

- CRUD Generator

- Pengurutan

- Pencarian

- Multiple File Upload

- User Context Filter


## Kebutuhan Sistem

- PHP 7.2 atau lebih baru

- MySQL/MariaDB/PostgreSQL sebagai RDBMS

- Redis Server sebagai Session Storage

- Composer sebagai Dependencies Management


## Cara Instalasi (Menggunakan Composer)

- Clone repositori dengan `git clone` command:

```
git clone https://github.com/KejawenLab/SemartSkeleton.git Semart
```

atau dengan `composer create-project` command:

```
composer create-project -sdev kejawenlab/semart-skeleton Semart
```

- Masuk ke direktori `Semart` dengan perintah `cd Semart`

- Jalankan perintah `composer update --prefer-dist -vvv`

- Jalankan perintah `symfony server:start` untuk menjalankan web server

- Buka browser pada alamat `http://localhost:8000` atau sesuai port yang tampil ketika menjalankan perintah diatas

- Gunakan username `admin` dan password `semartadmin` untuk masuk ke aplikasi

## Cara Instalasi (Menggunakan Docker)

- Clone repositori dengan `git clone` command:

```
git clone https://github.com/KejawenLab/SemartSkeleton.git Semart
```

atau dengan `composer create-project` command:

```
composer create-project -sdev kejawenlab/semart-skeleton Semart
```

- Masuk ke direktori `Semart` dengan perintah `cd Semart`

- Jalankan perintah `docker-compose build && docker-compose up`

- Masuk ke container `app` dengan perintah `docker-compose exec app bash`

- Jalankan perintah `php bin/console semart:install` dari dalam container `app`

- Buka browser pada alamat `http://localhost:8080`

- Gunakan username `admin` dan password `semartadmin` untuk masuk ke aplikasi

## Flow Semart Skeleton

![Flow](doc/assets/imgs/flow.png "Flow")

## Dokumentasi Lengkap

- [Penggunaan Dasar](doc/id/usage.md)

- [Pengaturan Hak Akses](doc/id/permission.md)

- [Konfigurasi Menu](doc/id/menu.md)

- [Pencarian dan Sorting](doc/id/search_sort.md)

- [Event System](doc/id/event.md)

- [User Context](doc/id/user_context.md)

- [Relasi Tabel](doc/id/relation.md)

- [Relasi Tabel](doc/id/date_time.md)

Anda juga dapat membaca dokumentasinya secara online melalui [Github I/O Putra Kahfi](https://puterakahfi.github.io/SemartSkeleton)

## Unit Testing

```bash
php vendor/bin/phpunit
```

## Preview

* Login

![Login](doc/assets/imgs/login.png "Login")

* Menu List

![Menu List](doc/assets/imgs/menu_list.png "Menu List")

* Roles

![Roles](doc/assets/imgs/roles.png "Roles")

* Setting List

![Setting List](doc/assets/imgs/setting_list.png "Setting List")

* User Form

![User Form](doc/assets/imgs/user_form.png "User Form")

* User List

![User List](doc/assets/imgs/user_list.png "User List")

* Query Runner

![Query Runner](doc/assets/imgs/query_runner.png "Query Runner")

## Bug dan Request Fitur

Anda dapat menggunakan `Issues` untuk melaporkan adanya bug, atau menggunakan `Pull requests` untuk request fitur.

## Kontributor

Terima kasih kepada semua [kontributor](https://github.com/KejawenLab/SemartSkeleton/graphs/contributors)
