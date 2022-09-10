##About
####I am using Dependency  injection   in products crud & API ,
And do not for role permissions [For time],

1. User type-based authentication system using passport (REST API).
2. User login with email, phone, username, and password (single field for email, phone, or username).
3. Product management system (only CRUD using laravel resource route and use Dependency injection properly).
4. Products should have variations (design the database in your own way).
5. Perform all crud operations with ajax.
6. Product filter with a price range, ASC/DESC, active/inactive from the product table (with a single method).
7. Create a dataset of ten products and insert or update it with one query. Also, share the dataset with us.
8. User crud role permission on the product (according to permission users will be able to perform specified CRUD operations).

Hope fully  All requirement have done. if any kind of issues please contact me.

##Api List

- [Api list Link](https://www.getpostman.com/collections/46cfb22cd0bc0e495b6f).
- [Base URL(assign)](http://127.0.0.1:8000/api/assignment).

### environment variable
{{assign}} == http://127.0.0.1:8000/api/assignment

#Technolgoy
#### laravel 
#### Vue js 
#### Inertia js 
#### Tailwind Css 


##installation
``` bash
  git clone https://github.com/Ariful491/assignment.git
  
  
  composer install
  
  
  cp .env.example .env
```
Open your .env file and change the database name (DB_DATABASE) to whatever you have, username (DB_USERNAME) and password (DB_PASSWORD) field correspond to your configuration.

``` bash

    php artisan key:generate
    
    npm install
    
    npm run dev
   
   php artisan migrate
   
   php artisan serve
   
   php artisan db:seed
    
    ////Api
    php artisan passport:install
   
```

###After seeding
you will get   all default data that's you prepared.
 
##short demo
 
