# Catálogo de Bolsiko

Las apps de Bolsiko (Android y iPhone) descargan `catalogo.json` al abrirse y guardan la última copia para usarla sin internet.

Aquí se cambian precios, colores, modelos, promociones, la galería y el número de WhatsApp. El cambio llega a las apps sin sacar otra versión.

- `negocio.whatsapp`: número con lada de país, solo dígitos (por ejemplo `524611234567`). Vacío = WhatsApp pide elegir el chat.
- `promociones`: aparecen entre `desde` y `hasta` (AAAA-MM-DD) y se quitan solas.
- `galeria`: cada trabajo es un diseño (`modelo`, `color`, `tinta`, `icono`, `nombre`, `nombre2`, `linea`) o una foto (`foto` con la URL de la imagen).
- Íconos disponibles: maiz, tortillas, trigo, pan, cruz, estrella, corazon, sol, flor, tienda, ninguno.
