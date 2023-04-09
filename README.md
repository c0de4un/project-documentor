# project-documentor
Project web-documentation management tool. Works on Laravel + Vue.js (&amp; Vite)

## Requirements
### System
* 2-Core CPU
* 1 GB RAM
* 10GB storage

### Software
* PHP 8+
* `intl` PHP-extension
* Node.js & npm

## Installation
### Common
Build and start Docker image
```sh
    $php docker-compose up --build -d
```

### Backend
1. Download `composer.phar` from `https://getcomposer.org/download/` to `/app/html`
2. Install PHP packages
```sh
    $php composer.phar install
```

### Frontend
1. Install Node.js on your host-machine
2. Build artefacts to `/app/html/public`, using your host-machine npm
