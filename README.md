<div id="top"></div>

# Easy Work Outsourcing

Nathan Vitiver Novaes - nathan.vitiver@gmail.com


### Built With

* [Docker](https://www.docker.com/)
* [PHP](https://www.php.net/releases/7_4_0.php)
* [Laravel Framework](https://laravel.com/)
* [Postman](https://www.postman.com/)

<p align="right">(<a href="#top">back to top</a>)</p>


## Getting Started

### Prerequisites

You need to have installed the PHP 7.4 (cli) on your local computer and Composer version 2.2.7.

  ```sh
    sudo apt install software-properties-common
    sudo add-apt-repository ppa:ondrej/php
    sudo apt update
    sudo apt install php7.4
    php -v
  ```

### Installation

1. Clone the api repo and the frontend repo
   ```sh
   git clone git@github.com:nathannovaes/api-easy-work.git
   ```
   ```sh
   git clone git@github.com:nathannovaes/web-easy-work.git
   ```
   
#### API Configuration
1. Run composer
   ```sh
   cd api-easy-work composer install
   ```
2. Copy env file
   ```sh
   cp .env.example .env
  ```
**Build you docker for the first time.
```sh
  docker-compose up --build -d
```
**Create your Database
```sh
  vendor/bin/doctrine orm:schema-tool:create
```
3. Start project containers
   ```sh
   composer start
   ```

#### Frontend Configuration
1. Run npm
   ```sh
   cd web-easy-work npm install
   ```

3. Start forntend 
   ```sh
   npm run dev
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

### Servers

API 
http://localhost:8080/api/

Frontend
http://localhost:3000/

PhpMyAdmin
http://localhost:8081/

<p align="right">(<a href="#top">back to top</a>)</p>

## Roadmap

### Mandatory Features
- [x] SQL Database to store users and record logs
- [x] User authentication
- [x] Endpoints
    - [x] POST  Create user
    - [x] GET   Request stock quote
    - [x] GET   History queries showing the latest entries firts
- [x] Send an email

### Bonus features
- [x] Unit Test
- [x] RabbitMQ to send the email asynchronously
- [x] JWT Authentication
- [x] Containerize the app 


<p align="right">(<a href="#top">back to top</a>)</p>

### API Endpoints Documentation
https://documenter.getpostman.com/view/11939856/UVyxQu2f

<p align="right">(<a href="#top">back to top</a>)</p>

