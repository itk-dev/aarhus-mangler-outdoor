# Sports-facilities proposal system

## Project setup

Run the docker container

`docker-compose up -d`

Install requiered packages

`docker-compose composer install`

Import drupal configutation

`docker-compose vendor/bin/drush config-import`

Export drupal configutation

`docker-compose vendor/bin/drush config-export`

## Sub theme

Sub-theme located in:

web/themes/sportsfaciliteter
