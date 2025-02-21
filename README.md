﻿# Laravel-Basic-to-Advanced

 # What is laravel ?
  * Laravel is an open-source PHP framework, which is robust and easy to understand. 
  * It follows a model-view-controller design pattern.
  * Laravel reuses the existing components of different frameworks which helps in creating a web application.
  * The web application thus designed is more structured and pragmatic.

# Advantages of Laravel

 * MVC Architecture: Clean and maintainable code.
 * Elegant Syntax: Readable and expressive.
 * Blade Templates: Lightweight and reusable.
 * Comprehensive Docs: Easy to learn and implement.
 * Authentication: Simplified user handling.
 * Eloquent ORM: Easy database operations.
 * Migration System: Database version control.
 * Artisan CLI: Automates tasks.
 * Security: Protection against common vulnerabilities.
 * Community: Large support base and resources.
 * API-Friendly: Easy RESTful API creation.
 * Testing Tools: Built-in unit testing support.
 * Scalable: Suitable for small to enterprise apps.
 * Performance: Built-in caching and optimization.
 * Integration: Seamless with third-party tools.

 # What is  Composer ? 

  * Composer is a tool which includes all the dependencies and libraries.
  * It allows a user to create a project with respect to the
    mentioned framework (for example, those used in Laravel installation).
  * Third party libraries can be installed easily with help of composer.
  * All the dependencies are noted in composer.json file which is placed in the source folder.

# What is  Artisan ?
 * Command line interface used in Laravel is called Artisan. 
 * It includes a set of commands which assists in building a web application. 
 * These commands are incorporated from Symphony framework, resulting in add-on features in Laravel .

# Features of Laravel 
 * MVC Architecture: Organized code structure.
 * Blade Templates: Dynamic and reusable views.
 * Eloquent ORM: Simplified database handling.
 * Routing: Easy route management.
 * Authentication: Built-in user handling.
 * Artisan CLI: Automates tasks.
 * Migrations: Database version control.
 * Caching: Boosts performance.
 * Localization: Multi-language support.
 * Security: Protects against common vulnerabilities.

# What is namespace in laravel? 
* Namespaces are defined at the top of PHP files using the namespace keyword.
   # Purpose
    * Prevents class name collisions.
    * Simplifies autoloading and class referencing.
  # Common Laravel Namespaces
    ```
      App\Models: For Eloquent models.
      App\Http\Controllers: For controllers.
     App\Http\Middleware: For middleware classes.
     App\Providers: For service providers.
   ```
  # Custom Namespaces
   * You can create custom namespaces for better organization. For example, grouping specific services under App\Services.
  # Autoloading    
  * Laravel's autoloader automatically loads classes based on their namespace, following PSR-4 standards.
 
 # What is Trait in laravel ?
   
   A Trait in Laravel is a reusable collection of methods that can be used in multiple classes, 
   providing a way to share functionality without inheritance.

    Code Reuse: Allows sharing methods across classes.
    Declaration: Defined with the trait keyword.
    Usage: Included in a class using the use keyword.
    Conflict Resolution: Handles method name conflicts with insteadof and as.
    Example in Laravel:
    SoftDeletes Trait: Adds soft delete functionality to models.


 # Composer Install ?

    * go to laragon -> www -> create folder -> open cmd -> give below command 

    ```
         compose init
         example/package 
         
         then next next next 
         comple composer setup 

         Install any packages : 
         
         composer require guzzlehttp/guzzle

         composer update
    ```

   # Install Fresh Laravel using composer
       
         composer create-project --prefer-dist laravel/laravel laravel-project
    
         go to laravel project 
    
         cd laravel-project
      
         start development server
      
         php artisan serve
     
    
 
