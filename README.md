TOKO 20 A
TOKO 20 A adalah sebuah aplikasi point of sales berbasis website dan mobiel.

# 2A-Kelompok3
Nama Kelompok 3 : <br>
Putri Indah Lestari (362155401014) <br>
Denta Prayogi (362155401013) <br>
Siti Mariyatul Kiptiyah (362155401014) <br>
Bunga Nailah Salsabilah (362155401015) <br>
Nudia Isma Annisa (362155401024) <br>

## Technologies
* Laravel
* Flutter

## Setup
Intalasi untuk laravel 7.4 - 8.0.
* setup .env
* composer update
* php artisan migrate --seed
* php artisan key:generate
* php artisan serve

Intalasi API untuk Flutter via IP 4
* xampp
* Apache config
* hapus # LoadModule version_module modules/mod_version.so, LoadModule vhost_alias_module modules/mod_vhost_alias.so
* hapus pagar di bawah # Server-pool management (MPM specific)
Include conf/extra/httpd-mpm.conf
* restart xampp
* setting ip adres 4, catat, contoh 192.168.1.12
* tes di smartphone
* tes API with localhost http://192.168.1.12/pbl-main/public/

## Features
List of features ready and TODOs for future development
* Register
* Login
* CRUD (all)

# Demo web
| url | [http://pbl-rest-api.masuk.web.id/public/login][PlDb] |
| gmail | [admin@gmail.com][PlGh] |
| password | [Toko20andalan][PlGd] |

To-do list:
* Add Rest API (done)

## Status
Done
