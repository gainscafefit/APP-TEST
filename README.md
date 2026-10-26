# app HORECA — prototipo Surtido

Prototipo clicable de una app de pedidos B2B entre proveedores de frescos y restaurantes.

- `index.html`: el prototipo completo en un solo archivo. Ábrelo en el navegador.
- `plantilla-catalogo.xlsx`: plantilla que descarga el proveedor para cargar su catálogo. Debe quedar en la misma carpeta que `index.html`.
- Mockup con datos de GAINS: 6 platos reales de gainscol.com (La Anabólica, Peak Fries, Mighty Birria, Primal Wings, Soda Probiótica y Tibbika) con sus ingredientes por plato, 10 proveedores por categoría (Tibbika como proveedor de prueba) y 8 semanas de pedidos generados desde el consumo del menú. Precios de proveedor, ventas por día y sub-recetas son estimados.
- Interfaz estilo iOS: barra de pestañas, títulos grandes, listas agrupadas, hojas que suben desde abajo, modo claro y oscuro.
- Las sugerencias de pedido, la clasificación de clientes y la previsión de compra usan las fórmulas del plan del MVP.

## Vistas

- **Restaurante:** lista de proveedores (en la app o por WhatsApp) con novedades accionables, pedido sugerido por proveedor, ofertas de sus proveedores, inventario predictivo de todo lo que compra, pregunta de cierre sobre el movimiento del día, best sellers con ingredientes por plato y programa Invita y gana.
- **Proveedor:** clientes como inicio con estado del día y novedades, pedidos con ajuste de peso real, alistamiento, ofertas (vence pronto, detalle visual, excedente), previsión de compra a 7 días, Invita y gana y ajustes de entregas y catálogo.

## Siguiente paso

Reemplazar los datos de ejemplo por el catálogo y el historial del proveedor real del piloto, y pasar a Next.js + Supabase.
