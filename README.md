# ActiveRouter
Rotas implementação simples, para iniciação a rota

Basic Usage
```php
<?php

require_once __DIR__ . '/vendor/autoload.php';

/**
 * Cria conexão com o banco de dados
 */
$router = new \ActiveRouter\Router();
$router->newRouter('/', 'namespace\Init');
$router->newRouter('/search', 'namespace\Search');
$router->run();
```
By Packagist
cd <your project>
composer require 'jandelson/active-router:dev-master'
