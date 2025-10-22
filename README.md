# Proyecto 2: Pruebas de API y Lógica de Negocio (Urban.Grocers)

Este proyecto demuestra la capacidad de analizar requisitos de backend, diseñar casos de prueba de API y validar la lógica de negocio del servidor usando Postman.

---

### 1. Objetivo del Proyecto

El objetivo fue probar la nueva funcionalidad de la API para la aplicación "Urban.Grocers". Específicamente, se probaron los endpoints responsables de:
1.  Agregar productos a un "kit".
2.  Calcular el costo del servicio de entrega "Order and Go".

El desafío era validar que la lógica de negocio (ej. cálculos de costos, límites de productos) funcionara correctamente antes de que la función llegara a los usuarios.

---

### 2. Mi Rol y Responsabilidades

* **Análisis de Requisitos:** Analicé los requisitos del backend y la documentación de la API (**Apidoc**) para entender la lógica de negocio y los parámetros de entrada/salida.
* [cite_start]**Diseño de Pruebas de API:** Diseñé una lista de comprobación y casos de prueba (positivos y negativos) en Google Sheets para los nuevos endpoints[cite: 1, 2].
* **Ejecución de Pruebas (Postman):** Ejecuté las pruebas directamente en **Postman**, enviando peticiones `POST` con diferentes `bodies` (JSON) para simular escenarios reales.
* **Análisis de Resultados:** Verifiqué que las respuestas del servidor fueran correctas, validando tanto los códigos de estado (ej. `200 OK`, `400 Bad Request`) como la lógica de negocio en el JSON de respuesta.
* [cite_start]**Reporte de Errores:** Documenté los hallazgos críticos y redacté un informe de resultados para el equipo de desarrollo .

---

### 3. Evidencias y Resultados

#### A. Diseño de Casos de Prueba de API
[cite_start]Creé casos de prueba para validar escenarios como límites de productos, cálculos de costos y manejo de errores[cite: 1, 2].

<img width="1678" height="960" alt="Captura de pantalla 2025-10-21 a la(s) 6 43 57 p m" src="https://github.com/user-attachments/assets/3bb37961-0714-4ce4-84b0-40de1792d64f" />


#### B. Ejecución en Postman
Validé los endpoints enviando peticiones `POST`. La siguiente imagen muestra una prueba de un escenario negativo (`400 Bad Request`) al intentar agregar más de 30 productos a un kit.

<img width="1680" height="1050" alt="Captura de pantalla 2025-10-21 a la(s) 7 07 40 p m" src="https://github.com/user-attachments/assets/a992e88e-100b-47ef-8028-32b23047a63e" />



#### C. Informe de Resultados y Análisis de Impacto
[cite_start]Durante las pruebas, descubrí fallos críticos en la lógica de cálculo de costos[cite: 4, 5]. [cite_start]Como resultado, redacté un informe formal para el equipo, explicando el impacto en el negocio (pérdidas económicas) y recomendando una revisión inmediata antes del lanzamiento[cite: 6, 7].
<img width="1680" height="961" alt="Captura de pantalla 2025-10-21 a la(s) 7 21 25 p m" src="https://github.com/user-attachments/assets/73a462d2-f5dd-4f2a-80bd-193d72963e53" />

[cite_start]*<img width="1680" height="961" alt="Captura de pantalla 2025-10-21 a la(s) 7 21 25 p m" src="https://github.com/user-attachments/assets/73a462d2-f5dd-4f2a-80bd-193d72963e53" />
*

---

### 4. Tecnologías y Herramientas Utilizadas

* **Pruebas de API:** Postman
* **Gestión de Proyectos y Bugs:** Jira (mencionado en el sprint)
* **Documentación de API:** Apidoc
* **Diseño de Pruebas:** Google Sheets
* **Habilidades:** Pruebas de API, Pruebas de Backend, Análisis de Requisitos, Pruebas de Lógica de Negocio, Reporte de Errores, REST/JSON.
