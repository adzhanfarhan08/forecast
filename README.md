# Documentation

## Developer Documentation

### Tech-Stack

This program is build with:

    - Framework: Laravel
    - Login: Breeze
    - Role Permission: Spatie
    - Dashboard Management: Filament

### How To Use

#### Step 1

```NPM
npm install
```

#### Step 2

```Composer
composer update
```

#### Step 3

```Fresh Migration
php artisan migrate:fresh
```

Optional

```Added Seeder
php artisan db:seed
```

Create Resource
php artisan make:filament-resource {Name Model}

Create model
php artisan make:model {Name Model} -m
