# highload-php72-lemp
My option Lemp Ubuntu 18.04 (bionic)

# Features
All-in-one one "click" installation of the LEMP environment
Nginx will be installed with the ability to dynamically load or disable any preloaded module
Backup will be created for your current Nginx, PHP and MySQL / MariaDB installations
Some core settings of Nginx and MariaDB that are often underestimated are configured properly
OPcache is enabled and configured for PHP-FPM
Monit will be configured to watch after SSH, Nginx, PHP and MySQL / MariaDB and restart them in case of an emergency
This configuration was tested in heavy loaded environment (>500k requests to a webserver a day) more then six months straight
Don't struggle anymore with adding new server blocks to Nginx when you add new websites to your server

# Requerements
Ubuntu 18.04 or later (best if it's fresh / clean installation)
This script utilises root user privileges. If you run it from another user you need to add this user to sudoers group and prepend sudo to all commands in the script.

# Exepmle Files
"Hello World" website in /var/www/test.com

phpinfo(); file at /var/www/test.com/info.php

opcache.php at /var/www/test.com/opcache.php
