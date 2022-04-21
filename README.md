# SACCO Management System

This is built on Laravel.

I am trying to create a system that can be used by SACCOs, which is absolutely free and open source where they can be able to manage their finances and loans. Any collaborators are welcome.

I am quite new to Laravel and so far, have enjoyed the learning experience. I wish to have people who are advanced in it so that they can help with ideas and also cleaning up the code.

This system should be able to:

<!-- This needs to be added. I will find some time and interact with some members of some SACCOs and come up with some of the services they expect out of such a system -->

## How to install

Please run the following commands:

```git clone https://github.com/josephopio11/SACCO.git```

After which you can then run

```cd SACCO```

```composer install```

```cp .env.example .env```

```php artisan key:generate```

Create a database

Open the .env file and enter the database credentials into the part showing the following:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=sacco
DB_USERNAME=root
DB_PASSWORD=
```

Then run the command

```php aritisan migrate --seed```

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

If you find a vulnerability within this app too please feel free to get in touch with me at [hi@josephopio.com](mailto:hi@josephopio.com)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

Feel free to copy this code and use it to make money if possible.

## Request

The people helping work on this project are 100% unpaid volunteers. [Buying them a cup of coffee](https://dashboard.flutterwave.com/donate/gbaigpnzvznt) will raise their morale and help them work longer to improve on this system. Please feel free to donate [using this link](https://dashboard.flutterwave.com/donate/gbaigpnzvznt).

Or

Scan the QR code below:

![Donation QR code](/QRCode.png "Donation QR Code")
