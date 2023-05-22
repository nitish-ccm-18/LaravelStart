
## We will create auth scaffold command to create login, register and dashboard. so run following commands:

### Include Laravel 8 UI Package
```
composer require laravel/ui
```

### Generate Auth
```
php artisan ui bootstrap --auth 

npm install

npm run dev
```

### If bootstrap is not loading then do following steps : 
```
npm install resolve-url-loader@^4.0.0 --save-dev --legacy-peer-deps
npm run dev
```

