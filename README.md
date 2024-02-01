#  Book Rental Library - Exercise 2: 

Expand the book rental library application to include functionality for users to view a list of books, and rent a book. This involves setting up a database, creating models and relationships, and handling form data securely.

## Installation

- Copy `.env.example` to `.env`
- Run `composer install`
- Run `php artisan key:generate --ansi`
- Run `php artisan migrate`
- Run `php artisan db:seed --class=GenresTableSeeder`
  
## Run Application

- Run `php artisan serve` or open project from browser: `http://localhost/laravel-project/public`.
- Add some books: Management > Books > [Add new book]
  
## Topics

- [Validation](https://laravel.com/docs/10.x/validation)
- [Database](https://laravel.com/docs/10.x/database)
- [DB Query Builder](https://laravel.com/docs/10.x/queries)
- [DB Migrations](https://laravel.com/docs/10.x/migrations)
- [DB Seeding](https://laravel.com/docs/10.x/seeding)
- [Eloquent ORM](https://laravel.com/docs/10.x/eloquent)
- [Eloquent - Relationships](https://laravel.com/docs/10.x/eloquent-relationships)
- [Eloquent - Collections](https://laravel.com/docs/10.x/eloquent-collections)