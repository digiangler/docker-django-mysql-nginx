# docker-django-mysql-nginx

### ローカル環境

- docker 20.10.8
- docker-compose 1.29.2
- git 2.33.0
- GitHub 2.14.2

### 作成する環境

- Python 3.9.5
- MySQL 8.0
- nginx 1.21.3

### サービスの構築

```
$ docker-compose build
```

### コンテナーの作成と立ち上げ

```
$ docker-compose up
```

### アプリのコンテナーに接続

```
$ docker-compose exec app bash
```

### Django インストールコマンド

```
$ docker-compose exec app django-admin.py startproject app .
```
