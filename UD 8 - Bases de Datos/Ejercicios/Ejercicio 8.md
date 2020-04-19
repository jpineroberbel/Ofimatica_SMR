## EJERCICIO 87 - Bases de Datos
### Consultas de Campos Calculados y Totalesselección con parámetro.

Antes de realizar cada uno de estos ejercicios estudiar la distribución de información en tablas y las relaciones entre estas.

**A.** A partir de la **base de datos “[BIBLIO.mdb](http://descargas.teformas.com/Archivos%20Teformas/BIBLIO.accdb)”** realizar las siguientes **consultas**:

1.  Cread una consulta con los campos autor y año de nacimiento de la tabla autores mostrando solo aquellos que tienen año de nacimiento. Añadid un campo que calcule la edad actual de los autores.
2.  Realizad una consulta similar para conocer los años que llevan publicados los libros con parámetro**:

1.  Título y año de publicación de los libros escritos por un autor determinado.
32.  Calculad cuál es elTítulo y año de publicación de los libros más reciente.
4.  Calculad la media de edad de los autores.
5.  ¿Cuál es el año de publicación más antiguo? A partir de este dato mostrad los libros más antiguos.

(Resultado en cantidad de registros: 3-1999, 4-63, 5-“World of dBASE”)  publicados por una determinada editorial (indicad el nombre de la compañía).

(Resultado en cantidad de registros: 1–Ej: “Blanc,Iris” 1, 2-Ej: “Que Corp” 162)

  
  
  
**B.** Realizar las siguientes **consultas** sobre los datos almacenados en la **base de datos “[Neptuno.mdb](http://descargas.teformas.com/Archivos%20Teformas/NEPTUNO.accdb)”**:

1.  Cread una consulta con los campos producto, precio unidad, cantidad y descuento de la tabla detalles de pedidos. Añadid un campo que calcule el precio total (precio unidad x cantidad), otro que calcule el descuento y un tercer campo que calcule el precio final.
2.  ¿Cuántos pedidos se enviaron a España?
3.  ¿Cuántos clientes hicieron un pedido en Octubre de 1996?
4.  ¿Cuál es la fecha de nacimiento más reciente de los empleados? A partir de este dato mostrad el nPrecio y nombre de los productos enviados por una compañía de envíos en concreto. Mostrad la fecha del envío.
2.  Nombre y los apellidos del los empleado más joven.
5.  Calcula la media del precio unidad de los productos de la categoría bebidas.
6.  ¿Cuántos productos hay de una categoría determinada? (consulta con parámetro)
7.  Suma el precio unidad de los productos valorados en más de 50 dólares.
8.  ¿Cuál es el producto más caro?

(Resultado en cantidad de registros: 2-23, 3-26, 4-“Anne Dodsworth”, 5-“37,98€”s que han realizado un pedido para cierto cliente (nombre de compañía). Mostrad la fecha del pedido.

(Resultado en cantidad de registros: 1–Ej: “Speedy Express” 643, 62-Ej: “bebidas” 12, 7-“735,79€”, 8-“Vino Côte de Blaye”Que Delícia” 9)

**C.** Realiza las siguientes **consultas** sobre la **base de datos [VIDEOCLUB](http://descargas.teformas.com/Archivos%20Teformas/VIDEOCLUB.accdb)** proporcionada por el profesor:

1.  ¿Cuántos alquileres de 3,00€ se han realizado?
2.  ¿Cuántos dvd hay disponibles?
3.  ¿Cuántas películas hay de género drama estrenadas en el 1998?
4.  Calculad la media del precio de alquilerIdent-dvd y título de los dvd alquilados por cliente en concreto (solicitad el DNI). Incluid también la fecha de alquiler y devolución.
52.  Cread una consulta con los campos Ident-dvd, nombre y apellidos del cliente. Añadid un campo que muestre los días que el cliente tiene la película en su poder.

(Resultado en cantidad de registros: 1-6, 2-38, 3-5, 4-“3,82€”Nombre, dirección y teléfono de los clientes que han alquilado cierto Dvd.
3.  Ident-dvd y título de los dvd sin devolver de un cliente concreto (solicitad el DNI). Incluid también la fecha de alquiler.
4.  Ident-dvd y título de los dvd de un género determinado.

(Resultado en cantidad de registros: 1–Ej: “11111111A” 2, 2-Ej: “AIR-1” 1, 3-Ej:”00000000J” 1, 4-Ej:”drama” 25)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTMzNDg2MjE3MSwxNDY5NzI0MDkzXX0=
-->