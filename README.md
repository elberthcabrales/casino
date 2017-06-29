# ngMaterialCasino
Sistema para venta en casino con Laravel, angular, Maaterial, web token y json


sistema en laravel 5, angular y jwt. tiene dos roles de usarios cajeros y administradores los cuales pueden hacer solo canjeos o administrastrar jugadores, usuarios, fichas y registrar movimientos

# ngMaterialCasino
Sistema para venta en casino con Laravel, angular, Maaterial, web token y json

#instalar dependencias php
composer update

#instalar dependencias de node del package.json y/o bower
npm install 
bower install

#muchos arcivos se encuentran remotos dentro del index.php
angular_material
jquery-2.1.1
angular
underscore.js

#crear los modelos
php artisan migrate

#Correr seed para llenar modelos con datos de pruebas
#database/seeds/{nombre}Seeder.php
php artisan db:seed --class=DatabaseSeeder
php artisan db:seed --class=JugadorTableSeeder
php artisan db:seed --class=FichaTableSeeder
php artisan db:seed --class=CanjeoTableSeeder
php artisan db:seed --class=RegistroTableSeeder

#nota...por esta unica ocacion no los agregue en el package.json
