# yannoff/stunning-octo-fiesta

A leaf-weight docker stack for PHP development.

## Prerequisites
- docker
- docker-compose

## Usage

```bash
$ bin/stack start|stop|log|restart
```

## Example

```bash
$ bin/stack start
```
Now your php site is accessible at `http://localhost:8000/`

## Using composer

This project comes in with a wrapper script for `composer`, allowing to run it inside the container.

> This can be very useful if `php` is not installed on the host machine, or if `PHP_VERSION` does not match your `composer.json` requirements.


```bash
bin/composer show
```

## Customizing

You can customize the stack editing the `.env` file.

Available parameters:
- `EXPOSED_PORT` The port to access your website (defaults to 8000)

## Note
The stack uses `PHP`'s built-in development server.

## About the name

Why `stunning-octo-fiesta`? 

Well, running out of inspiration for once, I decided to give github's strange naming bot a chance :)
