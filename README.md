Gestión de Stock para la restauración

Introducción
¿Cuál es su funcionamiento?
Gestionar de manera automática el inventario que hay en el almacén de un restaurante y que automáticamente cree una lista de todo lo que es necesario comprar tambien de podria ver el stock actual por si se tiene una previsión muy fuerte de trabajo hacer un pedido mayor o en caso de que haya habido un problema de stock por un plato mal hecho, que sea erróneo o que no sea para venta al público. 

¿Funcionamiento interno de la Base de datos?
Para realizar este sistema de gestión de datos primero deberemos de introducir los datos por cada plato -> ingredientes, dentro de ingredientes -> cantidad en gramos o mililitros que lleva y los alérgenos de estos, también para cada ingrediente necesitaremos saber cuál es el proveedor que lo trae. Será necesario saber la capacidad máxima de producto que cabe para que no haya más de lo que se puede guardar, y necesitaremos saber la cantidad de producto que hay por paquete, bolsa o caja según cómo sea el pedido mínimo.
Con las bebidas también lo necesitaremos hacer en este caso es más sencillo por que a la bebida solo le añadiremos el proveedor y la capacidad máxima que caben para no hacer un sobre pedido también hay que definir la capacidad de bebidas por cada caja.

Una vez hecho esto nuestro sistema guardará las veces que se vende X producto para que una vez llegue al pedido mínimo lo guarde en un listado el cual se actualiza constantemente para posteriormente ver el pedido que hay que hacer.
En el caso de las bebidas es mucho más sencillo por que una bebida es una unidad pero hay que definir el stock por cajas para que una vez se llega a la cantidad de cada caja marque que hay que pedir una.

Objetivo
Nuestro objetivo es facilitar el trabajo de tener que estar semanalmente revisando stocks en almacén cámaras frigoríficas y neveras, también gracias a este proyecto el mantenimiento del stock se hace de manera mucho más efectiva ya que a la hora de revisarlo manualmente siempre se puede escapar algo en este caso nunca fallará ya y siempre los stocks estarán justos y no sería necesario realizar dos pedidos a una misma empresa por culpa de un mal conteo y por último ganaría muchísima agilidad a la horav de trabajar y ese tiempo perdido en el stock se podria invertir en cualquier otra cosa.
