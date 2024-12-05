# Proyecto DAW - Desarrollo Web en Entorno Cliente

## Descripción de la Actividad

En esta actividad, cada grupo desarrollará una aplicación web del lado cliente que obtenga datos de una API pública gratuita. La aplicación deberá:

1. **Obtener un listado de elementos** (por ejemplo, productos, personajes, países, etc.) desde la API seleccionada.
2. **Mostrar ese listado en la página** principal, utilizando JavaScript para integrar los datos obtenidos mediante `fetch`.
3. **Al hacer clic en un elemento del listado, mostrar su detalle** (por ejemplo, imagen, descripción, atributos relevantes) sin recargar la página, manipulando dinámicamente el DOM.
4. **Validar formularios en el lado cliente**, si se añade algún formulario de filtrado o búsqueda (opcional, pero recomendado).

Esta aplicación se desarrollará con las tecnologías y metodologías vistas en clase (HTML, CSS, JS, comunicación asíncrona con `fetch`, manipulación del DOM, uso de una API externa, etc.).

## Pasos a seguir

1. **Clonar el repositorio inicial**: Contiene el `index.html`, `styles.css`, `script.js` y un ejemplo de `fetch` a la PokéAPI. Pueden modificar o reemplazar la API utilizada según sus intereses (ej.: [PokéAPI](https://pokeapi.co/), [The Rick and Morty API](https://rickandmortyapi.com/), [The Open Movie Database](http://www.omdbapi.com/) u otra que consideren interesante).

2. **Seleccionar una API gratuita**:  
   - Asegurarse de que la API permita acceso sin necesidad de claves complicadas.  
   - Leer la documentación de la API para saber qué endpoints usar para el listado (ej. `/characters`, `/items`, `/movies`) y para el detalle (ej. `/characters/{id}`).

3. **Mostrar el listado**:  
   - Utilizar `fetch` para obtener los datos.  
   - Crear elementos en el DOM para cada ítem (por ejemplo, un `<div>` con el nombre o imagen de cada elemento).  
   - Aplicar estilos básicos con `styles.css` o añadir vuestros propios estilos.

4. **Mostrar el detalle**:  
   - Al hacer clic en un elemento del listado, realizar una segunda petición `fetch` a la API para obtener más información del ítem seleccionado.  
   - Modificar el DOM dinámicamente para mostrar la información detallada (texto descriptivo, imágenes, datos específicos).

5. **Validación de formularios (opcional)**:  
   - Si se incluye un formulario de filtrado o búsqueda, validar el campo (por ejemplo, que no esté vacío) antes de enviar la solicitud.  
   - Mostrar mensajes de error o feedback al usuario en el DOM, sin recargar la página.

6. **Trabajo cooperativo**:  
   - Recordad asignar roles en el equipo (programador principal, tester, documentador, soporte técnico).  
   - Uso del repositorio (commits claros, trabajo en ramas si es necesario).  
   - Comunicación y revisión de código entre compañeros.

## Evaluación

- **Aspecto técnico**: correcta implementación de `fetch`, manipulación del DOM, validación de formularios, compatibilidad básica.  
- **Aspecto cooperativo**: reparto de roles, commits adecuados, documentación en comentarios, README mejorado.  
- **Presentación final**: se valorará la claridad en la explicación oral del proyecto, justificando las decisiones tomadas y mostrando las funcionalidades desarrolladas.

## Recomendaciones

- Revisar la documentación de la API antes de empezar.  
- Empezar mostrando el listado en consola (`console.log`) antes de pintar en el DOM, para asegurar que los datos se obtienen correctamente.  
- Añadir pequeñas mejoras estéticas (CSS) para hacer la aplicación más atractiva.  
- Aprovechar el feedback del docente y del grupo para refinar el código.

¡Adelante con la actividad y mucha suerte con el proyecto!