# Hack n Write Ecommerce App

## Getting started
* Clone this repo
* Create a mysql/mariadb database with DB name hnr-ecommerce

    ```bash
    mysql -uroot

    # in db repl
    CREATE DATABASE hnr_ecommerce;
    ```
* Run migrations

    ```bash
    php artisan migrate
    ```
    
* Install dependencies

    ```bash
    npm install
    ```

* Generate an app key

    ```bash
    php artisan key:generate
    ```

* Run the server

    ```bash
    php artisan serve
    ```

## Contributing
1. Pick an issue
0. Develop that issue
0. Make a PR

