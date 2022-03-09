# php8.1-ubuntu
Install php 8.1 en UBUNTU with extension


- Add PPA for PHP 8.1
Add the ondrej/php which has PHP 8.1 package and other required PHP extensions.

```bash
sudo apt install software-properties-common
sudo add-apt-repository ppa:ondrej/php
sudo apt update
```

## Install PHP 8.1 for Apache
Execute the following command to install PHP 8.1

```bash
sudo apt install php8.1
```

After the installation has completed, you can confirm the installation using the following command
```bash
php -v
```

## Install PHP 8.1 Extensions
Now, install some commonly used php-extensions with the following command.

```bash
sudo apt install php8.1-common php8.1-mysql php8.1-xml php8.1-xmlrpc php8.1-curl php8.1-gd php8.1-imagick \ 
php8.1-cli php8.1-dev php8.1-imap php8.1-mbstring php8.1-opcache php8.1-soap php8.1-zip php8.1-redis php8.1-intl -y
```
## Install PHP 8.1 FPM for Nginx
For Nginx you need to install FPM. Execute the following command to install PHP 8.1 FPM

```bash 
sudo apt install php8.1-fpm
```


