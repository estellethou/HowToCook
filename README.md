# HowToCook 

"How To Cook" is a template of a website displaying ads using  LARAVEL v8, HTML, CSS, PHP and MySQL. You can :
- authentificate : sign-in, sign-up, log out, log as admin or user
- manage CRUD : use an admin page to manage your database and see all your users
- create profile for each user and display adds, create / edit / delete them 

It's a collaborative website where you can offer cooking classes for a fee or just participate in cooking classes. 

## Installation

#### Install PHP and Apache
[macOS 11.0 Big Sur Apache Setup: Multiple PHP Versions](https://getgrav.org/blog/macos-bigsur-apache-multiple-php-versions)

#### Install mySQL
You also need to install ```mySQL``` : https://dev.mysql.com/doc/mysql-installation-excerpt/8.0/en/windows-install-archive.html

#### Install composer
```brew install composer```

#### Install library
Read composer.json and install all libraries 
```npm install ```

## Usage

```bash
php artisan serve
```
In .env file change DB "name", "username", "password"
In mySQL create a DB named "name" 

```bash
php artisan telescope:install 
php artisan migrate
yarn
npm run dev
```

Go to /public and run 
```
rm storage
```
The go to root directory and run:
```
php artisan storage:link  
```

Then open a browser with the url :
```http://127.0.0.1:8000/home/page0```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Tutorial 
Here is the tutorial on which I based my project [Laravel PHP Framework Tutorial - Full Course for Beginners (2019)](https://www.youtube.com/watch?v=ImtZ5yENzgE)
