1. Symfony installer runterladen und installieren.

        https://symfony.com/download


2. Projekt erstellen

        symfony new <projectname>
        symfony server:start

3. Packages installieren

        composer require debug profiler vardumper
        composer require maker
        composer require ramsey/uuid ramsey/uuid-doctrine 
        composer require api


4. Entities basteln

        bin/console make:entity --api-resource


Links:

    https://api-platform.com/docs/distribution/#using-symfony-flex-and-composer-advanced-users
    https://api-platform.com/docs/core/security/

