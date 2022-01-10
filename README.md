# React Project with Laravel backend
## Requirement
1. NodeJS and npm (https://nodejs.org/en/download/)
2. Composer (https://getcomposer.org/download/)
3. PHP (https://www.php.net/downloads.php)

# Installation
```
1. Clone the project using git clone   
2. Copy a fresh .env file from laravel github    
3. Update .env file by adding database information like DB_HOST.  
4. Go to project root folder. Open terminal and run composer install       
5. Run php artisan key:generate in the terminal    
6. Run php artisan migrate  
7. npm install
9. npm start
```

# Create from Scratch
## Setup Frontend (React)
### To create a project, run: Open your terminal:
```
npx create-react-app projectname
```
### cd projectname and run:
```
npm start
```
### Install Bootstrap in React JS . (https://getbootstrap.com/)
```
npm install bootstrap
```
### after installation of Bootstrap,, import Bootstrap in React JS in <b>src/index.js<b> file.
```
import 'bootstrap/dist/css/bootstrap.min.css'; 
import 'bootstrap/dist/js/bootstrap.bundle.js';
```
### Install React Router Dom for routing
```
npm install react-router-dom@5.2.0
```
### Install Axios for receive API
```
npm install axios
```
## Setup Backend (Laravel)
### Create laravel project
```
composer create-project laravel/laravel projectname
```
### Cd projectname and run:
```
php artisan serve
```
### Create a migration
```
php artisan make:migration create_******_table
```
### Create a Model
```
php artisan make:model ******
```
### Create a Controller
```
php artisan make:controller ******
```
### Migrate
```
php artisan migrate
```

# Reference
1. https://www.fundaofwebit.com/post/crud-app-in-react-js-with-hooks-using-laravel-8-restful-api
2. https://www.youtube.com/watch?v=NidmTs2xZaE
3. https://blog.devgenius.io/a-blogs-posts-app-with-laravel-react-crud-c714c6c5944f
4. https://github.com/vikalp2502/laravel-react-crud-posts
