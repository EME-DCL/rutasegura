# RutaSegura — Sistema de transporte escolar

Sitio de presentación del proyecto **RutaSegura**: plataforma web y móvil de gestión y trazabilidad del transporte escolar (25 furgones, ~450 estudiantes diarios).

Proyecto académico de **Ingeniería de Requisitos (RQY1101)**, Evaluación N°2, Sección 005D, Grupo N°5.

- **Integrantes:** Mariano Cornejo (Scrum Master y Product Owner) y Maximiliano Herrera (Equipo de Desarrollo)
- **Docente:** Rocío Contreras Aguila

## Contenido

Aplicación de una sola página (`index.html`) con HTML, CSS y JavaScript puro, sin frameworks:

- Hero, introducción, KPIs y métricas animadas
- Ámbito y límites, perspectiva del producto, funciones (FE) y usuarios
- Requisitos funcionales (RF) filtrables y no funcionales (RNF) por categoría
- Planificación Scrum: equipo, 5 sprints y Definition of Done
- Historias de usuario (HU) con criterios de aceptación y filtros
- Product Backlog ordenable y estimación con Planning Poker (gráfico SVG)
- Conclusiones, footer e historial de versiones

Incluye modo claro/oscuro, navegación por anclas, animaciones respetuosas de `prefers-reduced-motion` y accesibilidad AA (Lighthouse: 100 en Accesibilidad y Buenas prácticas).

## Vistas de usuario (prototipo)

`vistas.html` es un prototipo navegable con las cuatro vistas del sistema, enlazado desde la landing:

- **Administrador** (escritorio): ocupación de furgones y bloqueo de asignaciones al 100% de capacidad.
- **Conductor** (móvil): inicio de recorrido y marcaje de abordajes con botones de 48 px, incluido el modo offline con cola SQLite.
- **Apoderado** (móvil): mapa con ETA, informe de ausencia y alerta push por retraso.
- **Asistente de transporte** (móvil): lista delegada sincronizada con la vista del conductor.

Cada pantalla indica los RF y HU que demuestra y ofrece un recorrido guiado con datos simulados.

## Uso

Abre `index.html` en el navegador, o visita la versión publicada en GitHub Pages.

- Landing: <https://eme-dcl.github.io/rutasegura/>
- Prototipo: <https://eme-dcl.github.io/rutasegura/vistas.html>
