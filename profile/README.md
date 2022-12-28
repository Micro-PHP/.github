
![Logo](https://github.com/Micro-PHP/.github/blob/master/logo/png/logo-color-for-github-welcome.png?raw=true)


# It is a fast, lightweight and highly flexible web application PHP framework.

## Requirements
The minimum PHP version must be at least 8.2

## Get started

It is recommended that you create your first application in a [docker environment](https://github.com/Micro-PHP/micro-docker).

Or you can create an application via [composer](https://getcomposer.org/).

```bash
$ composer create-project micro/skeleton {directory} ^1
$ cd {directory}
$ php -S localhost:10000 -t public/ 
```

Open http://localhost:10000 and you will see HelloWorld page.

There is also support for console utilities.
```bash
php bin/console
``` 



## Running Tests

To run tests, run the following command

```bash
$ php vendor/bin/phpunit
``` 


## Authors

- [Stanislau Komar](https://www.github.com/asisyas)


## Contributing

Contributions are always welcome!


## License [MIT](../LICENSE)

