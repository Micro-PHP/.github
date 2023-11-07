
![Logo](https://github.com/Micro-PHP/.github/blob/master/logo/png/logo-color-for-github-welcome.png?raw=true)


[#StandWithUkraine](http://stand-with-ukraine.pp.ua)

It is a fast, lightweight and highly flexible web application PHP framework.

## Requirements
The minimum PHP version must be at least **8.2**

## Get started

It is recommended that you create your first application in a [Docker environment](https://github.com/Micro-PHP/micro-docker) or in a [Docker RoadRunner environment](https://github.com/Micro-PHP/micro-docker-roadrunner)

Or you can create an application via [composer](https://getcomposer.org/).

```bash
$ composer create-project micro/micro {directory} --remove-vcs
$ cd {directory}
$ php -S localhost:10000 -t public/
```

Open http://localhost:10000 and you will see HelloWorld page.

There is also support for console utilities.
```bash
php bin/console
``` 



## Running Tests

To run tests, run the following command. By default, phpstan, psalm, phpunit will be runned.

```bash
$ composer run-script test-all
``` 


## Authors

- [Stanislau Komar](https://www.github.com/asisyas)
- [Oleksii Bulba](https://github.com/OleksiiBulba)


## Contributing

Contributions are always welcome!


## License [MIT](../LICENSE)

