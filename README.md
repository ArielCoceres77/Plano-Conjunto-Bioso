# Lente Plano · Revisá tu lámina (Conjunto Biosol)

Realidad aumentada para revisar una lámina de dibujo técnico **mientras se dibuja**: compara en vivo la hoja del alumno con el Plano N.º 1 «Conjunto Biosol» (escala 1:10).

- En **verde**, lo que ya está dibujado en su lugar; en **rojo**, lo que falta o está corrido (tolerancia ≈ 0,8 mm).
- Con la mira se ve qué pieza es, sus medidas y cuánto le falta.
- Progreso por vista.

## Cómo funciona
La hoja se ubica con **11 marcadores ArUco** pegados (8 en los márgenes y 3 en huecos vacíos del plano), así sigue funcionando aunque el dibujo cambie y con trazos de lápiz suaves. Se calibra una sola vez llevando 4 puntos a 4 esquinas del dibujo.

## Archivos
- `index.html`: la app (un solo archivo, sin dependencias externas).
- `marcadores.png`: hoja A4 con los 11 marcadores para imprimir al 100 %.

Publicado en https://arielcoceres77.github.io/Plano-Conjunto-Bioso/
