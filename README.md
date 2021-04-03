# Docker Spot - Linux, Nginx, MySQL 8.0, PHP 7.4 & PHPMyAdmin

Set of all development-related tools needed for PHP development i.e,

- Linux

- Nginx

- MySQL 8.0

- PHP 7.4

- PHPMyAdmin

## Assumption

I am assuming that you are familiar with,

- Docker

## Installion

Just run this command,

- `docker-compose up -d`

## Information

After installation below are the ports for the usage of the container,

### Nginx

It is bound on port number 80. Please take a note if the port is already in use then change the port number.

### MySQL 8.0

MySql is bound on the same default port. Please take a note if MySQL is running on the host machine then either you should stop MySQL in the host machine or change the port in the `docker-compose.yml` file.

### PHPMyAdmin

It is bounded on port number 3333. For accessing PHPMyAdmin in the browser, you need to hit the `localhost:3333`.
