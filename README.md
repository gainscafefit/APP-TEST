# app HORECA — prototipo Surtido

Prototipo clicable de una app de pedidos B2B entre proveedores de frescos y restaurantes.

- `index.html`: el prototipo completo en un solo archivo. Ábrelo en el navegador.
- `plantilla-catalogo.xlsx`: plantilla que descarga el proveedor para cargar su catálogo. Debe quedar en la misma carpeta que `index.html`.
- Todos los datos son de ejemplo: el catálogo de un fruver, 4 clientes y 8 semanas de pedidos generados.
- Las sugerencias de pedido, la clasificación de clientes y la previsión de compra usan las fórmulas del plan del MVP.

## Vistas

- **Restaurante:** pedido sugerido según su historial, inventario predictivo (cuánto le queda y hasta qué día le alcanza, con corrección que aprende su consumo), pregunta de cierre sobre el movimiento del día y best sellers con ingredientes por plato en Mi negocio, ajuste con + y −, confirmación, estado del pedido y recepción.
- **Proveedor:** pedidos para mañana con ajuste de peso real, alistamiento consolidado, clientes por segmento con alertas de riesgo y previsión de compra a 7 días.

## Siguiente paso

Reemplazar los datos de ejemplo por el catálogo y el historial del proveedor real del piloto, y pasar a Next.js + Supabase.
