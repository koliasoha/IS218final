# is218final
To run the faq project:

1, git clone https://github.com/koliasoha/is218final.git

2, cd into is218final and run composer install

3, cp .env.example to .env

4, Run: php artisan key:generate

5, setup database / with sqlite or other https://laravel.com/docs/5.6/database

6, Run: php artisan migrate

7, Run: unit tests: phpunit

8, Run: seeds php artisan migrate:refresh --seed
