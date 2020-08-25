# PHP_Doctrine
[Understand the Model-View-Controller pattern](https://cursos.alura.com.br/course/php-model-view-controller)

This a trainning provided by [Alura](https://cursos.alura.com.br)

Take this PHP for web course and:
- Understand the Model-View-Controller pattern
- Filter and validate form data
- Use session and cookies for authentication
- Apply good practices and use PSRs
- Find out what WebServices are and how to implement

## Installation

Use the package manager to install php.
On Windows, I'm using [Chocolatey](https://chocolatey.org/)
```bash
choco install php
```
```bash
choco install composer
```

## Usage
Open a terminal on the folder where is the code and type:
```bash
composer install
```
```bash
vendor\bin\doctrine-migrations migrations:migrate
```
```bash
vendor\bin\doctrine orm:generate-proxies
```
```bash
php -S localhost:8080
```

Access the pages

[localhost:8080/login](localhost:8080/login)

[localhost:8080/listar-cursos](localhost:8080/listar-cursos)

[localhost:8080/buscarCursosEmJson](localhost:8080/buscarCursosEmJson)

[localhost:8080/buscarCursosEmXml](localhost:8080/buscarCursosEmXml)


## License
[MIT](https://github.com/GabrielDSousa/MVC_with_PHP/blob/master/LICENSE.md)

