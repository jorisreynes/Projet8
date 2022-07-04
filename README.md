# Project 8 Openclassrooms Backend Development PHP Symfony

Upgrade an existing ToDo and Co project

Made with PHP 7 and Symfony 5

To get a local copy follow these simple steps

git clone https://github.com/jorisreynes/Projet7.git

• Install dependencies

    composer install
    
• Create the database

    php bin/console doctrine:database:create
    
• Create and install migrations

    php bin/console make:migration 

    php bin/console doctrine:migrations:migrate
    
• Create a virtual server

    php -S localhost:8000 -t public
