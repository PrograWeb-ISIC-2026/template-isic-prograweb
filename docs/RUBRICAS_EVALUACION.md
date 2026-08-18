# Rúbricas de Evaluación Asignatura: Programación Web (AEB-1055)

**Carrera:** Ingeniería en Sistemas Computacionales  
**Asignatura:** Programación Web (AEB-1055)  
**Enfoque Evaluativo:** Evaluación orientada a Procesos Cognitivos, Curaduría Crítica de Información, Uso Ético/Analítico de IA Generativa y Toma de Decisiones Técnicas.

---

## 1. Lineamientos Generales sobre el Uso de Inteligencia Artificial Generativa

En el desarrollo de software actual, el uso de herramientas de Inteligencia Artificial Generativa (IAG) es una competencia profesional real y valorada. Sin embargo, en este curso el código o texto generado por IA **no constituye por sí mismo la evidencia de aprendizaje**. Lo que se evalúa es el nivel de razonamiento crítico, la curaduría de la información recibida, la verificación técnica, el diagnóstico de errores y la toma de decisiones fundamentadas por parte del estudiante.

Todo entregable que incorpore IA Generativa debe acompañarse de una sección obligatoria denominada **"Registro de Curaduría y Prompting (Bitácora IA)"**, donde se especifiquen:
* Los prompts clave o consultas utilizadas y el propósito de cada una.
* Las alucinaciones, errores técnicos o sesgos detectados en las respuestas generadas.
* Las modificaciones, refactorizaciones y decisiones tomadas para adaptar el resultado al proyecto real.
* La justificación técnica de por qué la solución elegida es óptima para el contexto del problema.

---

## 2. Rúbrica 1: Proyecto Semestral Integrador (20% de la Evaluación)

Evalúa el desarrollo progresivo de una aplicación web completa, priorizando la arquitectura, la integración del código generado/curado, la resolución de problemas y la justificación de decisiones de diseño e implementación.

| Criterio / Dimensión | Excelente (100% - 90%) | Notable / Bueno (89% - 80%) | Suficiente (79% - 70%) | Insuficiente (< 70%) |
| :--- | :--- | :--- | :--- | :--- |
| **Curaduría de Código e Integración con IA** | Integra código asistido por IA habiendo auditado, refactorizado y optimizado cada módulo. Explica a detalle cómo adaptó la salida a la arquitectura del proyecto y eliminó dependencias innecesarias o código alucinado. | Integra el código de la IA con adaptaciones funcionales. Comprende la mayor parte de la estructura pero presenta ajustes menores pendientes de optimización o estilo. | Copia e integra el código generado por IA con modificaciones mínimas. La aplicación funciona parcialmente, pero le cuesta explicar la lógica de integración o justificar cambios. | Copia directa e indiscriminada de código generado por IA sin adaptación ni comprensión. La aplicación presenta errores críticos, alucinaciones de sintaxis o incompatibilidades. |
| **Toma de Decisiones y Arquitectura Web** | Demuestra excelente criterio técnico en la selección de tecnologías (Frontend, Backend, BD, Nube). Sustenta las decisiones considerando escalabilidad, seguridad (OWASP) y rendimiento. | Selecciona adecuadamente la arquitectura y tecnologías. Justifica sus elecciones basándose en requisitos funcionales básicos, con algunas lagunas en aspectos de seguridad o escalabilidad. | Aplica una arquitectura básica pero con baja justificación técnica. La elección de tecnologías parece fortuita o dependiente exclusivamente de la plantilla/prompt de IA. | Ausencia de un diseño de arquitectura coherente. Mezcla paradigmas o tecnologías sin criterio técnico ni correspondencia con las necesidades del proyecto. |
| **Proceso Cognitivo y Diagnóstico de Errores** | Muestra alta capacidad de depuración (debugging). Identifica alucinaciones de la IA o errores de ejecución, proponiendo y documentando soluciones metodológicas y eficientes. | Logra diagnosticar y corregir errores comunes durante el desarrollo mediante pruebas guiadas y consulta de documentación oficial o IA. | Requiere asistencia constante del docente para corregir fallos menores o alucinaciones de la IA. Le cuesta aislar la causa raíz del problema. | Incapaz de explicar el funcionamiento del código o diagnosticar errores. No diferencia entre el comportamiento esperado y los fallos de la aplicación. |
| **Funcionalidad e Interoperabilidad** | La aplicación cumple al 100% las competencias de la asignatura: interfaces responsivas, interactividad cliente, backend dinámico, acceso a BD y despliegue en la nube. | La aplicación es funcional en sus componentes clave (Frontend, Backend, BD), con pequeños detalles de interfaz o despliegue en la nube por pulir. | La aplicación integra solo algunas capas (ej. HTML/CSS y algo de cliente/servidor), pero el acceso a datos o servicio en la nube es limitado o erróneo. | Proyecto no funcional o fragmentado. No logra comunicar las diferentes capas del software ni cumple con los mínimos requeridos. |

---

## 3. Rúbrica 2: Ejercicios de Portafolio por Unidad (30% de la Evaluación)

Evalúa el trabajo continuo de investigación, solución de ejercicios prácticos guiados y la capacidad de análisis sintáctico y conceptual.

| Criterio / Dimensión | Excelente (100% - 90%) | Notable / Bueno (89% - 80%) | Suficiente (79% - 70%) | Insuficiente (< 70%) |
| :--- | :--- | :--- | :--- | :--- |
| **Investigación y Curaduría de Información** | Consulta múltiples fuentes oficiales (MDN, W3C, OWASP) e IA. Contrasta respuestas de la IA contra documentación oficial, discriminando sesgos, conceptos obsoletos o erróneos. | Investiga en fuentes confiables y utiliza la IA para estructurar información, verificando los datos principales antes de incluirlos en el portafolio. | Depende casi exclusivamente del texto arrojado por la IA. Acepta afirmaciones sin verificar en la documentación técnica oficial. | Presenta información sin procesar, con respuestas alucinadas, conceptos desactualizados o copy-paste directo sin revisión conceptual. |
| **Resolución de Algoritmos y Retos** | Resuelve los ejercicios aplicando estructuras de control y patrones óptimos. Explica el flujo de ejecución paso a paso con diagrama o pseudocódigo explicativo. | Resuelve correctamente la mayoría de los ejercicios propuestos. La explicación del algoritmo es clara aunque sintetizada. | Resuelve los ejercicios de forma parcial o con lógica ineficiente. La explicación del flujo de datos es confusa. | No resuelve los retos propuestos o entrega código no funcional/incompleto sin explicación de su funcionamiento. |
| **Reflexión Cognitiva y Registro de Aprendizaje** | Incluye una sección de auto-evaluación reflexiva: qué aprendió, qué dificultades enfrentó con la IA/herramientas y cómo las superó argumentadamente. | Incluye comentarios reflexivos sobre el proceso de aprendizaje y los obstáculos encontrados durante la resolución de los ejercicios. | Reflexiones breves, superficiales o genéricas ("se me dificultó el código pero la IA lo resolvió"). | Omite la sección reflexiva o presenta textos generados automáticamente sin aportación personal. |

---

## 4. Rúbrica 3: Reportes de Prácticas de Laboratorio (20% de la Evaluación)

Evalúa el trabajo práctico en el laboratorio de cómputo y la documentación técnica formal de los experimentos y desarrollos realizados.

| Criterio / Dimensión | Excelente (100% - 90%) | Notable / Bueno (89% - 80%) | Suficiente (79% - 70%) | Insuficiente (< 70%) |
| :--- | :--- | :--- | :--- | :--- |
| **Documentación Técnica del Proceso** | Documenta de forma impecable la práctica: objetivo, arquitectura, código comentado, captura de evidencia funcional, casos de prueba ejecutados y manejo de excepciones. | Documenta de forma clara la práctica con capturas de pantalla, explicación del código desarrollado y pruebas funcionales básicas. | Documentación incompleta en la presentación de evidencias funcionales. | Reporte deficiente o extemporáneo. Carece de capturas, código explicativo o de la mínima estructura solicitada. |
| **Prompting Crítico y Registro de Interacción con IA** | Presenta la bitácora de prompting: muestra los prompts iniciales, el análisis de las respuestas obtenidas, los errores corregidos manualmente y las pruebas de refactorización. | Incluye el registro de prompts utilizados y menciona brevemente los cambios realizados al código sugerido por la IA. | Solo incluye el prompt utilizado sin analizar si la respuesta de la IA fue correcta o si requirió ajustes técnicos. | No documenta el uso de IA o niega su uso a pesar de evidenciarse patrones claros de generación automática sin revisión. |
| **Validación y Pruebas de Software** | Diseña e implementa casos de prueba (entradas válidas, inválidas, ataques de inyección/XSS básicos). Demuestra que el software es robusto. | Ejecuta pruebas funcionales estándar (Happy Path) verificando que el software responda a las entradas requeridas. | Pruebas mínimas o limitadas a un solo escenario. El software falla ante entradas inesperadas o datos vacíos. | No realiza pruebas. El código reportado no ejecuta o falla al primer intento de interacción. |

---

## 5. Rúbrica 4: Bitácora Técnica, Apuntes y Resúmenes (5% de la Evaluación)

Evalúa el seguimiento diario del estudiante, el orden metacognitivo y la sistematización personal del conocimiento de la asignatura.

| Criterio / Dimensión | Excelente (100% - 90%) | Notable / Bueno (89% - 80%) | Suficiente (79% - 70%) | Insuficiente (< 70%) |
| :--- | :--- | :--- | :--- | :--- |
| **Sistematización Metacognitiva del Conocimiento** | Construye anotaciones personalizadas, mapas mentales, diagramas de flujo o esquemas de arquitectura propios. Traduce conceptos complejos a su propio lenguaje técnico. | Registra apuntes claros y ordenados de cada clase, utilizando organizadores gráficos para estructurar la información clave. | Apuntes parciales o basados principalmente en transcripciones literales de diapositivas o salidas de IA sin personalización. | Bitácora incompleta, desordenada o inexistente. Carece de evidencias de seguimiento clase a clase. |
| **Registro de Errores y Lecciones Aprendidas** | Mantiene una "Bitácora de Bugs y Soluciones" donde anota errores recurrentes de sintaxis/lógica, mensajes de la consola y la estrategia seguida para solucionarlos. | Anota los errores más relevantes encontrados durante las sesiones de laboratorio y la solución correspondiente. | Anotaciones ocasionales sobre errores sin explicar la causa ni el método de solución. | No registra errores ni lecciones aprendidas. La bitácora se limita a textos teóricos sin vinculación práctica. |

---

## 6. Rúbrica 5: Participación, Trabajo Colaborativo y Actitudes (5% de la Evaluación)

Evalúa el desempeño actitudinal, la ética profesional, la asistencia, el compromiso con el aprendizaje y la colaboración en equipo.

| Criterio / Dimensión | Excelente (100% - 90%) | Notable / Bueno (89% - 80%) | Suficiente (79% - 70%) | Insuficiente (< 70%) |
| :--- | :--- | :--- | :--- | :--- |
| **Proactividad y Discusión Técnica en Clase** | Participa activamente proponiendo soluciones, formulando preguntas críticas sobre las respuestas de la IA o los temas expuestos y apoyando en debates técnicos. | Participa regularmente cuando se le solicita, aportando ideas pertinentes a la discusión de casos o revisión de código. | Su participación es pasiva o se limita a responder preguntas directas con aportes mínimos. | Muestra desinterés, interrumpe el desarrollo de la clase o no participa en las actividades académicas. |
| **Ética Académica y Responsabilidad en el Uso de IA** | Demuestra transparencia total en el uso de herramientas tecnológicas. Asume la responsabilidad autoral de todo el código presentado y comprende su funcionamiento. | Es transparente sobre el uso de IA y demuestra comprender la mayor parte del trabajo entregado bajo su autoría. | Muestra reticencia a explicar fragmentos de su trabajo o intenta hacer pasar contenido íntegro de IA como propio sin curaduría. | Falta a la ética académica (plagio de compañeros o copia directa no declarada de IA sin comprensión). Incapaz de defender su trabajo. |
| **Trabajo Colaborativo, Asistencia y Puntualidad** | Asiste puntualmente a clases y laboratorios (≥ 95%). Asume roles de liderazgo constructivo en el equipo del proyecto integrador, facilitando el trabajo en grupo. | Mantiene buena asistencia y puntualidad (90% - 94%). Colabora de manera constante y respetuosa en su equipo de trabajo. | Cumple con el mínimo de asistencia (80% - 89%). Su colaboración en equipo es limitada o requiere supervisión del docente. | Inasistencias frecuentes (< 80%), impuntualidad sistemática o conflictos no resueltos que afectan el desempeño del equipo. |