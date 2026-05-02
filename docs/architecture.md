# Arquitectura

## Resumen

Proyecto backend HTTP con Express y TypeScript.

## Capas

1. `src/server.ts`: punto de entrada (arranque del servidor).
2. `src/app.ts`: composición de middlewares y rutas.
3. `src/routes/`: definición de endpoints.
4. `src/config/`: configuración y utilidades de entorno.

## Flujo de request

1. Llega request HTTP.
2. `app.ts` aplica middlewares base.
3. Se enruta al handler correspondiente.
4. Respuesta JSON al cliente.
