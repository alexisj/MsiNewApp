Install submodules

    git submodule update --init

Install vendors

    php bin/vendors install

Create and chmod cache and logs in app

Create new file parameters.ini in app/config, etc.

Create database and schema and load fixtures

    app/console doctrine:dabatase:create
    app/console doctrine:schema:create
    app/console doctrine:fixtures:load

????

Profit!