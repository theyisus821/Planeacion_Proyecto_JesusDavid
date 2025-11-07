# Plan de Actividades y Cronograma

## 1. Actividades Principales del Proyecto

| Actividad | Fechas Tentativas | Responsable | Entregable de Diseño Relacionado |
| :--- | :--- | :--- | :--- |
| **1. Definición de Requisitos** | 06/11 - 07/11 | [JesusDavid] (Analista) | Documento de Requisitos Funcionales y No Funcionales |
| **2. Diseño de Base de Datos** | 08/11 - 09/11 | [JesusDavid] (Diseñador) | Diagrama Entidad-Relación (DER) del sistema |
| **3. Desarrollo del API (CRUD Tareas)** | 10/11 - 15/11 | [JesusDavid] (Backend Dev) | Endpoints listos y probados (Swagger/Postman) |
| **4. Implementación de Interfaz de Usuario** | 16/11 - 22/11 | [JesusDavid] (Frontend Dev) | Mockups/Wireframes implementados en código |
| **5. Pruebas de Integración y Unitarias** | 23/11 - 25/11 | [JesusDavid] (QA) | Reporte de pruebas y cobertura de código |

---

## 2. Preguntas Reflexivas

### o ¿Qué dificultades encontraste al usar GitHub para planificar tu proyecto?
La principal dificultad fue la **disciplina en la granularidad**. Al ser un proyecto individual, es fácil querer hacer grandes bloques de trabajo. Sin embargo, GitHub exige dividir la planeación en **commits pequeños y lógicos** (un *commit* para el cronograma, otro para los responsables), lo cual es tedioso al principio, pero asegura un historial limpio.

### o ¿Qué beneficios te aportó GitHub para organizar las tareas y visualizar el avance?
El principal beneficio fue la **trazabilidad**. Al crear la rama `planeacion`, puedo trabajar en la estructura del proyecto de forma aislada. La herramienta me fuerza a **formalizar** el plan (con *commits* y *Pull Requests*), haciendo que el avance sea visible a través del historial de cambios, no solo una lista mental de tareas.

### o ¿Cómo podrías integrar el control de versiones en un entorno laboral real?
Se integraría como el **corazón de la colaboración**. En un entorno real:
* Cada **tarea (Issue)** del backlog de desarrollo se asignaría a una **rama**.
* Los desarrolladores usan **Pull Requests (PRs)** para solicitar la integración de su trabajo, lo que activa la **revisión de código** por parte de otros miembros.
* Se usarían ramas principales (como `main` para producción y `develop` para integración) para **gestionar diferentes entornos** (desarrollo, pruebas, producción), asegurando que solo el código estable llegue a los clientes.

### o ¿Qué aspectos del trabajo colaborativo aprendiste que podrías aplicar en el desarrollo de software dentro de un equipo profesional?
Aprendí la importancia crítica de **la revisión de código**. Aunque no hubo revisores reales, la necesidad de estructurar el trabajo para una futura PR me hizo escribir **mensajes de commit** más claros y **organizar** las modificaciones lógicas. En un equipo profesional, esto se traduce en **evitar que se integren errores** o código de baja calidad y en **compartir conocimiento** entre pares.
## FIN DE LA PLANEACION - PRUEBA GIT