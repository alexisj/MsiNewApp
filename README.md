1. Install submodules

    git submodule update --init

2. Install vendors

    php bin/vendors install

3. Create and chmod cache and logs in app folder

4. Create new file parameters.ini in app/config etc

5. Create database and schema and load fixtures

    app/console doctrine:dabatase:create
    app/console doctrine:schema:create
    app/console doctrine:fixtures:load

6. ????

7 Profit!