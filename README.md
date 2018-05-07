## Available functionalities:

+ Login and logout, forget password  (Lock account in 5 minutes after 3 failed attempts).

+ Manage employees (Add, edit and delete).

+ Manage countries, cities, states (Add, edit and delete).

+ Manage users (Add, edit and delete).

+ Manage salary (Add, edit and delete).

+ Manage division (Add, edit and delete).

+ Manage departments (Add, edit and delete).

+ Make reports (export to Excel and PDF).

+ Search (with multiple combine fields).

+ Pagination

+ Validation

+ Responsive

## Instruction
Please follow all bellow steps:

composer update
rename .env.example with .env
configure database on .env file
create a new database with name employees_db
create new tables with: php artisan migrate
create default user for system with: php artisan db:seed
php artisan key:generate
Execute: php artisan config:clear
Execute: php artisan serve
default usename: admin@gmail.com/admin

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
