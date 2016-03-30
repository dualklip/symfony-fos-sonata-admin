Symfony 2.8 + FOS + Sonata Admin
================

dev versión (not for production use)

Deploy steps
================
1. composer install
2. composer update
3. app/console doctrine:schema:create
4. app/console fos:user:create
5. app/console fos:user:promote (use ROLE_SUPER_ADMIN)
6. app/console server:start
7. access to http://127.0.0.1:8000
