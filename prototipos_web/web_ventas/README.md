# Web de Ventas — Prototipo demostrativo

Abre `index.html` o usa `python -m http.server 8080` para ejecutarlo como PWA.

Incluye catálogo, categorías, buscador, ficha de producto, carrito, cantidades, subtotal/total, datos del cliente, entrega o recolección, confirmación, historial y panel administrativo de **PEDIDOS WEB** con estados Nuevo, Confirmado, Preparando, Listo, Entregado y Cancelado.

Los pedidos se guardan en `localStorage`, simulando la conexión con un POS.

## Reglas de pedidos
La fecha del pedido no puede ser anterior al día actual. La hora de entrega o recolección tiene un límite máximo de **20:00 h** y, si se elige el mismo día, debe ser una hora posterior a la actual.
