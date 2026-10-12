# Chispa — aprender jugando

Plataforma educativa infantil en español con una identidad cálida de cielo, menta y coral, y una luciérnaga como personaje guía. Las aventuras se abren como vistas separadas y se organizan en cuatro submódulos explicativos y un examen final. Los siete cursos se pueden explorar libremente.

## Archivos

- `index.html`: portada, navegación y contenedores de la aplicación.
- `css/styles.css`: identidad visual, estados accesibles y diseño adaptable.
- `js/courses.js`: objetivos, materiales, submódulos, prácticas, exámenes y recursos audiovisuales de los siete cursos.
- `js/main.js`: catálogo, navegación, respuestas y guía docente; el avance es temporal y en memoria.

## Ejecutar

Abre `index.html` en un navegador moderno. También puedes iniciar un servidor local desde esta carpeta con `py -m http.server 8000` y abrir `http://localhost:8000`. No hay dependencias que instalar ni servidor de aplicación.

## Probar las aventuras

En la portada, pulsa **Comenzar** en una tarjeta disponible. Cada curso tiene cuatro submódulos con explicación y práctica, seguidos por un examen de cinco preguntas. Se aprueba con al menos cuatro aciertos; al aprobar, se muestra el resultado. Si no se aprueba, se puede repasar o volver a intentar. Prueba además **Ver guía docente**, los botones de regreso, el control de movimiento y el diseño en una ventana estrecha.

## Incluye

- Siete cursos: amarrar cordones, sumar, restar, multiplicar, dividir, cuidarse en internet y cuidar el planeta.
- Cada curso incorpora un recurso de video o una búsqueda temática de YouTube. YouTube y otros sitios requieren internet; un adulto debe acompañar su reproducción.
- Práctica con retroalimentación inmediata, exámenes finales, aprobación con 4/5, avance temporal en memoria y guía pedagógica.
- Diseño adaptable, controles de teclado, mensajes anunciados por lector de pantalla y respeto por movimiento reducido.
- El avance solo se conserva en memoria mientras la página está abierta. Al recargar o cerrar la página, se reinicia. No se usa almacenamiento local ni cuentas.

No requiere servidor. Un servidor sería necesario para sincronizar progreso, administrar usuarios o mostrar resultados de una clase.




