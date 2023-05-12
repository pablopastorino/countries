# countries

Este proyecto está construido con Angular y NestJS, y utiliza Docker Compose para correr. 

## Instrucciones

1. Clonar el repositorio

`git clone --recurse-submodules https://github.com/pablopastorino/countries.git`

2. En la carpeta raíz del proyecto, correr el siguiente comando para construir y levantar la aplicación:

`docker-compose up --build`

3. Para correr los tests de la API, ir a la subcarpeta `api` y correr el siguiente comando:

`docker-compose run nestjs-api npm test`

4. Para correr los tests de la app de Angular, ir a la subcarpeta `app` y correr el siguiente comando:

`docker-compose run angular-app npm run test`

¡Listo! Con estos pasos podrás construir y testear la aplicación sin problemas.

¡Muchas gracias!:)
