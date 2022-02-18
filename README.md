# langkah-langkah-laravel-8

composer create-project --prefer-dist laravel/laravel blog <br>
cd blog <br>
php artisan serve    //jalankan web ke localhost<br>
php artisan make:model Post OR php artisan make:model Post -m  // create model Post  -m=migration untuk pembuatan class ke database<br>
php artisan make:controller PostController  //create controller<br>
route::resource('post', PostController::class); //tambahkan di routes/web<br>
php artisan route:list

selanjutnya https://qadrlabs.com/post/belajar-laravel-8-membuat-aplikasi-crud-sederhana
