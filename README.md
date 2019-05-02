
# Simple PHP login project using cookies, and unit tests with PHP Unit

[![Build Status](https://travis-ci.org/julio-cesar-development/simple-php-cookies.svg?branch=master)](https://travis-ci.org/julio-cesar-development/simple-php-cookies)

## Instructions

### Running with docker

> Daemon mode

```bash
docker-compose up -d
```

### Running appart

> Database

* Create a schema in a MySQL DB called db_cookie_project:

```mysql
CREATE DATABASE IF NOT EXISTS db_cookie_project;
```

* Through terminal:

```bash
mysql -u [mysql_user] -p[mysql_password] -h [mysql_host] -e "CREATE DATABASE IF NOT EXISTS db_cookie_project;"
```

* Run the file queries.sql through terminal:

```bash
mysql -u [mysql_user] -p[mysql_password] -h [mysql_host] db_cookie_project < queries.sql
```

> Running application

* Run this application through a server like apache, or even through the embedded PHP server like this:

```bash
php -S 0.0.0.0:80
```