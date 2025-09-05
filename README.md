# Desarrollo y Funcionamiento de una Aplicación de Citas Médicas con Microsoft Power Platform

## Introducción

Este proyecto, desarrollado como Trabajo de Fin de Grado (TFG), explora y demuestra la creación de una aplicación de programación de citas médicas utilizando el ecosistema de **Microsoft Power Platform**.

[cite_start]El objetivo es mostrar cómo las herramientas de bajo código ("low-code") como **Power Apps**, **Dataverse** y **Power Automate** pueden integrarse para construir soluciones empresariales funcionales de manera rápida y eficiente[cite: 9, 27, 28].

## ¿Por qué Power Platform? Un Enfoque Didáctico

La elección de Microsoft Power Platform para este proyecto no fue casual. Como desarrollador en formación, es crucial familiarizarse con las tecnologías que están redefiniendo la industria. [cite_start]Gartner, una de las principales consultoras del sector tecnológico, ha reconocido a Microsoft como líder en el mercado de plataformas de aplicaciones de bajo código (LCAP)[cite: 30].

[cite_start]Este proyecto representa una inmersión práctica en un entorno de desarrollo real, permitiendo aplicar conocimientos teóricos en un contexto empresarial y aprender sobre una tecnología que se posiciona como una de las más relevantes para el futuro de la creación de aplicaciones[cite: 8, 30].

## Componentes de la Solución

La aplicación de citas médicas se construye sobre tres pilares principales de la Power Platform:

* [cite_start]**Power Apps:** Utilizado para el desarrollo de la interfaz de usuario (UI), permitiendo un control total sobre el diseño y el comportamiento de las pantallas, similar a una herramienta de arrastrar y soltar[cite: 27, 120]. [cite_start]Para este proyecto, se usó un formato de aplicación de lienzo (`Canvas App`)[cite: 122].

* [cite_start]**Microsoft Dataverse:** Sirve como la base de datos relacional y el motor de almacenamiento centralizado para la aplicación[cite: 37, 38]. [cite_start]Aquí se gestiona la información de usuarios, especialistas, horarios y citas a través de tablas con relaciones predefinidas[cite: 39, 42].

* [cite_start]**Power Automate:** Automatiza los flujos de trabajo clave, como el envío de correos electrónicos de recordatorio a los pacientes antes de sus citas[cite: 28, 64]. [cite_start]Esto mejora la experiencia del usuario y ayuda a reducir las ausencias y cancelaciones[cite: 16, 18].

## Funcionalidades de la Aplicación

La aplicación desarrollada incluye las siguientes funcionalidades:

* [cite_start]**Gestión de Citas:** Permite a los usuarios y especialistas gestionar la reserva, consulta y eliminación de citas[cite: 19].
* [cite_start]**Gestión de Datos:** Implementa las operaciones CRUD (`Create, Read, Update, Delete`) para manipular los registros de las tablas en Dataverse[cite: 64].
* [cite_start]**Integración de Horarios:** Muestra en tiempo real los horarios disponibles de los especialistas, facilitando la reserva de citas[cite: 22].
* [cite_start]**Recordatorios Automáticos:** Envía notificaciones por correo electrónico para recordar las citas a los usuarios[cite: 21, 64].
* [cite_start]**Interfaz Responsiva:** Diseñada para funcionar tanto en navegadores como en dispositivos móviles[cite: 112].

## Estructura del Proyecto

El proyecto se basa en un diseño de base de datos relacional con las siguientes tablas:

* **`Usuario_3`:** Almacena la información de los usuarios.
* **`Especialistas`:** Contiene los datos de los especialistas.
* **`Especialidades`:** Gestiona los tipos de servicios ofrecidos.
* **`Agenda_2`:** Contiene el calendario con las fechas y horas disponibles.
* [cite_start]**`Cita`:** Registra la información detallada de cada cita reservada[cite: 77, 86].

## Lecciones Aprendidas

Esta práctica demostró que el desarrollo de bajo código no solo acelera el proceso de construcción de aplicaciones, sino que también ofrece un gran potencial para la automatización y la integración con otras herramientas. Además, la experiencia de trabajar con la Power Platform destaca la importancia de comprender la arquitectura de datos y la lógica de negocio, habilidades que son fundamentales para cualquier desarrollador, independientemente de la tecnología utilizada.

## Autor

**Sergio Felipe García**
* **Curso:** 2º Desarrollo de Aplicaciones Web - DAW
* **Tutor del Proyecto:** Carmelo Escribano

---
Si necesitas cualquier otra modificación o información adicional, no dudes en consultarme.
