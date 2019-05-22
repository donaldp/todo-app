## Todo

<img src="demo,png">

### Getting Started

First clone the application:

```bash
git clone https://github.com/donaldp/todo-app.git
```

Install PHP dependencies:

```bash
composer install
```

Install JavaScript dependencies:

```bash
npm install
```

Rename `.env.example` to `.env` then set the app key by running the following command:

```bash
php artisan key:generate --ansi
```

Create a new Database and configure it in the `.env` then run the `migrate` command:

```bash
php artisan migrate
```

Add a cronjob

```bash
* * * * * php /todo-app-path/artisan schedule:run >> /dev/null 2>&1
```

Run the application!

```bash
php artisan serve
```

> Don't forget to configure the default email account in the `.env` file.

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [donaldpakkies@gmail.com](mailto:donaldpakkies@gmail.com). All security vulnerabilities will be promptly addressed.

## License

This Todo application is a open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
