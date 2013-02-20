nginx-automator
===============

## Warning ##

Before you use this, configure the file init.sh  so that all the values at "Global vars" match with your system directories and configs. I haven't fully tested on all operating systems. It should work on Debian and Ubuntu installations but it may contain bugs. Please make a backup of your files before anything bad happens.

## Description ##

Configuring nginx is easy, but sometimes you may have something more interesting to do, for example: playing with your dog or reading a book :P. This tool automates the basic configuration of an nginx host.

## Usage ##

init.sh HOSTNAME ROOT_DIR [ -drupal | -php | -mobile | -cake ]

-drupal

Include basic configuration for drupal

-php 

Include configuration for php-fpm

-mobile

Common configurations for mobile sites.

-cake

Common configurations for CakePHP sites.
