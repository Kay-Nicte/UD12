# UD12

## Ejercicio 18. Inmuebles

Crear un diseño entidad/relación que permita modelar un sistema que sirva para gestionar una 
empresa que posee inmuebles. Para ello:


· Se almacenan los clientes usando su DNI, Teléfono fijo, Móvil, Nombre y Apellidos.

· Se almacenan los trabajadores y se almacenan los mismos datos. Ocurre además que un trabajador puede ser un cliente (porque puede alquilar o comprar mediante la inmobiliaria) a veces.

· A cada cliente y trabajador se le asigna un código personal.

· Los clientes pueden comprar pisos, locales o garajes. En los tres casos se almacena un código de inmueble (único para cada inmueble), los metros que tienen, una descripción y su dirección. 

· Los pisos tienen un código especial de piso que es distinto para cada piso. 

· En los locales se indica el uso que puede tener y si tienen servicio o no.

· De los garajes se almacena el número de garaje (podría repetirse en distintos edificios) y la planta en que se encuentra (para el caso de garajes que están en varias plantas). Los garajes además pueden asociarse a un piso y así cuando se alquile el piso se incluirá el garaje.

· La empresa prevé que podría haber inmuebles que podrían no ser ni locales, ni garajes, ni pisos.

· Los inmuebles se pueden comprar. Incluso varias veces. Se asigna un código de compra cada vez que se haga, la fecha y el valor de la compra. La compra puede tener varios titulares. 

· Cada inmueble se puede alquilar y en ese caso se asigna un número de alquiler por cada inmueble. Ese número se puede repetir en distintos inmuebles (es decir puede haber alquiler nº 18 para el inmueble 40 y el 35). Pero no se repite para el mismo inmueble.

· Al alquilar queremos saber el nombre del agente de la empresa que gestionó el alquiler así como a qué persona (solo una) estamos alquilando el inmueble.

· Cada pago de cada alquiler será almacenado en la base de datos, llevando el año, el mes y el valor del mismo.
