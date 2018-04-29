# Webhook Tester

With the Webhook Tester app, you can easily test HTTP webhooks and other types of HTTP requests. 

Upon visiting the app, you get a random URL to send your requests and webhooks to, and they're all logged in the app – instantly. Check it out at [https://webhook.site](https://webhook.site). 

Built by Simon Fredsted ([@fredsted](https://twitter.com/fredsted)).

## Requirements

* PHP 7
* Redis
* Composer
* Web server

Version 1.1 switched to using Redis for storage. If you want to use SQLite, you can use version 1.0.

## Installation

### Web Server

1. Run the following commands:
   1. `cp .env.example .env` - adjust settings as needed
   2. `php artisan key:generate`
   3. `composer install`
2. Setup virtual host pointing to the /public folder.

### Docker

A Dockerfile is available at hub.docker.com: https://hub.docker.com/r/dahyphenn/webhook.site/. 

## Acknowledgements

The app was built with Laravel for the API and Angular.js for the frontend SPA.

Thanks to [da-n](https://github.com/da-n) for creating the Docker image.

## Donate

* Bitcoin address: 1Maf64K9Wkpy7oBGEtqEda8H1H2drLSUuF
* Paypal: https://paypal.me/fredsted

