# Covidpp

O projeto tem como objetivo fornecer melhor visualização dos dados da epidemia de covid19 da Secretaria de Saúde de Presidente Prudente.

## Requisitos

PHP 7.2+

Composer

Extensões listadas no Dockerfile

## Rodando com Docker

docker build --network=host --tag covidprudente:1.0 .

docker run -d -p 8001:8001 covidprudente:1.0

## License

The Lumen framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
