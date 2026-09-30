# 📊 Matriz de Estado y Control del Proyecto — Innovación Tecnológica

> **Propósito:** Este documento registra y sincroniza el estado de completitud, nivel de avance y elementos pendientes de cada archivo y componente del proyecto de grado en LaTeX. Sirve como referencia centralizada para agentes de IA y desarrolladores.
> **Última Actualización General:** 2026-09-30

---

## 📌 Datos Generales del Proyecto

- **Título:** SISTEMA WEB DE INSCRIPCIÓN PARA EL MÓDULO TECNOLÓGICO PRODUCTIVO SAN JULIÁN BTH
- **Modalidad:** Innovación Tecnológica (9 Capítulos, BTH RM 0912/2023)
- **Especialidad:** Sistemas Informáticos (Técnico Medio)
- **Institución:** Módulo Tecnológico Productivo San Julián
- **Distrito / Departamento:** Distrito Educativo San Julián | Santa Cruz - Bolivia
- **Autores:** Estudiante 1 y Estudiante 2
- **Tutor Guía:** Ing. Juan Vladimir Ramirez Flores
- **Gestión Académica:** 2026
- **Estado Global:** **Plantilla Modular Estructurada y Compilable** (100% compila sin errores, estructura base validada, tablas conformes con APA 7, formato general sincronizado con `docs/formato.md` y `docs/protocolo.md`, pendiente de redacción temática y datos empíricos de campo).

---

## 📑 1. Páginas Preliminares

| Sección / Elemento | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **Carátula Oficial BTH** | `preliminares/caratula.tex` | **Completo** | Parametrizada vía `estilos/configuracion.tex` y `estilos/caratula.sty` según `docs/formato.md` (Times New Roman 14/12pt, logo 6x4.5cm, marco azul). | 2026-09-30 |
| **Agradecimientos** | `preliminares/agradecimiento.tex` | **Plantilla estructurada** | Requiere texto definitivo y dedicatorias de las autoras. | 2026-09-20 |
| **Dedicatoria** | `preliminares/dedicatoria.tex` | **Plantilla estructurada** | Requiere texto formal de dedicatoria de las autoras. | 2026-09-20 |
| **Resumen en Castellano** | `preliminares/resumen.tex` | **Plantilla estructurada** | Requiere síntesis factual (problema, solución, resultados) y palabras clave definitivas. | 2026-09-20 |
| **Abstract (Inglés)** | `preliminares/resumen.tex` | **Plantilla estructurada** | Pendiente de traducción técnica una vez concluido el resumen en español. | 2026-09-20 |
| **Resumen Lengua Originaria** | `preliminares/resumen.tex` | **Plantilla estructurada** | Pendiente de traducción a quechua/guaraní/aymara según contexto sociolingüístico. | 2026-09-20 |

---

## 🚀 2. Capítulos de Innovación Tecnológica (1 al 9)

### Capítulo 1: Introducción (`capitulos/01_introduccion/`)
* **Archivo de ensamble:** `capitulos/01_introduccion/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **1.1 Contexto general** | `contexto_general.tex` | **Plantilla estructurada** | Contextualizar sector educativo de San Julián y problemática de inscripciones manuales. | 2026-09-20 |
| **1.2 Motivación y pertinencia** | `motivacion_pertinencia.tex` | **Plantilla estructurada** | Articular con la RM 0912/2023 y digitalización de procesos BTH. | 2026-09-20 |
| **1.3 Contribución esperada** | `contribucion_esperada.tex` | **Plantilla estructurada** | Definir tipo de innovación (incremental) y mejoras de tiempo/precisión proyectadas. | 2026-09-20 |

### Capítulo 2: Planteamiento del Problema (`capitulos/02_planteamiento_problema/`)
* **Archivo de ensamble:** `capitulos/02_planteamiento_problema/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **2.1 Diagnóstico de la realidad** | `diagnostico.tex` | **Plantilla estructurada** | Detallar situación de colas, saturación de secretaría y duplicidad de registros. | 2026-09-20 |
| **2.2 Identificación del problema** | `identificacion_problema.tex` | **Plantilla estructurada** | Árbol de problemas: causas raíz (papel, tiempo) y efectos negativos. | 2026-09-20 |
| **2.3 Formulación del problema** | `formulacion_problema.tex` | **Plantilla estructurada** | Ajustar pregunta formal orientada al sistema web para MTP San Julián. | 2026-09-20 |
| **2.4 Objetivos** | `objetivos.tex` | **Plantilla estructurada** | General y 4 específicos redactados en infinitivo con viñetas `itemize`. | 2026-09-20 |
| **2.5 Justificación** | `justificacion.tex` | **Plantilla estructurada** | Desarrollar justificación técnica, social, institucional y económica. | 2026-09-20 |

### Capítulo 3: Marco Referencial (`capitulos/03_marco_referencial/`)
* **Archivo de ensamble:** `capitulos/03_marco_referencial/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **3.1 Antecedentes** | `antecedentes.tex` | **Plantilla estructurada** | Incluir 3 antecedentes con citas APA 7 (`\textcite`, `\parencite`) locales e internacionales. | 2026-09-20 |
| **3.2 Bases teóricas** | `bases_teoricas.tex` | **Plantilla estructurada** | Fundamentación de arquitecturas cliente-servidor, bases de datos relacionales y seguridad web. | 2026-09-20 |
| **3.3 Marco conceptual y normativo** | `marco_conceptual.tex` | **Plantilla estructurada** | Definiciones operativas clave y respaldo en Ley 070 y RM 0912/2023. | 2026-09-20 |

### Capítulo 4: Desarrollo de la Innovación (`capitulos/04_desarrollo_innovacion/`)
* **Archivo de ensamble:** `capitulos/04_desarrollo_innovacion/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **4.1 Diseño del producto o servicio** | `diseno.tex` | **Plantilla estructurada** | Contiene `especificaciones_tecnicas_ejemplo.tex` y `figura_ejemplo.tex`. Pendiente diagrama real del sistema. | 2026-09-30 |
| **4.2 Planificación y cronograma** | `planificacion.tex` | **Plantilla estructurada** | Contiene `cronograma_ejemplo.tex`. Ajustar fechas reales de desarrollo 2026. | 2026-09-20 |
| **4.3 Recursos** | `recursos.tex` | **Plantilla estructurada** | Detallar recursos humanos, equipamiento hardware, stack de desarrollo y servidores. | 2026-09-20 |
| **4.4 Cálculo de costos** | `calculo_costos.tex` | **Plantilla estructurada** | Contiene `costos_ejemplo.tex`. Subtítulos de Costos de inversión y operación en plural. | 2026-09-30 |

### Capítulo 5: Metodología (`capitulos/05_metodologia/`)
* **Archivo de ensamble:** `capitulos/05_metodologia/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **5.1 Tipo de investigación** | `tipo_investigacion.tex` | **Plantilla estructurada** | Enfoque aplicado (I+D tecnológico) y diseño pre-experimental. | 2026-09-20 |
| **5.2 Población y muestra** | `poblacion_muestra.tex` | **Plantilla estructurada** | Cuantificar población de estudiantes del MTP San Julián y muestra de validación piloto. | 2026-09-20 |
| **5.3 Técnicas e instrumentos** | `tecnicas_instrumentos.tex` | **Plantilla estructurada** | Protocolos de prueba de usabilidad (SUS), cronometraje y fichas de observación. | 2026-09-20 |
| **5.4 Análisis de datos** | `analisis_datos.tex` | **Plantilla estructurada** | Procedimiento estadístico descriptivo para contraste de tiempos y satisfacción. | 2026-09-20 |

### Capítulo 6: Estrategia de Mejora y Proyección (`capitulos/06_estrategia_mejora/`)
* **Archivo de ensamble:** `capitulos/06_estrategia_mejora/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **6.1 Plan de mejora continua** | `plan_mejora.tex` | **Plantilla estructurada** | Contiene `plan_mejora_ejemplo.tex`. Pendiente definir hitos a corto, mediano y largo plazo. | 2026-09-20 |
| **6.2 Proyección y escalamiento** | `proyeccion_escalamiento.tex` | **Plantilla estructurada** | Detallar potencial de réplica en otras unidades educativas del distrito San Julián. | 2026-09-20 |

### Capítulo 7: Resultados (`capitulos/07_resultados/`)
* **Archivo de ensamble:** `capitulos/07_resultados/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **7.1 Resultados obtenidos** | `resultados_obtenidos.tex` | **Plantilla estructurada** | Métricas cuantitativas de las pruebas piloto del sistema web de inscripción. | 2026-09-20 |
| **7.2 Beneficios e impacto** | `beneficios_impacto.tex` | **Plantilla estructurada** | Evaluación de impacto administrativo, optimización de tiempo y satisfacción de usuarios. | 2026-09-20 |
| **7.3 Comparación antes vs. después** | `comparacion_antes_despues.tex` | **Plantilla estructurada** | Contiene `comparacion_antes_despues_ejemplo.tex`. Pendiente datos empíricos de contraste. | 2026-09-20 |

### Capítulo 8: Proyecto de Vida (`capitulos/08_proyecto_vida/`)
* **Archivo de ensamble:** `capitulos/08_proyecto_vida/main.tex` (**Plantilla estructurada**)
  - Subsección 1: Aspiraciones académicas y profesionales en el área de ingeniería/tecnología.
  - Subsección 2: Competencias técnicas y socioemocionales fortalecidas durante el desarrollo.
  - Subsección 3: Compromiso ético y proyección comunitaria en San Julián.
  - *Pendiente:* Redacción vivencial y vocacional de las autoras.

### Capítulo 9: Conclusiones y Recomendaciones (`capitulos/09_conclusiones_recomendaciones/`)
* **Archivo de ensamble:** `capitulos/09_conclusiones_recomendaciones/main.tex` (**Completo**)

| Sección | Archivo Fuente | Estado | Pendientes / Notas | Última Act. |
| :--- | :--- | :--- | :--- | :--- |
| **9.1 Conclusiones** | `conclusiones.tex` | **Plantilla estructurada** | Cierre ordenado por cada objetivo específico formulado en el Capítulo 2 (`itemize`). | 2026-09-20 |
| **9.2 Recomendaciones** | `recomendaciones.tex` | **Plantilla estructurada** | Pautas de mantenimiento preventivo, seguridad informática y futuras ampliaciones. | 2026-09-20 |

---

## 📊 3. Tablas Independientes (`tablas/`)

| Archivo de Tabla | Inclusión en Documento | Cumplimiento APA 7 | Estado / Propósito |
| :--- | :--- | :---: | :--- |
| `especificaciones_tecnicas_ejemplo.tex` | `capitulos/04_desarrollo_innovacion/diseno.tex` | **100%** | Matriz de requerimientos y especificaciones del sistema web. |
| `cronograma_ejemplo.tex` | `capitulos/04_desarrollo_innovacion/planificacion.tex` | **100%** | Cronograma de actividades por fases de desarrollo. |
| `costos_ejemplo.tex` | `capitulos/04_desarrollo_innovacion/calculo_costos.tex` | **100%** | Desglose de inversión y costos de operación. |
| `plan_mejora_ejemplo.tex` | `capitulos/06_estrategia_mejora/plan_mejora.tex` | **100%** | Matriz de mejora continua y fases de evolución técnica. |
| `comparacion_antes_despues_ejemplo.tex` | `capitulos/07_resultados/comparacion_antes_despues.tex` | **100%** | Matriz de contraste de indicadores clave de rendimiento. |
| `tabla_ejemplo.tex` | Referencia / Plantilla base | **100%** | Plantilla de partida para nuevas tablas con `booktabs`. |
| `estudio_mercado_ejemplo.tex` | Referencia / Plantilla | **100%** | Modelo para análisis de alternativas y beneficiarios. |
| `estructura_organizacional_ejemplo.tex` | Referencia / Plantilla | **100%** | Estructura de roles técnicos y responsabilidades. |
| `inversiones_ejemplo.tex` | Referencia / Plantilla | **100%** | Detalle de activos tangibles e intangibles. |
| `costos_produccion_ejemplo.tex` | Referencia / Plantilla | **100%** | Costos unitarios y de operación mensual. |
| `indicadores_financieros_ejemplo.tex` | Referencia / Plantilla | **100%** | Ratios de viabilidad financiera y sostenibilidad. |
| `resultados_piloto_ejemplo.tex` | Referencia / Plantilla | **100%** | Métricas de pruebas piloto vs. metas planificadas. |

*Auditoría de Tablas:* Realizada con `scripts/verificar_tablas.py` (`12/12 correctas, 0 advertencias, 0 errores`).

---

## 🖼️ 4. Recursos Gráficos e Ilustraciones (`imagenes/`)

| Recurso | Tipo / Formato | Estado / Uso |
| :--- | :--- | :--- |
| `marco_portada_bth.png` | Gráfico perimetral azul | Operativo en la portada modular de `preliminares/caratula.tex`. |
| `logo_bth.png` | Logotipo oficial institucional | Operativo en carátula BTH (Módulo San Julián). |
| `diagrama_proceso_ejemplo.png` | Imagen técnica PNG (300 DPI) | Ejemplo de diagrama importado en `imagenes/figura_ejemplo.tex`. |
| `figura_ejemplo.tex` | Plantilla modular APA 7 | Incluida en `capitulos/04_desarrollo_innovacion/diseno.tex`. |

---

## 💻 5. Código Fuente (`codigo/`) y Anexos (`anexos/`)

| Archivo | Ubicación / Referencia | Estado |
| :--- | :--- | :--- |
| `codigo/ejemplo_controlador.py` | Importado en Anexo C | **Operativo:** Script de ejemplo con sintaxis coloreada en Courier. |
| `anexos/index.tex` | Ensamble general raíz | **Operativo:** Carga con `\capitulopreliminar{ANEXOS}`. |
| `anexos/anexo_a_canvas.tex` | Sección Anexo A | **Operativo:** Estructurado con `\seccionanexo{...}`. |
| `anexos/anexo_b_fichas_tecnicas.tex` | Sección Anexo B | **Operativo:** Estructurado con `\seccionanexo{...}`. |
| `anexos/anexo_c_codigo_fuente.tex` | Sección Anexo C | **Operativo:** Importa `codigo/ejemplo_controlador.py`. |

---

## 📚 6. Bibliografía (`bibliografia/`)

- **Archivo:** `bibliografia/referencias.bib`
- **Configuración:** BibLaTeX con estilo `apa` (APA 7ma Edición) y backend `biber`.
- **Estado:** Base de datos con citas estándar operativas.
- **Sección final:** Limpia de numeración de página y cabeceras mediante `\configurarseccionfinal`.

---

## ⚙️ 7. Infraestructura de Compilación y Scripts

| Script / Herramienta | Entorno | Estado | Comandos Soportados |
| :--- | :--- | :---: | :--- |
| `compilar.sh` | Linux / macOS / Bash | **Operativo** | `./compilar.sh` (completo), `--fast`, `--clean`, `--only-clean`, `--check-tablas` |
| `compilar.ps1` | Windows PowerShell | **Operativo** | `.\compilar.ps1`, `-Fast`, `-Clean`, `-OnlyClean`, `-CheckTablas` |
| `compilar.bat` | Windows CMD | **Operativo** | `compilar.bat` (wrapper para `compilar.ps1`) |
| `scripts/verificar_tablas.py` | Python 3 | **Operativo** | Auditoría estricta de booktabs y APA 7 en `tablas/`. |

---

## 🤖 8. Suite de Prompts para Agentes de IA (`promts/`)

- **Migración y recopilación (`promts/migracion/`):** 3 prompts (`crear-contexto.md`, `ficha-proyecto.md`, `copiar-documento.md`).
- **Revisión temática y calidad (`promts/revicion/`):** 17 prompts (`00_README_flujo_revision.md`, `00_analisis-capitulos-tesis.md`, `01` a `14_revision_humanizacion_redaccion.md`).

---

## 📄 9. Documentación y Guías Base (`docs/`)

| Archivo | Propósito / Alcance | Estado / Sincronización |
| :--- | :--- | :--- |
| `docs/formato.md` | Especificación oficial de formato: papel Carta, Times New Roman 12pt, interlineado 1.5, márgenes (3.0 cm izq empaste / 2.5 cm otros), numeración inferior derecha y carátula. | **Sincronizado al 100%** con `configuracion.tex`, `estilos.sty`, `caratula.sty` y `main.tex`. |
| `docs/protocolo.md` | Guía metodológica institucional enriquecida con los 9 capítulos y sus subsecciones temáticas para Innovación Tecnológica. | **Sincronizado al 100%** con la estructura modular de `capitulos/`. |
| `docs/ficha-proyecto.md` | Ficha técnica y requerimientos del sistema web de inscripción. | **Base de datos de requerimientos activa.** |
| `docs/REGLAMENTO_BTH__RM_0912_2023.pdf` | Reglamento ministerial oficial de graduación BTH (Bolivia). | **Marco legal vigente.** |
