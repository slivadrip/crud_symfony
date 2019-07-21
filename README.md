# Novo Projeto Symfony 4

### Crud

`symfony new --full crud_symfony
`

`cd crud_symfony/
`

`composer req orm
`

`php bin/console make:entity
`

`Edit file .env
`

`php bin/console doctrine:database:create
`

`php bin/console doctrine:schema:create
`

`php bin/console make:crud Produtos
`

`composer require symfony/webpack-encore-bundle
`

`yarn install
`

`symfony server:start`
