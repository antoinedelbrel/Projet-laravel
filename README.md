# Creation d'un projet laravel

Crée le projet laravel : `laravel new 'nom du projet`.

Dans le .env il faut faire :   
`DB_CONNECTION=mysql `   
`DB_HOST=127.0.0.1`  
`DB_PORT=3306`  
`DB_DATABASE='nom de la base de donné'`
`DB_USERNAME='nom d'utilisateur de la base de donnée'`  
`DB_PASSWORD='mot de passe de la base de donnée'`

Configurer le web.php dans le dossier routes/, c'est dans ce fichier que l'on retourne des views.

Crée les seeder : 
`php artisan make:seeder 'nom du seeder'`

Crée les les controllers, les models, les migrations, les factorys :
`php artisan make:model 'nom du model' -a`  

Apres avoir modifié la migration de chaque table on actualise pour que les champs apparaissent sur phpMyAdmin grace a la commande `php artisan migrate`.

Pour lancer un projet laravel il faut faire `php artisan serve`

* Les Controllers sont dans app/http/controller/
* Les models sont dans app/
* Les migrations sont dans database/migrations/
* Les Seeders sont dans database/seeds/
* Les factories sont dans database/factories/
* Les views sont dans resources/views/
* Le CSS est dans resources/sass/
* Le JS est dans resources/js/

Pour le css et le js il faut faire la commande `npm install` et pour le lancer il faut faire `npm run watch`.

Le dossier public est le point d'entrée de notre application, c'est lui qui s'occupe de redirigé les URLS

Dans le dossier storage il y a les log de notre appli et les fichier sont stocker dans les storage comme les images...   


