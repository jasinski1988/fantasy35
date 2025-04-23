# Guía para contribuir a Fantasy 35

¡Gracias por tu interés en contribuir a Fantasy 35! Este documento proporciona las directrices para colaborar en este proyecto educativo.

## Proceso para contribuir

1. **Fork del repositorio**
   - Haz click en el botón "Fork" en la parte superior derecha de esta página

2. **Clona tu fork**
   ```bash
   git clone https://github.com/TU_USUARIO/fantasy35.git
   cd fantasy35
   ```

3. **Crea una rama para tu contribución**
   ```bash
   git checkout -b nombre-de-tu-rama
   ```
   - Usa un nombre descriptivo para tu rama, por ejemplo: `añadir-armas-legendarias` o `corregir-calculo-daño`

4. **Haz tus cambios**
   - Implementa las mejoras o correcciones
   - Asegúrate de seguir las convenciones de código existentes
   - Añade comentarios donde sea necesario
   - Actualiza la documentación si corresponde

5. **Prueba tus cambios**
   - Asegúrate de que el código compila y funciona correctamente
   - Verifica que no has introducido nuevos errores

6. **Haz commit de tus cambios**
   ```bash
   git add .
   git commit -m "Descripción clara de los cambios realizados"
   ```

7. **Sube tus cambios a tu fork**
   ```bash
   git push origin nombre-de-tu-rama
   ```

8. **Crea un Pull Request**
   - Ve a la página original del repositorio
   - Haz click en "New Pull Request"
   - Selecciona tu rama
   - Describe tus cambios y por qué deberían ser incluidos

## Convenciones de código

- Utiliza camelCase para nombres de variables y métodos
- Utiliza PascalCase para nombres de clases
- Escribe comentarios para explicar código complejo
- Mantén los métodos pequeños y enfocados en una sola tarea
- Sigue el principio de responsabilidad única

## Tipos de contribuciones bienvenidas

- Corrección de bugs
- Nuevas características (armas, armaduras, mecánicas de juego)
- Mejoras de rendimiento
- Mejoras en la documentación
- Refactorización de código

## Proceso de revisión de código

Cuando envíes un pull request, el profesor u otros colaboradores revisarán tu código. Podría haber solicitudes de cambios o preguntas sobre tu implementación. Este proceso es normal y es una oportunidad para aprender y mejorar.

## Reporte de bugs

Si encuentras un bug, por favor crea un issue con la siguiente información:
- Descripción clara del problema
- Pasos para reproducirlo
- Comportamiento esperado vs. comportamiento actual
- Capturas de pantalla si aplica
- Cualquier otra información relevante

## Solicitud de nuevas características

Si tienes ideas para nuevas características, crea un issue describiendo:
- Qué quieres añadir
- Por qué sería útil para el juego
- Cómo piensas implementarlo

## Preguntas?

Si tienes dudas o necesitas ayuda, no dudes en crear un issue con la etiqueta "pregunta" o contactar al profesor directamente.

¡Gracias por contribuir a Fantasy 35!
