 gershwin
==========
### Hello this is the gershwin readme

Consider reading more about George Gershwin:
https://wikipedia.org/wiki/George_Gershwin

## Introduction
Gershwin is a fork of lainchan, itself a fork of vichan which is based on tinyboard. 

## Requirements
1. PHP 5.4+
2. MySQL/MariaDB server
3. [mbstring](http://www.php.net/manual/en/mbstring.installation.php) 
4. [PHP GD](http://www.php.net/manual/en/intro.image.php)
5. [PHP PDO](http://www.php.net/manual/en/intro.pdo.php)

## Install
1. Download and extract gershwin to your desired directory or clone with git: `git clone https://github.com/WelcomeWinters/gershwin.git`.
2. Navigate to `/install.php` in a web browser and follow the prompts.
3. You are now running gershwin. Log in to `/mod.php`. The default username and password is admin/password. Please change the admin password immediately.

## Recommended
1. PHP 7.0+
2. MySQL/MariaDB server >= 5.5.3
3. php-imagick
4. [Memcached](http://www.php.net/manual/en/intro.memcached.php)

## Upgrade
To upgrade from any version of Tinyboard or vichan:

Using git: run `git pull` to update your files, if you used git, or

Without git: backup your `inc/instance-config.php`, replace all files with the current versions (don't remove boards or other files ignored by .gitignore), then put `inc/instance-config.php` back and finally run `install.php`.

To migrate from a Kusaba X board, use [Tinyboard-Migration](http://github.com/vichan-devel/Tinyboard-Migration)

## Contributions
In addition to contributing code to gershwin or any of the upstream projects, translations compatible with all boards based on Tinyboard can be contributed to [vichan](https://www.transifex.com/projects/p/tinyboard-vichan-devel/)

## Licensing and More Info
See LICENSE.md and LICENSE.Tinyboard.md. gershwin is provided with no additional requirements or license. 

## Further Reading
See the [gershwin wiki](https://github.com/WelcomeWinters/gershwin/wiki)
Reading the comments on /inc/config.php is probably the best source of information on the inner working of tinyboard.

