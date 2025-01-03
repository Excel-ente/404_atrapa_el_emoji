# Página 404 con Juego Interactivo - "Atrapa el Logo"

## Descripción
Este proyecto implementa una página de error 404 que incluye un mini juego llamado **"Atrapa el Logo"** para entretener a los usuarios cuando intentan acceder a una página no disponible. 

El objetivo del juego es atrapar los logos que aparecen de forma aleatoria dentro de los "agujeros" antes de que desaparezcan. Los usuarios pueden guardar su puntuación, competir por los mejores resultados y cambiar la dificultad para personalizar la experiencia.

---

## Características
- **Juego interactivo:** Un juego de reacción donde el usuario debe hacer clic en los logos que aparecen aleatoriamente.
- **Selector de dificultad:** Tres niveles disponibles: `Noob`, `Intermedio`, y `Nashe`.
- **Puntuaciones altas:** Se almacenan las mejores puntuaciones en el navegador mediante `localStorage`.
- **Modo de espera:** Después de cada tres partidas, los usuarios deben esperar 30 segundos antes de jugar nuevamente.
- **Responsive:** Diseño optimizado para dispositivos móviles y de escritorio.

---

## Archivos Incluidos
- `index.html`: Página principal con el código del juego y estilos embebidos.
- **Recursos adicionales:** 
  - Una imagen para el logo (`mole`) cargada desde un URL externo.
  - Utiliza almacenamiento local del navegador para guardar y cargar las puntuaciones.

---

## Cómo Usar
1. **Abrir la página:** Accede a la página 404 desde un navegador compatible con HTML5 y JavaScript.
2. **Ingresar un nombre:** Escribe tu nombre en el campo de texto para registrar tu puntuación.
3. **Seleccionar la dificultad:** Escoge entre los tres niveles de dificultad disponibles.
4. **Iniciar el juego:** Haz clic en el botón "Iniciar Juego".
5. **Atrapar los logos:** Haz clic en los logos que aparecen antes de que desaparezcan para sumar puntos. 
6. **Guardar tu puntuación:** Al finalizar el juego, tu puntuación se guardará automáticamente si estás entre los 10 mejores.
7. **Revisar puntuaciones altas:** Visualiza las mejores puntuaciones en la tabla de "Mejores Puntuaciones".

---

## Controles
- **Iniciar juego:** Botón "Iniciar Juego".
- **Finalizar juego:** Botón "Terminar" disponible durante el juego.
- **Seleccionar dificultad:** Menú desplegable para elegir entre los niveles `Noob`, `Intermedio` y `Nashe`.

---

## Configuración de Dificultad
- `Noob`: Más fácil, los logos permanecen más tiempo visibles (1 segundo).
- `Intermedio`: Nivel intermedio con una duración de 750 ms.
- `Nashe`: Mayor dificultad con logos visibles por solo 350 ms.

---

## Requisitos del Sistema
- Navegador compatible con HTML5 y JavaScript (Chrome, Firefox, Edge, Safari).
- Resolución de pantalla mínima recomendada: 320px de ancho.
- Conexión a internet para cargar la imagen del logo (se puede personalizar para usar imágenes locales).

---

## Personalización
Puedes personalizar el juego modificando:
1. **Imagen del logo:** Cambia el valor de `background-image` en el estilo de la clase `.mole`.
2. **Niveles de dificultad:** Ajusta los valores de `moleInterval` en el JavaScript.
3. **Diseño visual:** Edita los estilos CSS incluidos en la etiqueta `<style>`.

---

## Futuras Mejora
- **Temporizador ajustable:** Permitir a los usuarios configurar la duración de la partida.
- **Compartir puntuaciones:** Integración con redes sociales para compartir resultados.
- **Modo multijugador:** Implementar sesiones con puntuaciones compartidas.

---

### ¡Que lo disfrutes!
