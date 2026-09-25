# Actores del sistema

Antes de diseñar la arquitectura, identificamos quiénes interactúan con el Marketplace,
tanto personas como sistemas externos con los que se debe integrar.

| Actor | ¿Qué necesita realizar? |
|---|---|
| Cliente | Buscar productos, consultar información, agregar productos al carrito, realizar pedidos, efectuar el pago y consultar sus pedidos. |
| Seller | Ofrecer productos, registrar productos, actualizar productos, consultar sus productos y gestionar la información relacionada con sus ventas. |
| Administrador | Administrar la plataforma, gestionar sellers y supervisar el funcionamiento general del marketplace. |
| Pasarela de pago | Procesar los pagos generados por los pedidos. |
| Servicio de envío | Gestionar la información de entrega de los pedidos. |
| Servicio de Facturación | Generar los comprobantes de pago (boleta/factura). |
| ERP | Proporcionar información de productos y stock. |

**Nota:** los tres primeros (Cliente, Seller, Administrador) son actores humanos, mientras
que los cuatro últimos son sistemas externos con los que el Marketplace se integra.
