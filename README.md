# Examen segundo parcial POO

# Pedidos
Realiza el diseño de una aplicación para la gestión de pedidos. La aplicación deberá:
1. Administrar clientes (se guarda su nombre, dirección, teléfono y e-mail), que pueden realizar pedidos de productos, de los cuales se anota la cantidad en stock. Un cliente puede tener una o varias cuentas para el pago de los pedidos. Cada cuenta está asociada a una tarjeta de crédito.
2. Al realizar un pedido, un cliente puede realizar pedidos están asociados a una sola cuenta de pago. Además, sólo es posible realizar peticiones de productos en stock.
3. Existe una clase responsable del cobro, orden de distribución y confirmación de los pedidos. El cobro de los pedidos se hace una vez al día, y el proceso consiste en comprobar  todos los pedidos pendientes de cobro, y cobrarlos de la cuenta de pago correspondiente. Una vez que el pedido está listo para servirse, se ordena su distribución, y una vez entregado, pasa a estar confirmado.

# Instrucciones
- Realiza un diagrama de clases y añade los métodos necesarios para realizar pedidos de clientes, registra productos, pedidos y distribucion.
- Codifica en python el diagrama de clases que diseñaste
- Deberas subir al repositorio el diagrama de clases y el código que prueba que funciona el sistema.
  - Deberas probar que:
    - **Puedes registrar nuevos clientes, productos.**
    - **Realizar pedidos y mandarlos a distribución con sus diferentes estados.**

**NOTA: Toda la implementación puede ser en consola, no es necesario usar ni base de datos ni interfaz gráfica.**
**Sí usas BD e interfaz grafica podrias sumar puntos. Pero lo importante es el diagrama y que los metodos funcionen**
**Recuerda que necesitaras más que solo los métodos principales que se pide para probar**
