# Aarhus Mangler Outdoor proposal system

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

## Deployment

```sh
git clone git@github.com:itk-dev/aarhus-mangler-outdoor.git
git checkout main

composer install --no-dev

drush si --existing-config
```
