# Plantilla de prompts

Esta plantilla es una página HTML para generar prompts de texto mediante acordiones interactivos.

## ¿Qué incluye?

- Una interfaz responsive con secciones tipo acordeón.
- Opciones para completar cada parte del prompt:
  - Rol
  - Contexto
  - Público objetivo
  - Tarea
  - Objetivo
  - Tono
  - Formato
  - Restricciones
  - Ejemplos
  - Eficiencia
- Vista previa del prompt generada automáticamente.
- Botón para copiar el prompt al portapapeles.

## Estructura del archivo

- `plantilla-prompts.html`: contiene todo el proyecto en un solo archivo.
  - `<header>`: logotipo y cabecera.
  - `<main>`: título y diseño en dos columnas:
    - columna izquierda: acordeones de selección.
    - columna derecha: sección de vista previa.
  - `<footer>`: crédito de Factoría F5.
  - `<script>`: lógica de alternar acordeones, selección de opciones, generación de la vista previa y copia.

## Uso

1. Abre `plantilla-prompts.html` en tu navegador.
2. Selecciona una opción dentro de cada acordeón para construir tu prompt.
3. Observa cómo se genera el texto en la columna de vista previa.
4. Haz clic en `Copiar al portapapeles` para copiar el prompt completo.

## Desarrollo

1. Edita `plantilla-prompts.html`.
2. Actualiza los botones dentro de cada sección si deseas cambiar las frases.
3. Agrega o ajusta estilos en el bloque `<style>` dentro del archivo.
4. Prueba los cambios recargando la página en el navegador.

## Notas

- La plantilla funciona con HTML, CSS y JavaScript puro.
- En pantallas pequeñas, el diseño cambia a una sola columna para mantener la legibilidad.
