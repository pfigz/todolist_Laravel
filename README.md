
## To Do List App

This project follows a really straight-forward tutorial to get a handle on Laravel basics. The front end is built with Vue 2. As a result, some additional dependencies need to be installed if you create the app from scratch following the video. You will also need to setup your own database. MySQL is used here and in the tutorial. You should already have [Composer](https://getcomposer.org/) and [npm](https://www.npmjs.com/) installed prior to building this project.

- Scrypster's YouTube [tutorial](https://www.youtube.com/watch?v=UHSipe7pSac).

## Install Vue and Additional Dependencies

Run the following terminal commands from the project root after initial setup with [Laravel](https://laravel.com/docs/9.x/installation).

```
composer require laravel/ui
```
```
php artisan ui vue
```
```
npm i vue-loader
```
```
npm install && npm run dev
```

The app.js file will contain extra scaffolding code after running these commands. I recommend removing it to match the tutorial for simplicity. 

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
