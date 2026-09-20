# Web Plus — Prototipo demostrativo

Abre `index.html` o ejecuta `python -m http.server 8080` para probarlo como PWA.

Incluye catálogo y pedido web más un módulo de cotizaciones personalizadas: tipo de pastel, personas, tamaño, sabor, relleno, decoración, fecha/hora, texto, notas e imagen de referencia simulada. El flujo demostrativo es **Solicitud → Cotización → Aceptación → Anticipo → Pedido → Producción → Listo → Entrega → Liquidación**.

El panel administrativo muestra cotizaciones nuevas/pendientes, pedidos confirmados, anticipos, saldos y próximas entregas. Permite avanzar el flujo, registrar anticipo simulado y convertir una cotización en pedido. Los datos se guardan en `localStorage`.

## Reglas de fechas y horarios
Pedidos y cotizaciones no aceptan fechas pasadas. El horario máximo permitido para entrega o recolección es **20:00 h**; para el mismo día también se valida que la hora aún no haya pasado.
