# Hack n Write Ecommerce App

## Wireframes
Find the wireframes [here](https://www.figma.com/file/2D6B2eiCdRwO4VcTZCzxNi/Matoa-Website-Redesign-Community?node-id=48%3A0). The wireframes were created by an awesome UI designer known as [Muhammad Abdurrahman](https://twitter.com/mhdabdur_).

![wireframes-preview](https://user-images.githubusercontent.com/40396070/95829798-a7372d80-0d2e-11eb-88f7-10acdc5fcf77.png)

## Getting started
* Clone this repo
    ```bash
    git clone https://github.com/student-ambassadors-futo/laravel-vue-app.git
    ```

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

