# Bitácora de Prompts: Definición de Proyecto ATS

Este documento registra los prompts utilizados durante la sesión de consultoría para la definición de un Sistema de Seguimiento de Candidatos (ATS).

**Asistente utilizado:** Gemini Pro

---

### Prompt 1: Historias de usuario

> Quiero que actues como un experto Product Manager y Business Analyst, y que me apoyes en desarrollar un sistema ATS (Applicant-Tracking System), un sistema para reclutamiento y selección de personal. Te comparto un documento resultado de una sesión previa, la cual incluye decisiones y arquitectura que abarca el sistema. Instrucciones:
> 1. Generar las User Stories. Genera 5.
> 2. Usa una plantilla común para todas ellas.
> 3. Comparte la respuesta con el formato adecuado para documento Markdown (.md)
> 4. Si tienes dudas, dime.
> 5. Te comparto un par de ejemplos de historias de usuario de un servicio de reserva y alquiler de bicicletas
> User Story 1: Turista Explorador. Como un turista que visita la ciudad por primera vez, quiero reservar una bicicleta fácilmente desde mi smartphone para explorar los lugares turísticos recomendados.
> User Story 2: Residente Local. Como un residente que usa la bicicleta diariamente, quiero poder programar reservas recurrentes para asegurar mi transporte a la hora de ir al trabajo.

> * no aplicaste formato markdown (md) 

---

### Prompt 2: Backlog de producto

> Acerca del mismo proyecto, genera el product backlog. Instrucciones:
> 1. Prioriza las historias de usuario con al menos 2 de las metologías más utilizadas
> 2. Por cada una genera una breve explicación de la metodología y los criterios de priorización
> 3. Indica como experto, qué metología genera mayor valor al sistema a desarrollar
> 4. Recuerda generar la respuesta en formato Markdown (.md)

---

### Prompt 3: Tickets de trabajo

> Acerca del mismo proyecto, me parece adecuado la metodología MoSCow para priorizar el Backlog del producto. Tomemos la primera tarea US1: Listado Centralizado de Postulaciones y realiza lo siguiente:
> 1. Genera los tickets de trabajo, de forma técnica
> 2. Te comparto un ejemplo de ticket de trabajo: 
> Título: Implementación de Autenticación de Dos Factores (2FA)
>Descripción: Añadir autenticación de dos factores para mejorar la seguridad del login de usuarios. Debe soportar aplicaciones de autenticación como Authenticator y mensajes SMS.
>Criterios de Aceptación:
> - Los usuarios pueden seleccionar 2FA desde su perfil.
> - Soporte para Google Authenticator y SMS.
> - Los usuarios deben confirmar el dispositivo 2FA durante la configuración.
> Prioridad: Alta
> Estimación: 8 puntos de historia
> Asignado a: Equipo de Backend
> Etiquetas: Seguridad, Backend, Sprint 10
> Comentarios: Verificar la compatibilidad con la base de usuarios internacionales para el envío de SMS.
> Enlaces: Documento de Especificación de Requerimientos de Seguridad
> Historial de Cambios:
> - 01/10/2023: Creado por [nombre]
> - 05/10/2023: Prioridad actualizada a Alta por [nombre]
> 3. Si tienes dudas, dime.
> 4. Recuerda generar la respuesta en formato Markdown (.md)

---

### Prompt 4: Estimación de esfuerzo

> En base a los tickets de trabajo del inciso anterior, realiza:
> 1. Estima el esfuerzo de los tickets de trabajo usando las metodologías (fibonacci, poker, tallas de camiseta)
> 2. Utiliza como unidad de estimación horas
> 3. Indica como experto, qué metología genera mayor y una estimación de esfuerzo más adecuada si el equipo es inexperto y sus estimaciones no son muy acertadas
> 4. Si tienes dudas, dime.
> 5. Recuerda generar la respuesta en formato Markdown (.md)

---
