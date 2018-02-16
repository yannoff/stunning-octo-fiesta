# yannoff/stunning-octo-fiesta

A leaf-weight docker stack for PHP development.

## Prerequisites
- docker
- docker-compose

## Usage

```bash
$ bin/stack start|stop|log|restart
```

Now your php site is accessible at `http://localhost:8000/`

## Customizing

You can customize the stack editing the `.env` file.

Available parameters:
- `EXPOSED_PORT` The port to access your website (defaults to 8000)

## Note
The stack uses `PHP`'s built-in development server.

## About the name

Why `stunning-octo-fiesta`? 

Well, running out of inspiration for once, I decided to give github's strange naming bot a chance :)
