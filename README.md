# php-microframework

A minimal PHP 8 microframework for websites.

## Features

- Automatic routing based on URL path, e.g. `https://domain/controller/method/parameters...`
- Twig templates with Tailwind CSS base template

## Development Status

The framework is currently in development and subject to frequent change. A stable version with
tagged release will be made available when ready.

## Installation

`composer create-project johnsquibb/php-microframework:dev-main`

`npm install && npm run watch`

## Setup

Point the desired web server at the [public](public) directory and modify the contents
of [index.php](public/index.php) to add additional controller search paths.

## Run

Use the builtin PHP server to serve from the public directory during development:

`php -S localhost:8080 -t public`

Then visit: http://localhost:8080 to view the demo.

## Compile CSS

In order to use Tailwind CSS you need to compile it. You can do it by running `npm run watch`
