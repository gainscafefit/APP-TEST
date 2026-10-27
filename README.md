# app HORECA — prototipo Surtido

Prototipo clicable de una app de pedidos B2B entre proveedores de frescos y restaurantes.

- `index.html`: el prototipo completo en un solo archivo. Ábrelo en el navegador.
- `plantilla-catalogo.xlsx`: plantilla que descarga el proveedor para cargar su catálogo. Debe quedar en la misma carpeta que `index.html`.
- Mockup con datos de GAINS: 6 platos reales de gainscol.com (La Anabólica, Peak Fries, Mighty Birria, Primal Wings, Soda Probiótica y Tibbika) con sus ingredientes por plato, 10 proveedores por categoría (Tibbika como proveedor de prueba) y 8 semanas de pedidos generados desde el consumo del menú. Precios de proveedor, ventas por día y preparaciones son aproximados.
- Interfaz estilo iOS: barra de pestañas, títulos grandes, listas agrupadas, hojas que suben desde abajo, modo claro y oscuro.
- Las sugerencias de pedido, la clasificación de clientes y la previsión de compra usan las fórmulas del plan del MVP.

- Todos los textos están en español sencillo e informal, sin palabras técnicas.

## Vistas

- **Restaurante:** proveedores por categoría (en la app o por WhatsApp) con novedades por tipo, pedido sugerido por proveedor, ofertas, inventario predictivo, Cocina (crear receta con IA en 4 pasos: escribes el nombre y arma las preparaciones e ingredientes con gramos, todo editable, y la pone en una categoría según lo que lleva; la carta se ve por categorías; una tarea de 5 minutos al día en 3 pasos: cuánto lleva y cuánto cuesta cada plato, cuánto rinden tus salsas y bases, y cuánto botas de cada ingrediente), horario y cómo te fue cada día, e Invita y gana.
- **Proveedor:** clientes como inicio con estado del día y novedades, pedidos con ajuste de peso, qué alistar, ofertas (se vence pronto, feo pero bueno, me sobró), qué comprar para los próximos 7 días, Invita y gana y ajustes de entregas y catálogo.

## Siguiente paso

Reemplazar los datos de ejemplo por el catálogo y el historial del proveedor real del piloto, y pasar a Next.js + Supabase.
