# Mi Odoo para la floristeria
En este repositorio encontramos todos los archivos del Odoo desarrollado en especial para una floristeria. Explicaremos cada parte con sus respectivas configuraciones.

## Creación de la empresa
He creado la compañía "Les Flors de Javi" la empresa de floristeria i decoración de mi padre. Con todos sus datos como la dirección, codigo postal, telefono y correo electrónico.

En base a esta empresa es que se va a crear toda la configuración.

## Descarga de modulos
He descargado los siguientes modulos:

-Inventario: Este modulo me permite crear almacenes de inventario para los productos.

-Contactos: Este modulo me permite crear contactos que se convertiran en proveedores o clientes, dependiendo del contacto.

-Compra: Este modulo me permite gestionar la compra de material o productos para la empresa, en base a los distintos proveedores creados como contactos.

-Facturacion: Este modulo me permite gestionar tanto las facturas de compra de material.

-Punto de venta: Este modulo seria el principal FrontEnd ya que es el modulo mas visible, en este, gestionaremos los pedidos de clientes, el pago. Y la autogeneración de la factura del cliente, la cual se puede imprimir al momento o enviar por correo. Existe la posiblidad de buscar esta factura por un apartado de la página que pide el codigo de la factura, el id y la fecha. Pero al funcionar en local no es muy util.

## Creación de Categorias:
Se han creado categorias de productos para subdividir estos de manera que este mas ordenado y accesible. Las categorias creadas son las siguientes:

-Arreglos florales.

-Ramos.

-Accesorios decorativos.

-Plantas de maceta.

-Flor Suelta.

## Creacion de Productos
Se han creado tantos como se ha creido necesario para que el sistema este lo mas completo posible. No solo eso sino que en cualquier apartado relacionado con los productos, o en los mismos pedidos puedes crear productos nuevos en base a la necesidad, con una interfaz agradable y sencilla de usar. Cabe recalcar que a estos productos se les pueden asignar factores especiales como: La necesidad de un almacenaje especial, la fecha de caducidad, ubicacion del almacenaje o colores especificos.

## Contactos
En el modulo de contactos, se crean entidades con su respectiva información necesario de contacto que se subdividen en 2:

-Proveedores: A los que podras realizar encargos para completar el stock, ademas de subir la factur, comprovar en la app todo el materia pedido y confirmar la llegada correcta del pedido o material del pedido defectuoso.

-Clientes: A los que les podras asociar productos en venta, facturas de sus pedidos o incluso unos creditos de compra para realizar descuento especiales en base a la frecuencia a la que viene a comprar.

## Inventario
En el apartado de inventario te permite gestionar la cantidad de material y productos que tienes en cada almacen que puedes crear en este mismo apartado. En estos almacenes puedes especificar si tiene algun factor especial en la descripcion, como por ejemplo: Si es una refrigerador...

## Compra
Este modulo te permite realizar pedidos de compra a los contactos proveedores y gestionar los gastos, procetanjes de pedidos con entrega a tiempo, fechas limite, gastos totales de los pedidos realizados en un mes...

## Facturación
En este apartado te permite ver las facturas asignadas a clientes, debido a que este puede haber elegido que se facture a una entidad empresarial o simplemente a su cuenta de cliente. Esto es debido a que es posible que el pago no se realice al momento. Esta funcion tambien te permite generar la factura, enviarla, gestionar si esta pendiente de pago o si el pago ya ha sido realizado.

## Tableros
Este apartado fue añadido automaticamente, y nos permite gestionar las finanzas y la logistica, de manera que nos muestra graficos como: el total facturado por mes, productos principalmente mas vendidos, comerciales principales o graficos de almacenamiento y logistica como: la cantidad de stock disponible i stock reservado.

## Punto de venta
Este es el apartado que mas va a utilizar nuestro cliente, debido a que es mayoritariamente el FrontEnd o el servicio mas utilizado. En este modulo podemos gestionar cajas registradoras a las que inicialmente les tendremos que indicar una cantidad especifica de efectivo. En este apartado empieza la gestion de pedidos de venta al cliente, donde tienes todos los metodos de pago, los productos a seleccionar, un apartado de facturacion a una entidad o incluso la creación de un nuevo producto en base a la necesidad situacional. Este modulo te permite llevar distintos pedidos, de manera que no es imprescindiblemente necesario terminar con un cliente para atender a otro. Una vez realizada una venta, este modulo autogenera una factura que puedes imprimir o descargar. En caso de que no se realice ningun de estas dos acciones anteriores, tambien se puede buscar la factura en un apartado de busqueda por id, código de factura y fecha de factura. A cada producto en venta se le puede asignar una nota, en caso de que te pidan un arreglo floral al gusto del artista; lo que es muy comun; no deberias de tener problema.



