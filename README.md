# 📊 Academic Dashboard – Google Sheets

Mini-proyecto de modelado y visualización de datos desarrollado en Google Sheets.

Este proyecto consiste en el diseño de una plantilla interactiva para el seguimiento académico, estructurada bajo principios básicos de modelado de datos y visualización orientada a usuario.

---

## 🎯 Objetivo del proyecto

Diseñar una herramienta funcional que permita:

- Introducir datos académicos en una tabla base estructurada
- Generar métricas automáticas (media global, créditos superados)
- Visualizar la evolución del rendimiento por curso
- Separar claramente la capa de datos y la capa de visualización
- Garantizar actualización automática del dashboard ante cualquier modificación

El enfoque principal ha sido aplicar buenas prácticas básicas de estructuración de datos dentro de un entorno como Google Sheets.

---

## 🗂 Arquitectura del archivo

El documento está dividido en dos bloques principales:

### 🔹 Hoja "DATOS"

Actúa como base de datos editable.

El usuario puede introducir o modificar:

- Asignaturas
- Curso y cuatrimestre
- Créditos
- Nota obtenida

A partir de esta información:

- Se mantiene consistencia en el formato numérico
- Se generan variables derivadas (estado de asignatura)
- Se alimentan dinámicamente las tablas dinámicas del dashboard

Esta hoja representa la capa de datos del modelo.

---

### 🔹 Hoja "DASHBOARD"

Capa de visualización conectada directamente a la hoja "DATOS".

Incluye:

- Media global automática
- Créditos superados sobre el total
- Evolución del rendimiento por curso
- Resúmenes estructurados mediante tablas dinámicas

Cualquier modificación en la hoja "DATOS" actualiza automáticamente todas las métricas y gráficos.

---

## 👤 Experiencia de usuario

El flujo de uso es simple:

1. Introducir o modificar datos en la hoja "DATOS".
2. Acceder a la hoja "DASHBOARD".
3. Visualizar métricas y evolución actualizadas en tiempo real.

El diseño busca que el usuario no necesite conocimientos técnicos para utilizar la plantilla.

---

## 🛠 Herramientas utilizadas

- Google Sheets
- Tablas dinámicas
- Fórmulas básicas (agregación y lógica)
- Variables derivadas
- Formato condicional
- Diseño estructurado de dashboard

---

## 📸 Capturas

### Dashboard
<img width="717" height="791" alt="Dashboard" src="https://github.com/user-attachments/assets/bbb3c958-3536-4c6a-bb0e-305861a24202" />

### Tabla base
<img width="723" height="806" alt="Tabla base" src="https://github.com/user-attachments/assets/4847ed70-9b9b-4651-bf40-d33494644b39" />

---

## 📄 Demo

Puedes probar la plantilla aquí (se generará automáticamente una copia editable sin modificar el archivo original):

https://docs.google.com/spreadsheets/d/1fEsx_msYwf-V5N-TxhkjKcGiWzOI5iLR9a6ExvoPpag/copy

La plantilla es totalmente funcional y puede adaptarse a cualquier usuario que quiera utilizarla como herramienta de seguimiento académico.

---

## 🧠 Conceptos trabajados

- Modelado básico de datos
- Separación entre datos y visualización
- Creación de variables derivadas
- Métricas agregadas (media ponderada implícita por créditos)
- Automatización mediante tablas dinámicas
- Diseño de dashboard orientado a claridad y usabilidad

---

## 💡 Aprendizajes clave

Este proyecto me permitió trabajar:

- La importancia de estructurar correctamente los datos antes de analizarlos
- La consistencia en formatos numéricos para evitar errores de cálculo
- La actualización automática como principio básico de automatización
- La experiencia de usuario como parte fundamental del análisis

---

## 🚀 Próximos pasos

Replicar este mismo enfoque de modelado y visualización utilizando herramientas más avanzadas como:

- SQL (estructuración y consultas de datos)
- Python (análisis y automatización)
- Power BI (visualización profesional)

---

