# R3DM/Enterprise — Colmena Enterprise OS UI

Prototipo de interfaz independiente para revisión visual e integración posterior.

## Vista previa local
Abre `index.html` en un navegador. No requiere dependencias ni servidor de desarrollo.

## Contenido
- `index.html`: dashboard responsive con estética grafito/negro y verde neón.
- `assets/r3dm-enterprise.svg`: logotipo vectorial y marca de agua de baja opacidad.

## Estado e integración
Esta rama contiene únicamente el prototipo de interfaz. No modifica el backend, la base de datos, Stripe, los servicios systemd ni el dominio de producción. Los indicadores y cifras están marcados como datos de referencia y no están conectados al API.

## Siguiente fase
Conectar cada panel a endpoints reales, gestionar estados de carga/error y validar permisos antes de integrar con Colmena Enterprise OS.
