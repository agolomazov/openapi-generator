## Описание

OpenApi Generator - это

- инструмент написанный на Java для генерирования клиентов, серверов, документации по документу OpenAPI.
- 60+ генераторов клиентской части
- 50 генераторов серверной части

openapi-generator-cli - это npm пакет, который является кросплатформенной оберткой над .jar артефактом OpenApi Generator.

## Полезные ссылки:

[OpenApi Generator](https://openapi-generator.tech/docs/installation)

[openapi-generator-cli](https://www.npmjs.com/package/@openapitools/openapi-generator-cli)

[Список генераторов](https://openapi-generator.tech/docs/generators)

[Генератор для typescript-axios](https://openapi-generator.tech/docs/generators/typescript-axios/)

[Генератор для typescript-fetch](https://openapi-generator.tech/docs/generators/typescript-fetch/)

## NPM скрипты

| Скрипт                     | Описание                                                                 |
| :------------------------- | ------------------------------------------------------------------------ |
| npm run openapi:gen        | сгенерировать api и модели с использованием генератора typescript-axios  |
| npm runopenapi:only-models | сгенерировать только модели с использованием генератора typescript-axios |

## Установка Java

- для работы OpenApi Generator необходимо установить [java](https://jdk.java.net/archive/)
- добавить в системную переменную PATH следующий путь:

```
<PATH_TO_JAVA>\jdk-11\bin
```
