#### Xss Middleware
##### Step 1: Create new middleware: `php artisan make:middleware XssSanitization`
##### Step 2: Check XssSanitization file in middleware folder on the project.
##### Step 3: Register this middleware in our app/Http/Kernel.php file and add the following line in the $routeMiddleware array.
##### Finally: You can now use the XssSanitization middleware in the routes.
