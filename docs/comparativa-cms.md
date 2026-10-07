# Comparativa de gestores de contenidos

| | Joomla | Drupal |
|---|---|---|
| **Tipo de sitio para el que sirve** | Webs corporativas, revistas online, blogs de tamaño medio y tiendas. | Webs muy grandes, portales de universidades o de la administración pública. |
| **Licencia** | GPL | GPL |
| **Tiempo hasta ver la portada** | Unos 5 minutos | 2 o 3 minutos |
| **Dificultad del instalador (1-5)** | 2 (Bastante sencillo e intuitivo) | 3 (Fácil usando SQLite, pero pide más cosas) |
| **Base de datos que usa** | MariaDB / MySQL | SQLite, MySQL, MariaDB, PostgreSQL |
| **Imagen de Docker Hub** | `joomla` | `drupal` |

## ¿Qué gestor elegirías para cada caso y por qué?

1. **El blog de un club deportivo:**
   - **Elección:** Joomla.
   - **Razonamiento:** Es fácil de configurar y el panel de administración no es complicado. Para subir noticias de partidos, eventos o galerías de fotos sobra y basta, sin complicarse la vida como en Drupal.

2. **La web de una universidad, con muchos tipos de contenido:**
   - **Elección:** Drupal.
   - **Razonamiento:** Maneja mucho mejor estructuras de datos complejas. Una universidad necesita organizar fichas de asignaturas, carreras, profesores y noticias con distintos permisos de acceso, y en eso Drupal es bastante más potente.

3. **Una revista con secciones en varios idiomas:**
   - **Elección:** Joomla.
   - **Razonamiento:** Viene con el sistema multilingüe integrado de serie en el propio instalador, por lo que te permite traducir menús y artículos rápidamente sin necesidad de instalar plugins o módulos extra.
