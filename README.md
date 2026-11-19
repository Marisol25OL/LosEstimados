# EstimadosComerciantes

Aplicación web (PWA) para comercios de barrio: inventario, compras grupales con reparto de ganancias, ventas y ganancias, y asistente de voz en español (es-MX).

## Contenido
- `index.html`: aplicación completa y autocontenida.
- `manifest.json`: configuración para instalarla como app.
- `sw.js`: service worker para uso sin internet (opcional).

## Datos de acceso de prueba
| Dueño | Código | PIN | Correo | Contraseña |
|---|---|---|---|---|
| Don José (Abarrotes Don Pepe) | CB-101 | 1111 | jose@tiendita.mx | pepe1111 |
| Sra. Lupita (Miscelánea La Lupita) | CB-102 | 2222 | lupita@tiendita.mx | lupita22 |
| Doña Rosa (Tiendita El Sol) | CB-103 | 3333 | rosa@tiendita.mx | rosa3333 |

## Cómo usarla
Abre `index.html` en un navegador moderno, o súbela a un hosting estático (Netlify, Vercel, GitHub Pages).
Requiere internet la primera vez para cargar Tailwind, Dexie, JSZip y la fuente Inter desde sus CDN.
Los datos se guardan localmente en el dispositivo (IndexedDB con respaldo en localStorage).
