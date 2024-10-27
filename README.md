# TiendaVirtual-Goncalves

[![Tienda-Online.jpg](https://i.postimg.cc/GpSGQpY5/Tienda-Online.jpg)](https://postimg.cc/4KVY4sW6)



---

# Base de datos para una Tienda Virtual

### Alumno: Christian Alejandro Goncalves Viloria

### Comisión: #59430

### Profesor: Anderson M. Torres

### Tutor: Nicolás Maugeri

---  

🌱 Problema: 

Una empresa de comercio electrónico llamada TiendaVirtual desea optimizar su gestión de inventario y mejorar su servicio al cliente. Actualmente, la empresa enfrenta dificultades para realizar un seguimiento preciso de sus productos, pedidos y clientes debido a la falta de un sistema centralizado y eficiente. Esto resulta en problemas como el agotamiento de existencias, retrasos en los envíos y dificultades para identificar los productos más vendidos.

---

⚡ Descripción del problema:

🌐 Dificultad para realizar un seguimiento preciso del stock de productos, lo que resulta en agotamientos frecuentes y exceso de inventario.
Falta de visibilidad sobre qué productos necesitan ser reabastecidos y cuáles están quedándose obsoletos en el almacén.
Retrasos en los Envíos:

🌐 Retrasos en el procesamiento y envío de pedidos debido a la falta de una gestión adecuada de los mismos.
Problemas en la coordinación con los proveedores para garantizar el suministro oportuno de productos.
Problemas en el Servicio al Cliente:

🌐 Dificultades para acceder a la información completa del cliente, lo que afecta la capacidad de proporcionar un servicio personalizado y resolver problemas de manera eficiente.
Insatisfacción del cliente debido a la falta de seguimiento adecuado de sus pedidos y el estado de los mismos.
Toma de Decisiones Deficiente:

🌐 Falta de datos precisos y actualizados para analizar las ventas, el rendimiento de los productos y las tendencias del mercado.
Dificultades para identificar los productos más vendidos y los clientes más valiosos.

---

⭐ Objetivo:

El objetivo es desarrollar una base de datos que permita a TiendaVirtual gestionar eficientemente su inventario, pedidos, clientes y otros aspectos clave del negocio. La base de datos debe proporcionar una forma fácil de rastrear el stock de productos, procesar y seguir pedidos, y almacenar información sobre los clientes para mejorar la experiencia del usuario y la toma de decisiones de la empresa.

---

✏️ Descripción de la Base de Datos - Tienda de Comercio Online

### La base de datos constará de las siguientes tablas principales:

✔️ Productos:

ID_Producto (Primary Key): Identificador único para cada producto.
Nombre: Nombre del producto.
Descripción: Descripción del producto.
Precio: Precio del producto.
Stock: Cantidad disponible en inventario.
ID_Categoría (Foreign Key): Identificador de la categoría a la que pertenece el producto.

✔️ Categorías:

ID_Categoría (Primary Key): Identificador único para cada categoría.
Nombre: Nombre de la categoría.
Descripción: Descripción de la categoría.

✔️ Clientes:

ID_Cliente (Primary Key): Identificador único para cada cliente.
Nombre: Nombre del cliente.
Correo_Electrónico: Correo electrónico del cliente.
Teléfono: Número de teléfono del cliente.
Dirección: Dirección del cliente.

✔️ Pedidos:

ID_Pedido (Primary Key): Identificador único para cada pedido.
ID_Cliente (Foreign Key): Identificador del cliente que realizó el pedido.
Fecha_Pedido: Fecha en que se realizó el pedido.
Total: Monto total del pedido.

✔️ Facturas:

ID_Factura (Primary Key): Identificador único para cada detalle de factura.
ID_Pedido (Foreign Key): Identificador del pedido al que pertenece el detalle.
ID_Producto (Foreign Key): Identificador del producto en el detalle del pedido.
Cantidad: Cantidad de producto en el pedido.
Precio: Precio del producto en el momento del pedido.

✔️ Proveedores:

ID_Proveedor (Primary Key): Identificador único para cada proveedor.
Nombre: Nombre del proveedor.
Contacto: Información de contacto del proveedor (teléfono, correo electrónico, dirección).

✔️ Trabajadores:

ID_Trabajador (Foreign Key): Identificador del trabajador.
Nombre:  Nombre del Trabajador.
Sueldo: Sueldo del Trabajador.

---

🌴 DER 



---
