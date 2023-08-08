## About it
This is a project snippet that includes a controller for sending feedback and the corresponding frontend part.

The frontend section utilizes webpack encore for bundling and managing assets.

The backend part is written in Symfony.

## Installation

As a usual Symfony project with Webpack encore and Docker compose.

## Tests
### Backend
In order to run tests for the backend. You should launch the `php-fpm` service
```bash
docker compose run --rm php-fpm sh
```
And then
```sh
php bin/phpunit
```
### Frontend
To run tests for the frontend. You should launch `node` service.
```bash
docker compose run --rm node bash
```
And then
```bash
npm run test
```

