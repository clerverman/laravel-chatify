1. create a laravel project
2. install chatify :
https://chatify.munafio.com/installation
- composer require munafio/chatify
- php artisan chatify:install
- php artisan migrate
3. etablish auth system in u app , u should login to use u chatify
4. create a pusher account :
https://dashboard.pusher.com/apps/1551818/keys
5. go to api settings and enable client events : Enable client events
6. app keys to copy the key :
app_id = ""
key = ""
secret = ""
cluster = ""

notice that cluseter is an important info

7. to diplay image any other data , u should use :
php artisan storage:link
8. go to .env : APP_URL : http://localhost:8000



1. create a laravel project
2. install chatify :
https://chatify.munafio.com/installation
- composer require munafio/chatify
- php artisan chatify:install
- php artisan migrate
3. etablish auth system in u app , u should login to use u chatify
4. create a pusher account :
https://dashboard.pusher.com/apps/1551818/keys
5. go to api settings and enable client events : Enable client events
6. app keys to copy the key :
app_id = ""
key = ""
secret = ""
cluster = ""

notice that cluseter is an important info

7. to diplay image any other data , u should use :
php artisan storage:link
8. go to .env : APP_URL : http://localhost:8000


