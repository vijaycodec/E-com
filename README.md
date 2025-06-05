Install node packages: npm install
Install the composer dependencies: composer install
Link the storage: php artisan storage:link
For the database, you can either import the given SQL file or start a new one following the command lines.
Now migrate the tables: php artisan migrate
Run seeder: php artisan db:seed
Then generate the key: php artisan key:generate
And finally, run the project: php artisan serve
