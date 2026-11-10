# Nivara Clean — Smart Industrial Supply (rescatado 6 nov 2026)

Tienda de suministros industriales con cotizador IA y portal de clientes. Proyecto Vercel `nivara-clean`.

## Páginas
- `index.html` — landing: "Línea Nivara", Cotizador IA, Portal Cliente.
- `cotizador.html` — "Generar Cotización Oficial" (Cotizador Inteligente).
- `login.html` + `registro.html` — acceso y registro de clientes.
- `portal.html` — Portal Cliente (con gráficas Chart.js).
- `ticket.html` — Ticket de Orden imprimible.
- `admin.html` — "Centro de Comando" (panel de administración).

## Producto
- `Nivara_ZeroX_Ficha.pdf` — ZEROX, removedor de óxido de alta eficiencia para limpieza textil: acción penetrante, control de dureza del agua, biodegradable, resultados inmediatos. Uso: aplicar directo, tallar, enjuagar.

## Automatización
- `n8n.bin` — flujo n8n: Webhook `prospeccion-nivara` → Pomelli → Google Sheets (prospección de clientes a hoja de cálculo).
- `AGENTS-2.md` — mejores prácticas de Vercel para agentes de código.

## FALTA
Los archivos JS/CSS propios (si los hay) y el backend/base de datos que muevan cotizaciones, pedidos y portal. Las páginas usan Tailwind CDN + Font Awesome.
