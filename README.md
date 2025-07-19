## Project init
install laravel using you cli

## install breeze
- install [laravel breeze](https://laravel.com/docs/11.x/starter-kits#laravel-breeze-installation)
  - ```
    composer require laravel/breeze --dev
    
    php artisan breeze:install
    
    php artisan migrate:fresh
    npm install
    npm run dev
    ```
## Next steps
- create View file and route for each user Role
- got to AuthenticationSessionController file and change Redirect after login based on User Roles
- create and modify RoleManage middleware
  - ```
    php artisan make:middleware RoleManager
    ```
- Go to bootstrap > app and declare middleware
- Add Middleware to Routes
