# Proyecto "Nube Solida"
## Lección 1 – Contexto y definición del problema

### 1.1 Contexto del proyecto

El presente proyecto corresponde al diseño de una **solución arquitectónica para un sistema de reservas**, orientado a su consumo a través de una aplicación web.

En escenarios reales, los sistemas de reservas suelen manejar información sensible, como datos de usuarios, disponibilidad y registros de operaciones. Por esta razón, es fundamental que la arquitectura propuesta considere desde su diseño aspectos como **seguridad, escalabilidad y separación de responsabilidades**.

Este proyecto no se centra únicamente en la implementación visual, sino en la **definición correcta de la arquitectura**, priorizando buenas prácticas utilizadas en entornos profesionales y en infraestructuras modernas.

La solución presentada ha sido diseñada por **Nathalie Carrasco**, aplicando principios básicos de arquitectura cliente-servidor y buenas prácticas de diseño de sistemas.

---

### 1.2 Problema a resolver

Un error común en aplicaciones web básicas es permitir que el cliente (frontend) se comunique directamente con la base de datos. Este enfoque genera múltiples riesgos, tales como:

- Exposición directa de la base de datos
- Falta de control sobre las consultas
- Mayor superficie de ataque
- Dificultad para escalar o mantener el sistema

El problema principal que se busca resolver es **cómo permitir que un usuario realice reservas sin comprometer la seguridad ni la integridad de los datos**, manteniendo una estructura clara y mantenible.

---

### 1.3 Objetivo general

Diseñar una arquitectura de sistema de reservas que permita la interacción segura entre el cliente y los datos, evitando accesos directos a la base de datos y utilizando una capa intermedia que gestione la lógica del sistema.

---

### 1.4 Objetivos específicos

- Separar claramente las responsabilidades entre cliente, lógica de negocio y almacenamiento de datos.
- Reducir los riesgos de seguridad asociados al acceso directo a la base de datos.
- Facilitar la escalabilidad y el mantenimiento del sistema.
- Aplicar un enfoque arquitectónico alineado con buenas prácticas utilizadas en entornos cloud.

---

### 1.5 Alcance de la solución

Esta lección se enfoca en la **definición del contexto y el problema**, estableciendo las bases conceptuales necesarias para comprender la arquitectura propuesta.

En las siguientes lecciones se desarrollará el diseño arquitectónico, el análisis de componentes y la justificación de las decisiones técnicas adoptadas.
