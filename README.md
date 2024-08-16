Laravel API Project


Setup Instructions

composer install

4. Set Up Environment
Copy the example environment file:

cp .env.example .env


Generate the application key:
php artisan key:generate


Update your .env file with your database and other settings.

4. Run Migrations
Create the database schema:
php artisan migrate


6. Start the Development Server

php artisan serve
Your application should now be running at http://localhost:8000.
