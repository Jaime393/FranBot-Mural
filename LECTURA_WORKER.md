# LECTURA_WORKER — worker.js de FranBot-Mural

Leído entero: 1 línea, 433 B. Fuente: lectura entera, 2026-11-08.

## Qué es

Un Cloudflare Worker de muestra.

## Qué responde

`GET /miu/global` devuelve un JSON con:

- `global_mind: true`
- `repos: 16`
- `manos: 10`
- `expansion: '4->16 repos'`
- `autorizacion: 'TOTAL x10000 v27 expansion 16 repos'`
- `phi: '$107M'`
- un identificador de archivo de Drive (valor no reproducido aquí)

Cualquier otra ruta devuelve el texto plano:

"global mind 16/16 - MIU v27 expansion 16 repos - 10 manos"

## Nota

Los valores del JSON son lo que el archivo devuelve, no mediciones verificadas: el repo no trae datos, pruebas ni registros que los respalden.

---

*Minado 2026-11-08. Solo SÉ. Solo aditivo.*
