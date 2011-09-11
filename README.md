Create and chmod cache and logs in app

Create new file parameters.ini in app/config, etc.

Install submodules

    git submodule update --init

Install vendors

    php bin/vendors install

Create database and schema

    app/console doctrine:database:create
    app/console doctrine:schema:create

????

PROFIT!