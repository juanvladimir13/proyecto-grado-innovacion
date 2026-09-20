# 🔬 Marco Metodológico de Investigación y Desarrollo (METODOLOGIA.md)

> **Propósito:** Definir el marco metodológico transversal, la operacionalización de variables y el protocolo de validación empírica para el proyecto de grado «SISTEMA WEB DE INSCRIPCIÓN PARA EL MÓDULO TECNOLÓGICO PRODUCTIVO SAN JULIÁN BTH», bajo la modalidad de Innovación Tecnológica (BTH RM 0912/2023).

---

## 🧭 1. Paradigma, Tipo y Diseño de Investigación

1. **Paradigma y Enfoque:**
   - **Enfoque Mixto (Cualitativo y Cuantitativo):**
     * *Cuantitativo:* Medición exacta de tiempos de procesamiento (minutos/segundos por inscripción), porcentaje de reducción de errores y concurrencia de peticiones en el servidor.
     * *Cualitativo:* Evaluación de la percepción de facilidad de uso, satisfacción y claridad visual por parte de los postulantes y el personal de secretaría.
2. **Tipo de Investigación:**
   - **Investigación Aplicada y Desarrollo Tecnológico (I+D):** Orientada a resolver una necesidad operativa concreta en el Módulo Tecnológico Productivo San Julián mediante el desarrollo e implementación de un artefacto de software.
   - **Nivel Descriptivo y Propositivo:** Describe la situación inicial deficitaria (filas, duplicidad, extravío de formularios) y propone formalmente la arquitectura y funcionalidad del sistema web.
3. **Diseño Metodológico:**
   - **Diseño Pre-experimental con Pre-test y Post-test:**
     $$\text{Diagnóstico Previo } (O_1) \longrightarrow \text{Implementación de la Innovación } (X) \longrightarrow \text{Validación Posterior } (O_2)$$
     Se contrastan los indicadores del proceso tradicional manual ($O_1$) con los resultados obtenidos tras la puesta en marcha de la prueba piloto del sistema web ($O_2$).

---

## 🎯 2. Operacionalización de Variables

La investigación tecnológica se estructura sobre dos ejes de variables interrelacionadas:

### 2.1 Variable Independiente (VI)
* **Definición:** **Sistema Web de Inscripción para el MTP San Julián.**
* **Dimensiones Técnicas:**
  - *Arquitectura del Software:* Separación frontend-backend, API REST, modularidad.
  - *Gestión de Base de Datos:* Integridad referencial, modelo relacional, normalización.
  - *Seguridad y Control de Acceso:* Autenticación basada en roles, validación de formularios reactivos y hash de contraseñas.
  - *Diseño Adaptable (Responsive):* Accesibilidad desde ordenadores de escritorio y dispositivos móviles.

### 2.2 Variables Dependientes (VD)
* **VD 1: Eficiencia Temporal del Proceso de Inscripción:**
  - *Indicador:* Tiempo promedio (en minutos) requerido para completar una ficha de inscripción por estudiante.
  - *Unidad de Medida:* Minutos / segundos cronometrados.
* **VD 2: Tasa de Errores de Registro y Transcripción:**
  - *Indicador:* Porcentaje de formularios con datos duplicados, omitidos o ilegibles.
  - *Unidad de Medida:* Porcentaje ($\%$) de incidencias sobre el total de matrículas procesadas.
* **VD 3: Nivel de Satisfacción y Usabilidad de los Usuarios:**
  - *Indicador:* Puntuación estandarizada en la escala SUS (System Usability Scale).
  - *Unidad de Medida:* Escala de 0 a 100 puntos (considerando aceptable $> 68$ puntos).

---

## 👥 3. Población y Muestra de Validación

1. **Población Objetivo (Universo de Estudio):**
   - La totalidad de estudiantes postulantes de las unidades educativas adscritas que cursan formación técnica en el Módulo Tecnológico Productivo San Julián (Distrito Educativo San Julián).
   - Personal administrativo y directivo del MTP (secretaría, dirección, coordinadores de área).
2. **Muestra de Prueba Piloto:**
   - **Tipo de Muestreo:** No probabilístico por conveniencia / intencional.
   - **Sujetos de Validación Humana:**
     * Grupo piloto de estudiantes postulantes (representativo de las especialidades técnicas).
     * Personal de secretaría y administración encargado de validar y emitir reportes de matrícula.
3. **Unidades Experimentales de Prueba Técnica:**
   - Simulaciones de carga de peticiones concurrentes (pruebas de estrés de 10, 25 y 50 usuarios simultáneos).
   - Pruebas de validación cruzada de datos contra registros históricos en papel.

---

## 🛠️ 4. Técnicas e Instrumentos de Recolección de Datos

| Técnica | Instrumento | Propósito / Variable Evaluada |
| :--- | :--- | :--- |
| **Observación Directa** | Ficha de observación estructurada | Registro de incidencias, cuellos de botella y conducta del usuario frente al formulario. |
| **Cronometraje Experimental** | Protocolo de medición de tiempos | Cronometrar el tiempo de inscripción antes ($O_1$) vs. después ($O_2$) con el sistema web (VD 1). |
| **Encuesta Psicométrica** | Cuestionario estandarizado SUS (10 ítems) | Medir el nivel de usabilidad percibida y satisfacción de estudiantes y administrativos (VD 3). |
| **Auditoría de Datos** | Script de validación e integridad en base de datos | Detección de duplicidad de registros, campos nulos y discrepancias (VD 2). |
| **Pruebas de Carga de Software** | Herramienta de pruebas de rendimiento (Apache Benchmark / Locust / Postman) | Medición de concurrencia, tiempo de respuesta del servidor (latencia) y tasa de disponibilidad. |

---

## 📈 5. Procedimiento de Análisis e Interpretación de Datos

1. **Procesamiento Cuantitativo:**
   - Cálculo de medias aritméticas ($\bar{x}$) y desviaciones típicas ($s$) para tiempos de inscripción.
   - Cálculo del porcentaje de reducción de tiempo:
     $$\Delta\% = \frac{\bar{T}_{\text{manual}} - \bar{T}_{\text{web}}}{\bar{T}_{\text{manual}}} \times 100$$
   - Tabulación de puntuaciones individuales del test SUS y conversión al percentil de usabilidad global.
2. **Presentación Gráfica y Tabular:**
   - Matriz comparativa «Antes vs. Después» en el Capítulo 7 (`tablas/comparacion_antes_despues_ejemplo.tex`).
   - Gráficos estadísticos claros formateados bajo APA 7ma Edición.
3. **Matriz de Sincronía Transversal de 5 Ejes:**
   - Comprobación de que las variables e instrumentos definidos en este documento guarden correspondencia biunívoca en los capítulos:
     * **Cap. 2:** Problema y objetivos específicos.
     * **Cap. 4:** Arquitectura y módulos del sistema (VI).
     * **Cap. 5:** Técnicas, muestra e instrumentos.
     * **Cap. 7:** Datos empíricos y métricas de mejora obtenidas (VD).
     * **Cap. 9:** Conclusiones que dan respuesta a cada objetivo planteado.
