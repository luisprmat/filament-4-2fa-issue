# New app with Filament 4

## Configuration steps
- Open terminal in workspace
- Clone repo [git@github.com:luisprmat/filament-4-2fa-issue.git](https://github.com/luisprmat/filament-4-2fa-issue.git)
- Enter to directory app: `cd filament-4-2fa-issue`
- Install composer dependencies: `composer install`
- Copy `.env`: `cp .env.example .env`
- Set up `APP_KEY`: `php artisan key:generate`
- Create SQLITE database: `touch database/database.sqlite`
- Run migrations and seeders: `php artisan migrate --seed`
- Turn on serve: `composer run dev`
- Navigate to *User profile* `http://127.0.0.1:8000/admin/profile`
- Login as **email:** `test@example.com`, **password:** `password`
- Setup **authenticator app**, scan and input correct *code*
- **CRASH** (View development tools - console)
