# yannoff/stunning-octo-fiesta

A leaf-weight docker stack for PHP development.

## Prerequisites
- docker
- docker-compose

## Installation
1. Download the `zip` archive from github.

2. Change directory for your web project sources
```bash
$ cd my-web-project
```
3. Unzip from here:
```bash
$ unzip /path/to/downloaded/stunning-octo-fiesta-master.zip
```
4. You're ready to go!

## Usage

```bash
$ bin/server start|stop|log|restart
```

## Running the stack

```bash
$ bin/server start
```
Now your php site is accessible at `http://localhost:8000/`

## Using composer

This project comes in with a wrapper script for `composer`, allowing to run it inside the container.

> This can be very useful if `php` is not installed on the host machine, or if `PHP_VERSION` does not match your `composer.json` requirements.

### Example using composer

```bash
$ bin/composer show
```

## Customizing

You can customize the stack editing the `.env` file.

Available parameters:
- `EXPOSED_PORT` The port to access your website (defaults to `8000`)
- `DOCUMENT_ROOT` Relative path to your document root (defaults to `./`)
- `PHP_VERSION` The version of PHP (defaults to `7.1`)

## Note
The stack uses `PHP`'s built-in development server.

## About the name

Why `stunning-octo-fiesta`? 

Well, running out of inspiration for once, I decided to give github's strange naming bot a chance :)
