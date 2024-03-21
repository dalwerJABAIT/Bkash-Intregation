## bKash Payment Gateway Integration with Laravel 10

## Clone this repo
```
https://github.com/samironbarai/Bkash-Intregation.git
```

## Install composer packages
```
$ cd Bkash-Intregation
$ composer install
```

## Create and setup .env file
```
make a copy of .env.example and rename to .env
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
```

## Migrate and insert records
```
$ php artisan migrate
$ php artisan db:seed
```

## Put bKash sandbox credentials to config.json
```
create config.json file to storage/app/public
put credentials

```

# Sandbox Testing Credentials 
```
Testing Number: 01877722345, 01823074817
OTP: 123456
PIN: 12121
```
