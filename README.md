# SlimApp RESTful API

This is a RESTful api built with the SlimPHP framework and uses MySQL for storage.

### Version
1.0.0

### Usage


### Installation

Create database or import from _sql/agricultural.sql

Edit db/config params

Install SlimPHP and dependencies

```sh
$ composer
```
### API Endpints
- แฟ้มข้อมูลผู้ผลิต
```sh
$ GET /api/producers
$ GET /api/producers/{id}
$ POST /api/producers/add
$ PUT /api/producers/update/{id}
$ DELETE /api/producer/delete/{id}
```
- แฟ้มข้อมูลแปลงผลิต
```sh
$ GET /api/garden
$ GET /api/garden/{id}
$ POST /api/garden/create
$ PUT /api/garden/update/{id}
$ DELETE /api/garden/delete/{id}
```
- แฟ้มข้อมูลภาพสวน
```sh
$ GET /api/imggarden
$ GET /api/imggarden/{id}
$ POST /api/imggarden/create
$ PUT /api/imggarden/update/{id}
$ DELETE /api/imggarden/delete/{id}
```
- แฟ้มข้อมูลประเภทผลไม้
```sh
$ GET /api/fruittype
$ GET /api/fruittype/{id}
$ POST /api/fruittype/create
$ PUT /api/fruittype/update/{id}
$ DELETE /api/fruittype/delete/{id}
```
- แฟ้มข้อมูลผู้ซื้อ
```sh
$ GET /api/buyers
$ GET /api/buyers/{id}
$ POST /api/buyers/create
$ PUT /api/buyers/update/{id}
$ DELETE /api/buyers/delete/{id}
```
- แฟ้มข้อมูลข่าวกิจกรรม
```sh
$ GET /api/news
$ GET /api/news/{id}
$ POST /api/news/create
$ PUT /api/news/update/{id}
$ DELETE /api/news/delete/{id}
```
- แฟ้มข้อมูลภาพข่าวกิจกรรม
```sh
$ GET /api/imgnews
$ GET /api/imgnews/{id}
$ POST /api/imgnews/create
$ PUT /api/imgnews/update/{id}
$ DELETE /api/imgnews/delete/{id}
```
