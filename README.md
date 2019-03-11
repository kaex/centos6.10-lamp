## CentOS Web Development 💻

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/xosad/centos6.10-lamp/issues)

CentOS - Web Development Server PHP, MySQL, PHPMyAdmin, Composer, SSH

## Features
<ul>
<li>Centos 6.10</li>
<li>Apache</li>
<li>PHP 7.2</li>
<li>phpMyAdmin</li>
<li>Git</li>
<li>SSH</li>
<li>Composer</li>
</ul>

## How to use?
Fire up docker and pull image `docker pull xosad/centos6.10-lamp:latest`

Start image using `docker-compose up -d` (be inside the folder with `docker-compose.yml`)

## NOTES
MySQL creates temporary password you can find them using `grep -i temporary /var/log/mysqld.log` after you login `mysql -u root -p` change password using `SET PASSWORD FOR 'root'@'localhost' = PASSWORD('Yourpassword1!');`
