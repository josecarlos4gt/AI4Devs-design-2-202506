# Desarrollo de un Sistema ATS (Applicant Tracking System)

A continuación, se detalla las historias de usuario iniciales del sistema.

---

## 1. Historias de usuario - Sistema ATS

Principales historias de usuario del sistema ATS.


### User Story 1: El Reclutador Organizado

Como un **Reclutador** que gestiona múltiples vacantes a la vez, quiero **recibir y visualizar todas las postulaciones de diferentes portales (LinkedIn, página de carreras, etc.) en un único listado centralizado** para poder **dejar de revisar múltiples buzones de correo y plataformas, y así evitar que se pierdan candidatos valiosos en el proceso**.

---

### User Story 2: El Gerente de Contratación

Como un **Gerente de Departamento**, quiero **recibir una notificación para revisar y aprobar la descripción de una nueva vacante directamente en la plataforma** para poder **asegurar que los requisitos y responsabilidades del puesto están perfectamente alineados con las necesidades de mi equipo antes de que la oferta sea publicada**.

---

### User Story 3: El Candidato Informado

Como un **Candidato** que se ha postulado a un empleo, quiero **recibir notificaciones automáticas por correo electrónico sobre los cambios de estado de mi aplicación (ej: "Recibido", "En revisión", "Invitado a entrevista")** para poder **conocer en qué etapa del proceso me encuentro y tener una experiencia de postulación transparente y profesional, sin importar el resultado**.

---

### User Story 4: El Reclutador Eficiente

Como un **Reclutador** con una vacante que tiene más de 200 aplicantes, quiero **filtrar rápidamente la lista de candidatos usando criterios específicos como "años de experiencia", "habilidades clave" o "ubicación"** para poder **identificar y enfocar mi tiempo en los perfiles más calificados y así acelerar el tiempo de contratación**.

---

### User Story 5: El Director de RRHH Estratégico

Como un **Director de Recursos Humanos**, quiero **generar un reporte visual que me muestre qué canal de reclutamiento (página de carreras, portal de empleo X, referidos) genera la mayor cantidad de candidatos contratados** para poder **optimizar la inversión del presupuesto de reclutamiento en las fuentes más efectivas**.

---

## 2. Product Backlog Priorizado - Sistema ATS

Este documento representa el Product Backlog inicial para el desarrollo del Sistema ATS. Contiene las historias de usuario clave que definen la funcionalidad inicial y están priorizadas para guiar el desarrollo de un Producto Mínimo Viable (MVP) que aporte valor desde el primer momento.

---

### 2.1. Backlog sin Priorizar

Antes de aplicar las metodologías, aquí están las 5 historias de usuario que componen nuestro backlog inicial:

* **US1:** Como **Reclutador**, quiero **recibir todas las postulaciones en un único listado** para **evitar revisar múltiples plataformas y no perder candidatos**.
* **US2:** Como **Gerente**, quiero **revisar y aprobar vacantes** para **asegurar que se alinean con las necesidades de mi equipo**.
* **US3:** Como **Candidato**, quiero **recibir notificaciones automáticas sobre el estado de mi aplicación** para **tener una experiencia transparente y profesional**.
* **US4:** Como **Reclutador**, quiero **filtrar la lista de candidatos con criterios específicos** para **identificar rápidamente a los más calificados**.
* **US5:** Como **Director de RRHH**, quiero **generar un reporte de efectividad de canales de reclutamiento** para **optimizar la inversión del presupuesto**.

---

### 2.2. Priorización con el Método MoSCoW

#### Explicación de la Metodología

El método MoSCoW es una técnica de priorización que ayuda a las partes interesadas a entender la importancia de cada requisito, clasificándolos en cuatro categorías. Es ideal para alinear expectativas sobre lo que se incluirá en una versión o lanzamiento específico, como un MVP.

* **Must-have (Debe tener):** Crítico para el lanzamiento actual. Sin este requisito, el producto no es viable.
* **Should-have (Debería tener):** Importante, pero no vital para el lanzamiento. El producto funcionará sin él, pero será menos valioso.
* **Could-have (Podría tener):** Deseable, pero menos importante. Afectará poco al producto si se deja fuera. Son los primeros en descartarse si el tiempo es limitado.
* **Won't-have (No tendrá):** Se acuerda explícitamente que no se incluirá en el lanzamiento actual, pero podría considerarse para el futuro.

#### Backlog Priorizado con MoSCoW

##### **M - Must-have (Indispensable para el MVP)**

* **US1: Listado Centralizado de Postulaciones.**
    * **Justificación:** Esta es la función central del sistema. Resuelve el principal problema de desorganización y pérdida de información. Sin esto, el producto no cumple su promesa de valor fundamental de "unificar" el proceso.
* **US4: Filtro Rápido de Candidatos.**
    * **Justificación:** Un listado sin filtros no es mucho más útil que una bandeja de entrada. La capacidad de filtrar es lo que aporta la "optimización" y la "reducción de tiempo". Es indispensable para que el reclutador perciba el valor del sistema.

##### **S - Should-have (Importante post-MVP)**

* **US3: Notificaciones Automáticas al Candidato.**
    * **Justificación:** Mejora significativamente la "Experiencia del Candidato", lo cual es un diferenciador clave. Aunque el sistema puede funcionar sin esto para el reclutador, es una funcionalidad de alto impacto que debería seguir inmediatamente al MVP para profesionalizar la herramienta.
* **US2: Flujo de Aprobación de Vacantes por Gerentes.**
    * **Justificación:** Esencial para el segmento de clientes "Departamentos de RRHH Corporativos". Sin embargo, las "PyMEs" o "Startups" (los *Early Adopters*) podrían no necesitarlo al principio. Puede ser un requisito para una versión "Profesional" o "Enterprise", pero no para el MVP inicial.

##### **C - Could-have (Deseable a futuro)**

* **US5: Reporte de Efectividad de Canales.**
    * **Justificación:** Aporta un enorme valor estratégico, alineado con la "Analítica y Reportes". Sin embargo, es una función avanzada que requiere una cantidad significativa de datos acumulados para ser útil. Se enfoca en la optimización a largo plazo, no en la funcionalidad operativa del día a día del MVP.

---

### 2.3. Priorización con la Matriz de Valor vs. Esfuerzo

#### Explicación de la Metodología

Esta matriz visual clasifica las tareas en una cuadrícula de 2x2. El eje vertical representa el "Valor" (impacto en el cliente, negocio o usuario) y el eje horizontal el "Esfuerzo" (complejidad, tiempo y costo de desarrollo). Ayuda a identificar las tareas más estratégicas.

* **Quick Wins (Alto Valor, Bajo Esfuerzo):** Prioridad máxima. Generan gran satisfacción con poco trabajo.
* **Big Bets (Alto Valor, Alto Esfuerzo):** Grandes proyectos que son la base del producto. Deben planificarse cuidadosamente.
* **Fill-ins (Bajo Valor, Bajo Esfuerzo):** Tareas que se pueden hacer si hay tiempo, pero no son prioritarias.
* **Money Pits / Time Sinks (Bajo Valor, Alto Esfuerzo):** Tareas que deben evitarse.

#### Backlog Priorizado con Valor vs. Esfuerzo

| User Story                               | Valor (1-5) | Esfuerzo (1-5) | Cuadrante      | Justificación                                                                                                                                                                                                    |
| ---------------------------------------- | :---------: | :------------: | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **US1:** Listado Centralizado            |      5      |       4        | **Big Bet** | Es la funcionalidad con más valor, pero requiere un esfuerzo considerable (integraciones, base de datos robusta, CV parsing). Es la base del producto.                                                  |
| **US4:** Filtro de Candidatos            |      5      |       3        | **Big Bet** | Valor igual de alto que US1, ya que habilita la eficiencia. El esfuerzo es ligeramente menor porque se construye sobre la base de datos ya creada por US1.                                                    |
| **US3:** Notificaciones al Candidato     |      4      |       2        | **Quick Win** | Aporta mucho valor a la marca y la experiencia del candidato. El esfuerzo es relativamente bajo si se usa un servicio de email de terceros (ej. SendGrid), como se sugiere en la arquitectura. |
| **US2:** Flujo de Aprobación             |      3      |       4        | **Money Pit** | El valor es moderado (solo para ciertos segmentos de cliente), pero el esfuerzo es alto (requiere gestión de roles, estados y notificaciones complejas entre usuarios). No es estratégico para el inicio. |
| **US5:** Reporte de Efectividad de Canales |      4      |       5        | **Big Bet** | Aporta un alto valor estratégico, pero es la tarea de mayor esfuerzo. Requiere un motor de analítica, almacenamiento de datos históricos y una interfaz de visualización compleja.            |

---

### 2.4. Recomendación del Experto

Ambas metodologías ofrecen una perspectiva valiosa, pero para la etapa actual del proyecto (definir un Producto Mínimo Viable para atraer a los *Early Adopters*), mi recomendación es utilizar el **Método MoSCoW**.

**La metodología MoSCoW genera mayor valor al sistema en esta fase inicial por las siguientes razones:**

1.  **Claridad Absoluta para el MVP:** MoSCoW es directo y no deja lugar a ambigüedades. Las historias clasificadas como **"Must-have" (US1 y US4) constituyen, sin duda alguna, el corazón del MVP**. Esto alinea a todo el equipo y a los stakeholders en un objetivo común y alcanzable.
2.  **Enfoque en la Viabilidad del Producto:** La pregunta fundamental que responde MoSCoW es "¿Podemos lanzar sin esto?". Esto obliga a centrarse en la funcionalidad mínima que resuelve el problema principal del cliente, lo cual es crucial para validar el modelo de negocio rápidamente.
3.  **Simplicidad en la Comunicación:** Es más fácil comunicar a un inversor o a un gerente que "el MVP incluirá estas dos funcionalidades indispensables" que explicar los matices de una matriz de Valor vs. Esfuerzo, la cual puede ser más subjetiva en la estimación del "Esfuerzo" sin tener un equipo técnico que lo valide en detalle.

Mientras que la matriz de Valor vs. Esfuerzo es una herramienta excelente para refinar la priorización (por ejemplo, para decidir qué "Should-have" abordar primero), **MoSCoW es superior para trazar la primera línea en la arena y definir el alcance del producto con el que saldrás al mercado.**

---

## 3. Desglose de Tickets Técnicos para US1: Listado Centralizado de Postulaciones

A continuación, se presentan los tickets de trabajo técnicos, tanto de Backend como de Frontend, necesarios para completar la historia de usuario. Estos tickets están diseñados para ser asignados al equipo de desarrollo y ejecutados en los primeros sprints.

---

### Ticket 1/5 (Backend)

* **Título:** BE - Diseño e Implementación del Esquema de Base de Datos para Aplicaciones
* **Descripción:** Crear las tablas necesarias en la base de datos PostgreSQL del "Servicio de Aplicaciones" para almacenar la información de los candidatos, sus postulaciones y documentos asociados. Este esquema es la base para toda la funcionalidad de gestión de aplicaciones.
* **Criterios de Aceptación:**
    * Las tablas `Candidate`, `Application` y `Document` se crean en la base de datos siguiendo el modelo ERD definido en el documento del proyecto.
    * Las relaciones (claves foráneas) entre `Application` y `Candidate`, y entre `Application` y `Vacancy` están correctamente implementadas.
    * Los tipos de datos de las columnas coinciden con las especificaciones (ej. UUID para IDs, Timestamp para fechas).
* **Prioridad:** Alta
* **Estimación:** 3 puntos de historia
* **Asignado a:** Equipo de Backend
* **Etiquetas:** `Backend`, `Base de Datos`, `Sprint 1`, `AppSvc`
* **Comentarios:** Este es un ticket habilitador y bloquea el desarrollo de los endpoints de la API.
* **Enlaces:** LTI-JF.md (Sección 6: Modelo de datos)
* **Historial de Cambios:**
    * 07/07/2025: Creado por Product Manager

---

### Ticket 2/5 (Backend)

* **Título:** BE - Implementación de Endpoint para Recepción de Postulaciones
* **Descripción:** Desarrollar un endpoint de API en el "Servicio de Aplicaciones" que permita recibir nuevas postulaciones. Este endpoint debe procesar los datos del candidato y su CV, creando los registros correspondientes en la base de datos y almacenando el archivo.
* **Criterios de Aceptación:**
    * Existe un endpoint `POST /applications` en el `AppSvc` que acepta datos de candidato y un archivo (CV).
    * Al recibir una petición válida, se crea un nuevo registro en la tabla `Candidate` (o se asocia a uno existente si el email ya existe).
    * Se crea un nuevo registro en la tabla `Application`, vinculando al candidato y a la vacante.
    * El CV adjunto se almacena correctamente en el bucket de AWS S3/GCS designado.
    * Un nuevo registro se crea en la tabla `Document` con la URL del CV almacenado en S3.
* **Prioridad:** Alta
* **Estimación:** 8 puntos de historia
* **Asignado a:** Equipo de Backend
* **Etiquetas:** `Backend`, `API`, `Sprint 1`, `AppSvc`, `S3`
* **Comentarios:** La gestión de archivos multipart/form-data es clave. Considerar la validación del tamaño y tipo de archivo.
* **Enlaces:** LTI-JF.md (Sección 6: Diseño del sistema a alto nivel)
* **Historial de Cambios:**
    * 07/07/2025: Creado por Product Manager

---

### Ticket 3/5 (Backend)

* **Título:** BE - Implementación de Endpoint para Visualización de Postulaciones
* **Descripción:** Crear un endpoint `GET` en el "Servicio de Aplicaciones" que devuelva un listado paginado de todas las postulaciones asociadas a una vacante específica. Esta API será consumida por el frontend para mostrar la lista al reclutador.
* **Criterios de Aceptación:**
    * Existe un endpoint `GET /vacancies/{vacancyId}/applications`.
    * El endpoint devuelve una lista de objetos de postulación en formato JSON.
    * Cada objeto en la lista contiene información resumida del candidato (nombre, email, fecha de postulación, estado).
    * La respuesta debe estar paginada para manejar grandes volúmenes de datos.
* **Prioridad:** Alta
* **Estimación:** 5 puntos de historia
* **Asignado a:** Equipo de Backend
* **Etiquetas:** `Backend`, `API`, `Sprint 1`, `AppSvc`
* **Comentarios:** Asegurar que el endpoint sea eficiente y no realice un N+1 query a la base de datos.
* **Enlaces:** LTI-JF.md (Sección 6: Modelo de datos)
* **Historial de Cambios:**
    * 07/07/2025: Creado por Product Manager

---

### Ticket 4/5 (Frontend)

* **Título:** FE - Construcción de la Vista de Listado de Candidatos
* **Descripción:** Desarrollar el componente de UI en la SPA (React/Vue) que muestre la tabla o lista de candidatos para una vacante seleccionada. Este componente consumirá el endpoint `GET /vacancies/{vacancyId}/applications`.
* **Criterios de Aceptación:**
    * Al navegar a la página de una vacante, se realiza una llamada a la API para obtener la lista de postulaciones.
    * Los datos se muestran en una tabla con columnas para: Nombre del Candidato, Fecha de Postulación, Estado Actual, y un botón de "Ver Detalles".
    * Se muestra un estado de "Cargando..." mientras se obtienen los datos.
    * Se manejan correctamente los casos de error (ej. si la API falla) y el caso de una lista vacía.
* **Prioridad:** Alta
* **Estimación:** 5 puntos de historia
* **Asignado a:** Equipo de Frontend
* **Etiquetas:** `Frontend`, `UI`, `Sprint 1`, `React`
* **Comentarios:** La tabla debe ser responsiva para visualizarse correctamente en diferentes tamaños de pantalla.
* **Enlaces:** LTI-JF.md (Sección 6: Diseño del sistema a alto nivel)
* **Historial de Cambios:**
    * 07/07/2025: Creado por Product Manager

---

### Ticket 5/5 (Backend)

* **Título:** BE - Implementación de CV Parsing Básico
* **Descripción:** Integrar una funcionalidad en el "Servicio de Aplicaciones" que, tras la subida de un CV, intente extraer automáticamente información básica y estructurarla. La información a extraer inicialmente será el nombre, email y teléfono del candidato para autocompletar su perfil.
* **Criterios de Aceptación:**
    * Cuando se sube un nuevo CV a través del endpoint `POST /applications`, se activa un proceso de parsing.
    * El parser extrae correctamente el nombre completo, la dirección de correo electrónico y el número de teléfono del documento (PDF o DOCX).
    * Los campos extraídos se utilizan para rellenar el perfil del `Candidate` en la base de datos si estos no venían en la petición inicial.
* **Prioridad:** Media
* **Estimación:** 8 puntos de historia
* **Asignado a:** Equipo de Backend
* **Etiquetas:** `Backend`, `CV Parsing`, `Sprint 2`, `AppSvc`
* **Comentarios:** Este ticket tiene una prioridad ligeramente menor que los demás, ya que la funcionalidad básica puede operar sin él (con entrada manual de datos), pero es clave para la automatización. Investigar librerías de terceros (ej. Apache Tika) para acelerar el desarrollo. Se planifica para el siguiente sprint para no bloquear el flujo principal del MVP.
* **Enlaces:** LTI-JF.md (Sección 3: Recepción y Gestión de Aplicaciones)
* **Historial de Cambios:**
    * 07/07/2025: Creado por Product Manager
	
---

## 4. Estimación de Esfuerzo para Tickets de Trabajo (US1)

A continuación, se presenta la estimación de esfuerzo para los tickets de trabajo previamente definidos, utilizando diferentes metodologías ágiles.

**Descargo de Responsabilidad sobre la Estimación en Horas:** La práctica recomendada es usar puntos de historia abstractos. La conversión a horas es una aproximación para fines de planificación inicial y no debe ser tratada como un compromiso de tiempo exacto. Para este ejercicio, asumiremos una equivalencia de **1 Punto de Historia ≈ 4-6 horas de trabajo de desarrollo enfocado**.

---

### 4.1. Estimación con Fibonacci (usando Planning Poker)

#### Explicación de la Metodología

El Planning Poker es una técnica colaborativa donde el equipo de desarrollo discute cada ticket y cada miembro vota en privado su estimación usando cartas con la secuencia de Fibonacci (1, 2, 3, 5, 8, 13...). Si las estimaciones varían mucho, se discuten las razones (el "porqué" de la estimación) hasta llegar a un consenso. Esto fomenta la comunicación y comparte el conocimiento técnico.

#### Estimación de Tickets

| Ticket                                    | Estimación (Puntos) | Estimación (Horas Aproximadas) |
| ----------------------------------------- | :-----------------: | :----------------------------: |
| **1. BE - Esquema de Base de Datos** |          3          |           12 - 18 horas            |
| **2. BE - Endpoint de Recepción** |          8          |           32 - 48 horas            |
| **3. BE - Endpoint de Visualización** |          5          |           20 - 30 horas            |
| **4. FE - Vista de Listado de Candidatos** |          5          |           20 - 30 horas            |
| **5. BE - CV Parsing Básico** |          8          |           32 - 48 horas            |
| **Total Estimado** |     **29 Puntos** |        **116 - 174 Horas** |

---

### 4.2. Estimación con Tallas de Camiseta (T-Shirt Sizing)

#### Explicación de la Metodología

Esta es una técnica de estimación más rápida y de alto nivel. En lugar de números, el equipo asigna una "talla" (XS, S, M, L, XL) a cada tarea. Es excelente para una primera pasada rápida del backlog o para estimar funcionalidades muy grandes (Epics). Para convertirlo a un valor más concreto, cada talla se puede mapear a un número de puntos de historia.

#### Estimación de Tickets

Para mantener la consistencia, mapearemos las tallas a los puntos de Fibonacci estimados previamente.

* **S:** 2-3 Puntos
* **M:** 5 Puntos
* **L:** 8 Puntos
* **XL:** 13+ Puntos

| Ticket                                    | Talla de Camiseta | Puntos Equivalentes | Estimación (Horas Aproximadas) |
| ----------------------------------------- | :---------------: | :-----------------: | :----------------------------: |
| **1. BE - Esquema de Base de Datos** |         S         |          3          |           12 - 18 horas            |
| **2. BE - Endpoint de Recepción** |         L         |          8          |           32 - 48 horas            |
| **3. BE - Endpoint de Visualización** |         M         |          5          |           20 - 30 horas            |
| **4. FE - Vista de Listado de Candidatos** |         M         |          5          |           20 - 30 horas            |
| **5. BE - CV Parsing Básico** |         L         |          8          |           32 - 48 horas            |

---

### 4.3. Recomendación del Experto

#### ¿Qué metodología genera una estimación más adecuada para un equipo inexperto?

Para un equipo que es inexperto y cuyas estimaciones no son muy acertadas, la metodología que genera mayor valor y una estimación más adecuada a largo plazo es, sin duda, el **Planning Poker con la secuencia de Fibonacci**.

**Justificación:**

1.  **Fomenta la Conversación y el Aprendizaje:** El verdadero poder del Planning Poker no está en el número final, sino en la **discusión que se genera cuando hay estimaciones muy diferentes**. Un desarrollador junior podría votar "13" para una tarea que un senior vota como "5". La conversación que sigue ("¿Qué riesgos ves que yo no estoy viendo?" o "¿Conoces esta librería que simplifica el problema?") es una sesión de mentoría y alineación invaluable. Para un equipo inexperto, este intercambio de conocimiento es oro puro y mejora la habilidad de estimación del equipo con cada sesión.

2.  **Enseña el Pensamiento Relativo:** Los equipos inexpertos fallan al estimar en horas porque no tienen experiencia para saber cuánto tardará algo que nunca han hecho. El Planning Poker los obliga a pensar de forma relativa: *"No sé si esto son 20 o 40 horas, pero sí sé que es más complejo que el Ticket 3 (5 puntos) y similar en complejidad al Ticket 2 (8 puntos)"*. Este músculo de la estimación relativa es mucho más fácil y útil de desarrollar.

3.  **Reduce el Sesgo y la Presión:** La votación anónima evita que los miembros más nuevos del equipo simplemente sigan la estimación del desarrollador más experimentado. Les da una voz y una responsabilidad compartida sobre la estimación.

**Por qué las otras no son ideales para este caso:**

* **Tallas de Camiseta:** Es demasiado abstracta para la planificación de un sprint detallado. Es útil para una primera visión general, pero no fomenta la discusión profunda que un equipo inexperto necesita.
* **Estimación Directa en Horas:** Es la peor opción para un equipo inexperto. Crea una falsa sensación de precisión, genera presión por cumplir con un número que probablemente sea incorrecto y no deja espacio para la incertidumbre y el aprendizaje, que son inherentes al desarrollo de software.

**Conclusión:** Comiencen con **Tallas de Camiseta** para tener una idea general del backlog completo, pero para la planificación de cada sprint, utilicen rigurosamente el **Planning Poker**. Será más lento al principio, pero la inversión en comunicación y aprendizaje colectivo resultará en estimaciones mucho más predecibles y un equipo técnicamente más sólido en el mediano plazo.