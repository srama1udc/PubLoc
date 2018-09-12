
# PubLoc
Trabajo de fin de grado en Ingeniería Informática por la rama de Ingeniería de Computadores.

Septiembre de 2018.

## Contenido del repositorio
Memoria del proyecto realizado.

## Resumen

El objetivo de este proyecto ha sido utilizar la ubicación de los teléfonos móviles como canal de comunicación entre comercios y clientes, intercambiando datos de posición por ofertas y descuentos, o por simples notificaciones acerca de productos disponibles a nuestro alrededor.

Los datos relativos a usuarios, tiendas y ofertas se almacenan en la nube. Se ha escogido la herramienta de *Google Firebase* por la flexibilidad que ofrece, la sencillez con la que podemos hacer peticiones, autenticarnos, dar permisos, almacenar imágenes e incluso ejecutar código.

Se ha desarrollado una aplicación móvil para dispositivos *iOS*, mediante la cual los clientes son avisados a medida que se aproximan a las tiendas con ofertas. No sólo está orientado a centros comerciales y grandes superficies, sino también a cualquier tipo de evento, feria o mercado.

Los usuarios tienen diferentes roles y permisos, de esta manera la aplicación presenta interfaces distintas para cada uno y así también se puedan delegar responsabilidades. Se ha decidido implementar una jerarquía clara: primero el administrador del sistema, seguido por los gerentes de los centros comerciales,  los propietarios de los comercios, los empleados y por último los clientes finales.

Como sistema de localización de interiores se ha empleado la tecnología de Situm, que, una vez calibrado un edificio, emplea los datos de los sensores (*GPS*, *Bluetooth BLE*, acelerómetros y *WiFi* ) para obtener la posición con un precisión unos dos metros. La precisión en *iOS* es menor, ya que no se tiene acceso a la información de la *WiFi*.

## Autor
Sergio Rodríguez Rama

### Contacto
<s.rama1@udc.es>