# Kindle Sudoku — Compatibility Test

Prueba mínima para comprobar el navegador del Kindle Paperwhite 12.

## Qué comprueba
- Ejecución de JavaScript.
- Interacción táctil con un tablero 9×9.
- Botones 1–9 y borrar.
- Persistencia mediante localStorage.
- Recuperación del tablero al volver a abrir la página.

## Cómo probarlo
1. Publica `index.html` en GitHub Pages.
2. Abre la URL desde el navegador del Kindle.
3. Comprueba que JavaScript y localStorage indiquen `OK`.
4. Introduce varios números.
5. Pulsa `Guardar`.
6. Cierra completamente el navegador.
7. Vuelve a abrir la página.
8. Comprueba si los números siguen en el tablero.

Si esto funciona, el navegador tiene las capacidades básicas necesarias para desarrollar el Sudoku completo.
