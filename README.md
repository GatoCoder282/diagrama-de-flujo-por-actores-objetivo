# Procedimiento objetivo — agente autónomo DataX

Diagrama de flujo por actores (swimlane) del procedimiento propuesto, donde un
agente autónomo basado en modelos de lenguaje absorbe la clasificación manual,
la escritura/reparación de código y la verificación de vigencia hoy realizadas
por el desarrollador externo y el validador humano.

Carriles: Sistema de tickets, Agente autónomo (6 módulos internos), Suite de
pruebas automatizadas (sin cambios), Motor de ejecución, Apache Airflow (sin cambios).

## Ver el diagrama

`index.html` renderiza el diagrama con Mermaid y permite zoom/pan libre sin
pérdida de calidad (SVG). Abrir directamente en el navegador o desplegar en Netlify:

1. Conectar este repositorio en Netlify.
2. Build command: (vacío)
3. Publish directory: `.`

No requiere paso de build ni dependencias — es HTML estático que carga Mermaid
y svg-pan-zoom desde CDN.

## Editar el diagrama

El código Mermaid está embebido directamente en `index.html`, dentro del `div#diagram`.
También existe una copia independiente en `flujograma_agente.mmd` (carpeta TG1) para
edición rápida en [mermaid.live](https://mermaid.live).
