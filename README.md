# Presentación interactiva · Mesa Redonda 2

## Archivos
- `index.html`: estructura de las 16 diapositivas.
- `styles.css`: sistema visual responsive.
- `script.js`: navegación y simuladores.

## Uso
1. Descomprime el ZIP manteniendo los tres archivos en la misma carpeta.
2. Abre `index.html` en Chrome o Edge.
3. Usa `←` y `→` para navegar, `F` para pantalla completa y el botón ☷ para abrir el índice.
4. En móvil puedes avanzar deslizando horizontalmente.

No requiere servidor ni frameworks. La tipografía remota necesita conexión a internet; con conexión limitada se usarán fuentes de respaldo.

## Interacciones por diapositiva
1. Portada: escena ilustrativa del invernadero y presentación del proyecto.
2. Objetivos: selección OE1, OE2 y OE3.
3. MR1: exploración de AsyncIO, tmpfs y pivote al hardware.
4. Entorno: exploración de humedad, UV y continuidad eléctrica.
5. Estado del arte: pipeline metodológico interactivo.
6. Tareas: exploración de los cuatro hitos del OE2.
7. Sensores: selector de sonda PAR y AM2315C con especificaciones.
8. Esquema eléctrico: selección de nodos y explicación de conexiones.
9. Riel: control de posición de la estación.
10. Cámara: activar/desactivar capas del diseño.
11. Telemetría: recorrido paso a paso desde sensores a dashboard.
12. UPS: simulación de corte y restauración de red.
13. VPD: cálculo interactivo según temperatura y humedad.
14. Marco teórico: exploración de backend, frontend, UI/UX y AsyncIO.
15. Conclusiones: exploración de logros y próximos pasos.
16. Referencias y preguntas: marcadores para incorporar bibliografía real.

## Notas de rigor
- Los datos de demostración son ilustrativos, no lecturas reales.
- Los diagramas y simuladores explican el concepto; no accionan hardware.
- La simulación UPS no modela autonomía real ni curva de descarga.
- El rango VPD 0.8–1.2 kPa se reproduce como referencia indicada en el texto base, no como recomendación agronómica universal.
- Para el AM2315C se dejaron campos de especificación que deben completarse con la ficha técnica exacta; el texto fuente no entregó rangos.
- El texto base no incluyó referencias bibliográficas concretas: reemplazar los marcadores de la diapositiva 16 por la bibliografía real.
- Revisar que cada afirmación de avance (integración, conectividad, montaje y pruebas) corresponda a evidencia verificable de la MR2 antes de la defensa.
