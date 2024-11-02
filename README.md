# Getting started 

## Installation

Before you begin, ensure that you have the necessary software installed on your machine, You’ll need: PHP, Composer, Git

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/5.4/installation#installation)

Clone the repository

    git clone git@github.com:yazeeid/sub_php_app.git

Switch to the repo folder

    cd sub_php_app

Get Submodules 

    git submodule init
    git submodule update

Switch to the proeject 

    cd base_php_app
    cd strideProject

Install all the dependencies using composer

    composer install

Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

Generate a new application key

    php artisan key:generate


Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate
    php artisan db:seed
    npm install --save-dev vite
    npm run build

Start the local development server

    php artisan serve

You can now access the server at http://localhost:8000

**TL;DR command list**

    git clone git@github.com:yazeeid/sub_php_app.git
    cd sub_php_app
    git submodule init
    git submodule update
    cd base_php_app
    cd strideProject
    composer install
    cp .env.example .env
    php artisan key:generate
    php artisan migrate
    php artisan db:seed
    npm install --save-dev vite
    npm run build
    
**Make sure you set the correct database connection information before running the migrations** [Environment variables](#environment-variables)

    php artisan migrate
    php artisan serve

**Please Register(Sign-up) to get access to all permission (CRUD)**
