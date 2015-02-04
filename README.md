This repo contains all selenium tests developed for Barloworld Transport systems.

# Selenium libraries:

```
# PHP SeleniumHQ recommend library:
A thin client library used with phpunit to interface with the selenium server engine.

# JS Protractor
A JS library used with nodejs to interface with the selenium server engine. Primary focus on Angular JS testing.
```

# Prepare server for PHP Selenium:
```

```

# Prepare server for Protractor:
```
# Ubuntu/Debian:
apt-get install nodejs firefox curl imagemagick openjdk-7-jre-headless Xvfb

# Archlinux:
pacman -S nodejs jre7-openjdk-headless jre7-openjdk firefox curl imagemagick Xvfb

# Redhat/CentOS:
yum install nodejs firefox curl imagemagick openjdk-7-jre-headless Xvfb

# General
npm install -g protractor

webdriver-manager update

webdriver-manager start

See the following link for more information on creating tests:

angular.github.io/protractor
```
