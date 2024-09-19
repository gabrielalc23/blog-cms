<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

### Project Description

Esse CMS foi feito em Laravel na versão 11

### What I use it this project
- Laravel Framework 11,
- Tailwind for front and admin,
- Laravel Policies,
- Laravel Gates,
- Laravel Mail,
- Laravel Queues ( Building weekly Newsletter ),
- Custom Validation Rule,
- Comments, Applied ( Polymorphic relationship ),
- Applied ( One to many and Many to many ) relationships betwen models,
- Posts Views Count using Cookies,
- Faker & Database Seeder,
- jQuery
- SEO friendly slug URLS,
l
### Screenshots

#### Data Base Schema
<img src="screenshot/schema-database-blog-cms-Gabriel-Campos.png" width="750" alt="Database Schema - BlogCMS - Gabriel Campos">

#### Admin Panel
<img src="screenshot/admin-panel-admin.png" width="750" alt="Admin Panel - BlogCMS - Gabriel Campos">

#### Writer Panel
<img src="screenshot/admin-panel-writer.png" width="750" alt="Writer Panel - BlogCMS - Gabriel Campos">

#### Front Blog
<img src="screenshot/blog-front.png" width="750" alt="Front Blog - BlogCMS - Gabriel Campos">

#### Front Blog - PostView
<img src="screenshot/post-view.png" width="750" alt="Front Blog - PostView - BlogCMS - Gabriel Campos">


### Project Functionality
#### Admin Panel
- Edit General Blog informations,
- Create/ Update / Delete ( Categories, Posts, Tags and Custom Pages )
- Manage Roles

### Writer Panel
- Create, Update and Delete it own Posts
- Create, Update and Delete Tags.

### Roles
                    
Role Name  | Role_ID
------------- | -------------
Admin  | 1
Writer | 2 
User | 3
                

### Gate Function
There is a gate filter login when the user login to the admin panel if the user is Admin it will have full functions to manage the blog and if a Writer it will have few functions.

### Api Routes
                    
Method  | End_Point | Description
------------- | ------------- | -------------
GET | api/categories | Show All Categories
GET | api/categories/{id} | Show All Posts inside Specific Category
GET | api/posts | Show All Posts
GET | api/posts/{id} | Show Specific Post

## Requirements
- PHP >= 8.2
- MySQL or other database server
- Composer
- NodeJS

### How to Install
1. Clone the project
2. Go to the project root directory and run `composer install` and `npm install`
3. Create `.env` file and copy content from `.env.example`
4. Run `php artisan key:generate` from terminal
5. Change database information in `.env`
6. Run migrations by executing `php artisan migrate` , Then Run  `php artisan db:seed` if you want use faker database records,
7. Start the project by running `php artisan serve`

## About Me

Sou um desenvolvedor full-stack, estudante do SENAI Alvares Romi

- [LinkedIn](https://www.linkedin.com/in/gabriel-aparecido-lopes-de-campos-1164a2271/).


