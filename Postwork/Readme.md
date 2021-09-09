

## Postwork. Alojar el fichero a un local host de MongoDB 

### OBJETIVO

- Realizar el alojamiento del fichero de un fichero `.csv` a una base de datos (BDD), en un local host de Mongodb a traves de R

#### REQUISITOS

- Mongodb Compass
- librerias `mongolite`
- Nociones básicas de manejo de BDD

#### DESARROLLO


Utilizando el manejador de BDD _Mongodb Compass_ (previamente instalado), deberás de realizar las siguientes acciones: 

- Alojar el fichero  `match.data.csv` en una base de datos llamada `match_games`, nombrando al `collection` como `match`

- Una vez hecho esto, realizar un `count` para conocer el número de registros que se tiene en la base

- Realiza una consulta utilizando la sintaxis de **Mongodb**, en la base de datos para conocer el número de goles que metió el Real Madrid el 20 de diciembre de 2015 y contra que equipo jugó, ¿perdió ó fue goleada?

- Agrega el dataset de `mtcars` a la misma BDD

- Por último, no olvides cerrar la conexión con la BDD
 