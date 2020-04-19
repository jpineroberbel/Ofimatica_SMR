## EJERCICIO 8 - Bases de Datos
### Consultas de selección con parámetro.

Antes de realizar cada uno de estos ejercicios estudiar la distribución de información en tablas y las relaciones entre estas.

**A.** A partir de la **base de datos “[BIBLIO.mdb](http://descargas.teformas.com/Archivos%20Teformas/BIBLIO.accdb)”** realizar las siguientes **consultas con parámetro**:

1.  Título y año de publicaciónque contiene información sobre los libros de una biblioteca, realizar las siguientes **consultas**:

1.  Nombre, dirección y teléfono de las editoriales de Nueva York (New York).
2.  Nombre, dirección y teléfono de loas libros escritos por un aueditoriales del estado Massachusetts (MA).
3.  Nombre y año de nacimientor determinado los escritores nacidos antes de 1950.
24.  Título y año de publicación de los libros publicados por una determinada editorial (indicad el nombre de la compañía).

(Resultado en cantidad de registros: 1–Ej: “Blanc,Iris” 1, 2-Ej: “Que Corp” 162)

  
  

**B.** ls deNombre de los escritores   Nombre, dirección y teléfono de las editoriales con número de teléfono que empiece por 2.
7.  Nombre completo de los escritores que se llamen Michael.
8.  Título y año de publicación de los libros publicados recientemente (desde 1995) y que contengan la palabra “Access” en su titulo.

(Resultado en cantidad de registros: 1–18, 2-6, 3-5, 4-434, 5-28, 6-11, 7-11, 8-38)

  
  

**B.** La **BD “[Neptuno.mdb](http://descargas.teformas.com/Archivos%20Teformas/NEPTUNO.accdb)”** contiene información relativa a los pedidos de una empresa. Realizar las siguientes **consultas** sobre los datos allí almacenados en la **base de datos “[Neptuno.mdb](http://descargas.teformas.com/Archivos%20Teformas/NEPTUNO.accdb)”**:

1.  Precio y nombre de los productos enviados por una compañía de envíos en concreto. Mostrad la fecha del envío:

1.  Nombre, apellido y cargo de los empleados que estén trabajando desde antes del 1993 (El campo es de tipo fecha así que el criterio también debe realizarse con una fecha: 1/1/1993).
2.  Nombre de compañía, contacto, dirección y ciudad de los clientes a los que se les envió un pedido (fecha envío) en 1996. (¡Cuidado que el campo es de tipo fecha!)
3.  Nombre de contacto y teléfono de los proveedores de los productos con pocas unidades en existencia (<10). Incluid también el nombre del producto en la consulta.
4.  Nombre de los productos con un precio por unidad (tabla productos) de más de 30 dólares enviados a Alemania.
25.  Nombre y, apellidos y cargo de los empleados que han realizado un pedido para cierto cliente (ns de más de 100 unidades (campo cantidad en la tabla detalles de pedidos).
6.  Nombre de la compañía). Mostrad, contacto y teléfono de los clientes que han efectuado un pedido sin descuento (descuento = 0). Incluid también la fecha del pedido en la consulta.

(Resultado en cantidad de registros: 1–Ej: “Speedy Express” 643, 2-Ej: “Que Delícia” 93, 2-143, 3-12, 4-108, 5-13, 6-1317)

**C.** Realiza las siguientes **consultas** sobre la **base de datos [VIDEOCLUB](http://descargas.teformas.com/Archivos%20Teformas/VIDEOCLUB.accdb)** proporcionada por el profesor:

1.  Ident-dDvd y título de los dvd alquilados por cliente en concreto (solicitad el DNI). Incluid también la fecha de alquiler y devolución.
2.  Nsin devolver (Fecha devolución = nulo).
2.  DNI, nombre, dirección y, teléfono y correo electrónico de los clientes que han alquilado cierto Dvd.
3.  Ident-dvd y título de los dvd sin devolveralgún dvd el año 2001. (Cuidado que el campo fecha de alquiler es de tipo fecha).
3.  Título de los dramas del 1999, comedias de 1997 y de todas las películas del 2001.
4.  Nombre de unlos cliente concreto (solicitad el DNI). Incluid también la fecha de alquiler.
4.  Ident-dvd y título de los dvd de un género determinado.

(Resultado en cantidad de registros: 1–Ej: “11111111A” 2, 2-Ej: “AIR-1” 1, 3-Ej:”00000000J” 1, 4-Ej:”drama” 25s que han alquilado una película que se estrenó en 1997. Incluid también el título de la película.

(Resultado en cantidad de registros: 1–6, 2-38, 3-8, 4-4)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA5MTM2MDc4MiwtMTYxMjI4NDU5MSwtMT
AzOTUwMjcyXX0=
-->
