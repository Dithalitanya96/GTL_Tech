
<h3 align="center">
Global Tote PHP Assesment 
</h3>


## You'll Need to install following Software/Libraries
- XAMPP / WAMP server
- Composer (PHP package manager)

## How to setup this project

Please follow following steps to setup this project in your machine

- Download / Clone this project.
- Open this project folder in CMD
- Type "composer install" and press enter, this will take a while
- Duplicate '.env.example' file and rename it to '.env'
- Create a databse schema named "GlobalTech"
- Check your database settings are correct in '.env' file (DB_PORT,DB_DATABASE,DB_USERNAME,DB_PASSWORD)
- After that type "php artisan key:generate" and press enter
- After that type "php artisan migrate" and press enter
- Finally type "php artisan serve" and press enter
- Click on the generated link to view project

