# Lareact Movie Test
This application is aimed at building a movie app which allows users create a and add any movie of their choice to the list 


# Technologies
1. Laravel (backend)
2. React (Frontend)
3. MySQL (Database)
4. Tailwind (Styling)
6. PHPUnit (Testing)
# Requirements
```sh
    "php": "^8.0"
```
# Setting it up
These are the steps to get the app up and running. Once you're using the app.

1. Clone the repository
2. `composer install`
3. Rename `.env.example` to `.env` and run `php artisan key:generate`
4. Create a MySQL database. Add the database name to your `.env`
5. Run migrations: `php artisan migrate --seed`
6. Run `php artisan test`
