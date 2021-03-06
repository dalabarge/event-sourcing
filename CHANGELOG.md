# Release Notes

- Installed Laravel v5.6.0 (2018-02-07)
- Installed Composer dependencies
- Installed NPM dependencies
- Created `.env` and generated key with `php artisan key:generate`
- Required `ramsey/uuid` PHP package via Composer
- Emptied `protected $listen = []` in `App\Providers\EventServiceProvider`
- Emptied `protected $policies = []` in `App\Providers\AuthServiceProvider`
- Removed `Illuminate\Foundation\Auth\Access\AuthorizesRequests` from `App\Http\Controllers\Controller`
- Deleted `App\Http\Controllers\Auth` controllers
- Deleted `App\User` model
- Deleted `database/factories/UserFactory.php`
- Deleted `database/migrations/*` database migrations
- Deleted route definitions from `routes/*` files
- Added `public/js`, `public/css`, and `public/mix-manifest.json` paths to `.gitignore`
- Added developer notes to `readme.md`
- Added Composer scripts and dev dependencies for PHP beautification and reporting
- Added `.php_cs` with configurations for code styling
- Added `.php_cs.cache` to `.gitignore`
- Added `<logging>` block to `phpunit.xml` for reporting
