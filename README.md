<p align="center">
<a href="https://github.com/sathish447/laravel-breeze-multi-auth/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/sathish447/laravel-breeze-multi-auth"></a>
<a href="https://github.com/sathish447/laravel-breeze-multi-auth/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/sathish447/laravel-breeze-multi-auth"></a>
<a href="https://packagist.org/packages/sathish447/laravel-breeze-multi-auth"><img src="https://img.shields.io/packagist/dt/sathish447/laravel-breeze-multi-auth" alt="Total Downloads"></a>
<a href="https://github.com/sathish447/laravel-breeze-multi-auth/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/sathish447/laravel-breeze-multi-auth"></a>
</p>


## Installation

Clone this repo

    git clone https://github.com/sathish447/laravel-breeze-multi-auth.git

Create env file and set up your DB connection

    cp .env.example .env

Generate key

    php artisan key:generate

Install packages

    composer install

Run migrations without admins/users

    php artisan migrate

Or run migrations with admins/users

    php artisan migrate --seed

Default password for admin and users is "password"

## References
- [Laravel 9](https://laravel.com)
- [Laravel Breeze](https://laravel.com/docs/9.x/starter-kits#laravel-breeze)

## Contributing

Anyone who wants to make some improvement just make a Pull-Request.

If you can achieve the same goal using Jetstream, please share your solution with me as I am very interested.

## License

The Laravel framework and this repository is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
