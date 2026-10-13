# 🧙 Mazmorra en Consola — Guía Interactiva del Proyecto Capstone

Guía visual e interactiva que acompaña el **Proyecto Final de Programación 1** (Jala University): un juego de mazmorra por turnos en Java que corre en la consola, donde el mapa es una matriz y el héroe se mueve según una cadena de comandos.

Esta página explica la especificación del proyecto (elementos del mapa, anatomía de un turno, reglas del jugador, comportamiento de los enemigos, estadísticas, puntaje, parámetros CLI y validaciones) y permite jugar un simulador en vivo en el navegador antes de implementarlo en Java.

## 🔗 Acceder a la guía

**[Abrir la guía interactiva →](https://zerchito.github.io/proyecto-capstone-mazmorra)**

> Reemplaza el enlace de arriba con la URL real una vez que actives GitHub Pages.

No necesitas instalar nada ni clonar el repositorio: solo abre el enlace desde cualquier navegador, computadora o celular.

## 📖 Qué incluye

- Descripción general del proyecto y tabla de los temas del curso que practica cada parte.
- Los 8 elementos del mapa (vacío, muro, jugador, enemigo, moneda, poción, trampa, salida) con su valor y su símbolo en consola.
- Los cinco pasos de cada turno, en orden.
- Reglas del jugador según la celda de destino, con ejemplos de antes y después.
- Enemigos: detección en el vecindario de 5 × 5, persecución, ataque y por qué hace falta una copia del mapa.
- Estadísticas en arreglos, historial de vida y fórmula del puntaje final.
- Tabla completa de parámetros de línea de comandos (`w`, `h`, `m`, `c`, `s`, `v`) y ejemplos de validación.
- Avances por semana.
- **Simulador interactivo:** ejecuta una cadena de comandos o juega turno a turno con los botones o las teclas W A S D X, en vista visual o de consola.
- Preguntas frecuentes sobre errores comunes de implementación.

## ▶️ Ejemplo de ejecución

```
java Mazmorra w=10 h=5 s=500 c=DDDSDSSDDWDDSSDD m=2004001#0110001040#0060300010#0410001500#0000100007
```

## ⚠️ Importante para estudiantes

El simulador de esta página es una **implementación de referencia independiente**, escrita en JavaScript solo para visualizar el comportamiento esperado del juego. **No es, ni reemplaza, la solución en Java** que deben entregar como proyecto. Úsenla para comparar el comportamiento de su propio programa y resolver dudas sobre las reglas, no como código fuente a copiar.

---

Jala University · Programación 1
