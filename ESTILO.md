# ✍️ Guía Editorial y de Estilo Académico (ESTILO.md)

> **Propósito:** Establecer las pautas obligatorias de redacción académica, formato numérico, tipografía, citación APA 7 y convenciones sintácticas en LaTeX para agentes de IA y redactores del proyecto de grado.

---

## 🎯 1. Registro, Tono y Persona Gramatical

1. **Voz Impersonal (Tercera Persona):** Toda la redacción del documento técnico debe realizarse en tercera persona impersonal.
   - *Correcto:* «Se diseñó una arquitectura cliente-servidor...», «La investigación demuestra que...», «Se implementó un módulo de autenticación...».
   - *Incorrecto:* «Diseñamos un sistema...», «En mi opinión...», «Nuestro trabajo busca...».
   - *Excepción:* En el **Capítulo 8 (Proyecto de Vida)** se admite una voz reflexiva personal o testimonial cuando las autoras exponen sus aspiraciones vocacionales y vivencias personales.
2. **Registro Formal y Científico:** Emplear terminología técnica precisa, objetiva y fundamentada. Evitar coloquialismos, adjetivos exagerados («el sistema es sumamente increíble») y afirmaciones sin respaldo empírico o bibliográfico.
3. **Claridad y Concisión:** Oraciones estructuradas con sujeto, verbo y predicado claros. Evitar párrafos excesivamente extensos (se recomienda entre 4 y 8 líneas por párrafo).

---

## ⏳ 2. Matriz de Tiempos Verbales por Capítulo

| Capítulo | Tiempos Verbales Principales | Justificación y Aplicación |
| :--- | :--- | :--- |
| **Cap. 1: Introducción** | Presente y Futuro propositivo | **Presente** para describir la realidad del sector educativo y la problemática; **futuro o presente** para la contribución técnica esperada («El sistema optimizará el proceso de inscripción...»). |
| **Cap. 2: Planteamiento del Problema** | Presente e Infinitivo | **Presente** para el diagnóstico contextual y la formulación del problema; **infinitivo** para los objetivos generales y específicos («Diseñar...», «Implementar...», «Evaluar...»). |
| **Cap. 3: Marco Referencial** | Pretérito y Presente | **Pretérito** para antecedentes históricos e investigaciones previas consultadas («Pérez (2023) desarrolló un sistema...»); **presente** para leyes, normativas vigentes y teorías científicas consolidadas. |
| **Cap. 4: Desarrollo de la Innovación** | Pretérito e Impersonal descriptivo | **Pretérito** para relatar las etapas de desarrollo y construcción ejecutadas; **presente** para describir la arquitectura, especificaciones de componentes y cálculo de costos actuales. |
| **Cap. 5: Metodología** | Pretérito descriptivo | **Pretérito** para explicar el diseño metodológico aplicado, la selección de la muestra y los procedimientos de recolección empleados durante la investigación. |
| **Cap. 6: Estrategia de Mejora** | Futuro propositivo y Presente | **Futuro y condicional** para proyectar planes de mantenimiento, escalamiento distrital y mejoras evolutivas («Se implementará un módulo de notificaciones vía SMS...»). |
| **Cap. 7: Resultados** | Pretérito y Presente analítico | **Pretérito** para reportar las mediciones de las pruebas piloto («El tiempo promedio se redujo de 25 a 3 minutos...»); **presente** para interpretar gráficos y matrices comparativas («La Tabla 7.1 evidencia un incremento en la satisfacción...»). |
| **Cap. 8: Proyecto de Vida** | Presente reflexivo y Futuro | **Presente** para reflexionar sobre las competencias adquiridas; **futuro** para proyectar aspiraciones universitarias y profesionales. |
| **Cap. 9: Conclusiones y Recomendaciones** | Pretérito sintético e Infinitivo propositivo | **Pretérito/presente** para concluir sobre los objetivos cumplidos; **infinitivo o condicional** para recomendar acciones futuras al módulo y a próximos investigadores. |

---

## 🔢 3. Formato Numérico, Decimales y Separador de Miles (Norma SI/ISO 80000-1)

En todo el proyecto (capítulos, tablas, notas y anexos) se sigue de manera estricta la normativa internacional del Sistema Internacional de Unidades y la recomendación técnica de la RAE:

1. **Parte Decimal con Punto (`.`):**
   - Utilizar obligatoriamente **punto** como separador decimal.
   - *Ejemplos correctos:* `12.50`, `3.1416`, `98.5%`, `0.75 Bs.`, `4.8 segundos`.
   - *Prohibido:* Usar coma (`,`) para cifras decimales (ej. evitar `12,50`).
2. **Separador de Miles:**
   - **PROHIBIDO** el uso de comas (`,`) o puntos (`.`) como separadores de millares (ej. evitar `1,000` y `1.000`).
   - **Cifras de 4 dígitos:** Deben escribirse juntas sin separación (ej. `1000`, `3500`, `4500.00`, `7700.00`).
   - **Cifras de 5 o más dígitos:** Deben escribirse de forma continua o con un espacio delgado no separable entre grupos de tres dígitos (ej. `25000.00` o `25~000.00`, `46~500.00`), nunca con comas ni puntos.
3. **Moneda y Unidades:**
   - Escribir la unidad monetaria boliviana como `Bs.` o `BOB` precedida o sucedida del valor con espacio no separable: `150.00~Bs.` o `Bs.~150.00`.
   - Las unidades de medida técnicas deben llevar espacio no separable: `15~ms`, `50~MB`, `100~Mbps`.

---

## 📝 4. Listas y Elementos de Enumeración (Prioridad de Viñetas)

1. **Prioridad Obligatoria de Viñetas (`itemize`):**
   - Emplear siempre el entorno `\begin{itemize}` para:
     * Objetivos específicos (Cap. 2).
     * Requerimientos funcionales y no funcionales (Cap. 4).
     * Características técnicas, componentes y recursos.
     * Conclusiones y recomendaciones (Cap. 9).
     * Ventajas, beneficios y elementos descriptivos generales.
2. **Uso Exclusivo de Listas Numeradas (`enumerate`):**
   - Reservar `\begin{enumerate}` **únicamente** para:
     * Pasos de algoritmos secuenciales estrictos.
     * Procedimientos cronológicos donde el orden numérico sea imprescindible e inherente a la explicación técnica.

---

## 📊 5. Normas para Tablas (APA 7ma Edición)

1. **Estructura con `booktabs`:**
   - Usar exclusivamente `\toprule`, `\midrule` y `\bottomrule`.
   - **PROHIBIDO** el uso de líneas divisorias verticales (`|`) y el comando `\hline`.
2. **Ubicación del Título y Rótulo:**
   - El comando `\caption{...}` debe ubicarse obligatoriamente **arriba** de la tabla, seguido de `\label{tab:...}` y `\centering`.
3. **Notas al Pie de Tabla:**
   - Para indicar fuentes o notas explicativas debajo de la tabla, usar obligatoriamente la macro semántica `\notatabla{Fuente: ...}` (aplica tamaño pequeño, cursiva e interlineado ajustado).
4. **Tablas con Textos Extensos:**
   - Utilizar el entorno `tabularx` con ancho `\textwidth` y columnas auto-ajustables `L`, `C`, `R` o `X` (definidas en `estilos.sty`) para evitar desbordamientos del margen derecho.
5. **Auditoría Automatizada:**
   - Toda tabla debe superar sin errores el script `python3 scripts/verificar_tablas.py` (o `./compilar.sh --check-tablas`).

---

## 🖼️ 6. Normas para Figuras e Ilustraciones (APA 7ma Edición)

1. **Ubicación de Rótulo y Gráfico:**
   - Título y rótulo obligatoriamente **arriba** con `\caption{...}\label{fig:...}`.
   - Contenido gráfico centrado con `\centering`.
2. **Notas al Pie de Figura:**
   - Utilizar la macro semántica `\notafigura{Fuente: ...}` inmediatamente después del gráfico (espaciado configurable `\espacionotafigura`).
3. **Dimensiones:**
   - Ancho estándar controlado centralmente por `\anchuraimagenpredeterminada` (definido en `estilos/configuracion.tex`, por defecto `0.8\textwidth`).
4. **Macros Semánticas de Inclusión:**
   - Usar el entorno flotante estándar `\begin{figure}[htbp]` o la macro de inserción ágil:
     `\incluirfigura[ancho]{archivo}{Título}{etiqueta}{Nota al pie}`.

---

## 💻 7. Código Fuente y Algoritmos

1. **Entorno `listings`:**
   - Todo bloque de código debe utilizar el entorno `listings` con el estilo `estilocodigo` predeterminado (fuente Courier, números de línea en gris claro, sintaxis coloreada, soporte UTF-8 en español).
2. **Archivos Externos en `codigo/`:**
   - Guardar scripts completos en `codigo/` e importarlos modularmente con:
     `\lstinputlisting[language=Python, caption={...}, label={lst:...}]{codigo/archivo.ext}`.
3. **Ajuste Automático de Línea:**
   - Las líneas largas deben ajustarse automáticamente (`breaklines=true`) respetando el margen de texto.
4. **Código en Línea:**
   - Para mencionar variables, clases o métodos en el cuerpo del texto, usar `\lstinline|codigo|` o `\texttt{codigo}`.

---

## 📖 8. Citas y Bibliografía (APA 7ma Edición)

1. **Motor Bibliográfico:**
   - Motor `biblatex` con estilo `apa` (APA 7ma Edición) y backend `biber` sobre `bibliografia/referencias.bib`.
2. **Cita Parentética:**
   - `\parencite{clave}` $\rightarrow$ *(Apellido, Año)*.
   - Para múltiples fuentes: `\parencite{clave1, clave2}` $\rightarrow$ *(Apellido1, Año1; Apellido2, Año2)*.
3. **Cita Narrativa:**
   - `\textcite{clave}` $\rightarrow$ *Apellido (Año)*.
4. **Secciones Finales:**
   - La lista de referencias se imprime con `\printbibliography[heading=bibintoc, title={Bibliografía}]`.
   - Tanto la Bibliografía como los Anexos deben estar limpios de cabeceras y numeración de página mediante la macro global `\configurarseccionfinal`.

---

## 📐 9. Tipografía, Márgenes y Formato de Documento (docs/formato.md)

1. **Tamaño de Hoja y Tipografía:**
   - Papel: Carta (`letterpaper`, 21.59 cm $\times$ 27.94 cm).
   - Tipografía principal: **Times New Roman 12 pt** (`mathptmx`, gobernada centralmente por `\tipografiadocumento{times}`) con interlineado de 1.5 líneas (`\onehalfspacing`).
   - Tipografía para código y texto monoespaciado: Courier (`courier`).
2. **Márgenes Oficiales:**
   - **Margen Izquierdo:** 3.0 cm (`\margenizquierdo`, para empastado/anillado).
   - **Margen Derecho, Superior e Inferior:** 2.5 cm (`\margenderecho`, `\margensuperior`, `\margeninferior`).
3. **Numeración de Página:**
   - **Posición:** Obligatoriamente en la **parte inferior derecha** (`\rfoot{\thepage}`).
   - **Páginas Preliminares:** Números romanos minúsculos (`i, ii, iii...`) desde Agradecimientos hasta Resumen.
   - **Cuerpo Principal (Capítulos 1 al 9):** Números arábigos (`1, 2, 3...`) iniciando en la página 1 de la Introducción.
   - **Secciones Finales (Bibliografía y Anexos):** Totalmente limpias de número de página mediante `\configurarseccionfinal`.
4. **Espaciado de Párrafos (Estilo Bloque):**
   - Espaciado posterior configurable (`\espacioposteriorparrafo`, 8 pt) y sangría de primera línea en 0 pt (`\sangriaprimeralinea`).
