# Project Name

*Project short description*

---

### Requirements

- **[PHP](https://www.php.net/)** `8.1`
- **[MySQL](https://www.mysql.com/)** `8.0`
- **[Composer](https://getcomposer.org/)** `2.3`
- **[Yarn](https://yarnpkg.com)** `1.22`
- **[Symfony client](https://symfony.com/download)** `4.28`

---

### Installation

- create `.env.local` based on `.env` and set values for your local environment.
- `composer install` to get the framework dependencies.
- `yarn install` to get the assets pipeline dependencies.
- `php bin/console doctrine:database:create` to create database.
- `php bin/console doctrine:migrations:migrate` to setup database structure.
- `php bin/console doctrine:fixtures:load` to load data.

---

### Local environment

- `yarn watch` to launch webpack.
- `symfony server:start` to launch local server.