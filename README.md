## Proyecto de Gestión de Facturas con JPA ##

Descripción
-----------
Este proyecto es una implementación de un sistema de gestión de facturas utilizando JPA (Java Persistence API) con Hibernate como implementación ORM. Utiliza la base de datos H2 para el almacenamiento en memoria.

El sistema permite registrar clientes, domicilios, artículos, categorías y facturas.

Características
---------------
- Persistencia de datos con JPA y Hibernate.
- Base de datos H2 para desarrollo y pruebas en memoria.
- Relaciones entre entidades como Cliente, Domicilio, Factura, Detalle de Factura, Artículo y Categoría.

Estructura de la Base de Datos
------------------------------
El sistema gestiona las siguientes tablas:

- Cliente: Información de los clientes.
- Domicilio: Datos del domicilio asociados a un cliente.
- Factura: Registro de las ventas realizadas, con referencias a los clientes y detalles de los productos vendidos.
- DetalleFactura: Detalles de cada artículo en una factura.
- Artículo: Productos vendidos, incluyendo su cantidad y precio.
- Categoría: Clasificación de los artículos.
- Relaciones: Tablas intermedias como articulo_categoria para relacionar artículos y categorías.

Tecnologías Utilizadas
----------------------
- Java 17.
- Gradle para la gestión de dependencias.
- JPA (Java Persistence API) para la gestión de la persistencia de datos.
- Hibernate como proveedor de JPA.
- Base de datos H2 para el almacenamiento en memoria.
