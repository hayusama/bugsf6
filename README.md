# bugsf6

1.composer install
2.config mysql database in .env (32 line)
3.run cli : php bin/console doctrine:database:create
4.symfony server:start
5.show profiler (3 requests when i use {{ render(controller("App\\Controller\\BlogController::test")) }} in templates/blog/index.html.twig

Config : php 8.1.8 (cli and local test)  mysql 5.7
