<div id="top"></div>

# Easy Work Outsourcing

Nathan Vitiver Novaes - nathan.vitiver@gmail.com


### Built With

* [Docker](https://www.docker.com/)
* [PHP](https://www.php.net/releases/8_1_0.php)
* [Laravel Framework](https://laravel.com/)
* [Postman](https://www.postman.com/)

<p align="right">(<a href="#top">back to top</a>)</p>


## Getting Started

### Prerequisites

You need to have installed the PHP 8.1 (cli) on your local computer and Composer version 2.3.3.

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
   cd api-easy-work && composer install
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

3. Start frontend 
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

### Features
- [x] Register category
- [x] Register Notice
- [x] Home page with all notices
- [x] Search Bar



<p align="right">(<a href="#top">back to top</a>)</p>

### API Endpoints Documentation
https://documenter.getpostman.com/view/11939856/UVyxQu2f

<p align="right">(<a href="#top">back to top</a>)</p>

