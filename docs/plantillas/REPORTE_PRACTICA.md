<!-- 
================================================================================
TECNOLÓGICO SUPERIOR DE JALISCO (ITS ZAPOPAN)
DIVISIÓN DE INGENIERÍA EN SISTEMAS COMPUTACIONALES
ASIGNATURA: PROGRAMACIÓN WEB (AEB-1055)
PLANTILLA OFICIAL DE REPORTE DE PRÁCTICAS DE LABORATORIO
================================================================================
-->

# Reporte de Práctica N° [Número de Práctica]
**Título de la Práctica:** [Nombre corto y descriptivo de la práctica]

---

##  Información General

| Campo | Detalle / Especificación |
| :--- | :--- |
| **Institución:** | Tecnológico Superior de Jalisco — TSJ Zapopan |
| **Carrera:** | Ingeniería en Sistemas Computacionales |
| **Asignatura:** | Programación Web (Clave: AEB-1055) |
| **Unidad Temática:** | [Ej. Unidad 2: HTML5, CSS3 y XML / Unidad 3: JavaScript / etc.] |
| **Estudiante(s):** | [Nombre(s) completo(s) y Número(s) de Control] |
| **Profesor:** | Mtro. León Miguel Ramos Corchado |
| **Fecha de Realización:** | DD / MM / 2026 |
| **Fecha de Entrega:** | DD / MM / 2026 |

---

##  1. Objetivos

### 1.1 Objetivo General
* [Escribe aquí el objetivo principal de la práctica (Qué se va a desarrollar o analizar y para qué)].

### 1.2 Objetivos Específicos / Competencias a Desarrollar
* Aplica lenguajes de marcado, de presentación y/o programación cliente-servidor en el desarrollo web.
* Diseña e implementa soluciones con apego a buenas prácticas de código y diseño responsivo/modular.
* [Agregar objetivos específicos puntuales de la práctica].

---

##  2. Entorno de Desarrollo y Herramientas

* **Editor / IDE:** Visual Studio Code (VS Code)
* **Control de Versiones:** Git / GitHub (`TEMPLATE-ISIC-PROGRAWEB`)
* **Navegadores de Prueba:** Google Chrome / Mozilla Firefox / Brave
* **Lenguajes y Frameworks:** [Ej. HTML5, CSS3, JavaScript ES6+, PHP, Node.js, etc.]
* **Servidor Local / Nube:** [Ej. XAMPP, Live Server, Vercel, Render, etc.]
* **Herramientas de IA Asistente (opcional):** [Ej. ChatGPT, Claude, GitHub Copilot, Gemini]

---

##  3. Fundamentos Teóricos
> *Escribe una síntesis conceptual de los temas aplicados en la práctica (máximo 300-500 palabras). Debes citar fuentes oficiales como MDN Web Docs, W3C o la especificación del lenguaje.*

[Escribe aquí el marco teórico. Ej. Explicación de la API Fetch, Grid/Flexbox en CSS, Modelo Vista Controlador, Estructura del DOM, etc.]

---

##  4. Desarrollo e Implementación

### 4.1 Estructura del Proyecto
Muestra el árbol de archivos generado dentro de la carpeta correspondiente a esta práctica (`/src/unidad-X/...`):

```text
src/unidad-X-nombre/practica-Y/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── README.md
```


```

### 4.2 Fragmentos de Código Clave y Explicación

> *No pegues todo el código. Incluye solo los bloques más relevantes o complejos de la práctica e introduce una explicación técnica de su funcionamiento.*

####  [Nombre del Módulo o Componente 1]

```html
<!-- Ejemplo: Fragmento HTML o Maquetación -->

```

* **Explicación técnica:** [Describe el flujo, uso de etiquetas semánticas, selectores o lógica aplicada].

####  [Nombre del Módulo o Componente 2]

```javascript
// Ejemplo: Fragmento JS / Consumo de API / Manipulación del DOM

```

* **Explicación técnica:** [Explica la lógica del algoritmo, manejo de eventos o interacción cliente-servidor].

---

##  5. Registro de Curaduría y Uso Ético de IA (Bitácora de IA)

> *Sección obligatoria en caso de haber utilizado herramientas de Inteligencia Artificial Generativa durante el desarrollo.*

| N° | Prompts Clave Utilizados | Propósito / Qué se solicitó | Resultado arrojado por la IA | Alucinaciones, Errores o Sesgos Detectados | Modificaciones, Refactorización y Decisión Técnica |
| --- | --- | --- | --- | --- | --- |
| 1 | *"Cómo centrar una cuadrícula de tarjetas usando CSS Grid responsivo"* | Maquetación gráfica responsiva del catálogo de productos. | Sugirió `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`. | Ningún error grave, pero usaba un margen fijo no deseado. | Se adaptó la regla dentro del archivo `styles.css` ajustando el `gap` y padding para móviles. |
| 2 | *"... prompt utilizado ..."* | [Propósito] | [Resultado] | [Errores/Sintaxis obsoleta] | [Decisión tomada por el estudiante] |

---

##  6. Pruebas, Resultados y Evidencias Visuales

### 6.1 Casos de Prueba Ejecutados

| ID | Descripción de la Prueba | Entrada / Acción | Resultado Esperado | Resultado Obtenido | Estado (Pasa / Falla) |
| --- | --- | --- | --- | --- | --- |
| T01 | Validar formulario de registro. | Clic en "Enviar" con campos vacíos. | Mostrar mensajes de error en rojo. | Muestra validación correcta en el DOM. | **PASA** |
| T02 | Responsividad en móviles. | Redimensionar viewport a 375px. | Ocultar menú y mostrar botón hamburguesa. | Menú colapsa adecuadamente. | **PASA** |

### 6.2 Capturas de Pantalla y Evidencias

> *Agrega las imágenes cargadas en la carpeta `docs/img/` o capturas demostrativas del funcionamiento.*


*Figura 1: Interfaz gráfica de la práctica ejecutada en el navegador.*


*Figura 2: Verificación de respuestas HTTP / Consola de desarrollador (F12).*

---

##  7. Diagnóstico de Errores y Solución de Problemas

> *Describe al menos un problema técnico u obstáculo encontrado durante la práctica (error de sintaxis, CORS, CSS roto, problema de ruta, etc.) y cómo lo resolviste.*

* **Problema encontrado:** [Descripción del error o comportamiento no deseado].
* **Causa raíz:** [Causa técnica del fallo].
* **Solución aplicada:** [Cómo lo solucionaste o refactorizaste].

---

##  8. Conclusiones y Auto-evaluación Reflexiva

### 8.1 Conclusión Técnica

[Escribe una conclusión individual sobre el aprendizaje obtenido, relacionando la práctica con el perfil profesional de la Ingeniería en Sistemas Computacionales].

### 8.2 Reflexión sobre el Proceso

* **¿Qué fue lo más complejo de implementar?** [Respuesta]
* **¿Qué competencias técnicas o blandas fortalecí?** [Respuesta]
* **¿Qué mejoras futuras se le podrían realizar a este desarrollo?** [Respuesta]

---

##  9. Referencias Bibliográficas (Estilo APA 7)

1. MDN Web Docs. (2026). *HTML: Lenguaje de etiquetas de hipertexto*. Mozilla Developer Network. Recuperado de https://developer.mozilla.org/es/docs/Web/HTML
2. W3C. (2026). *Cascading Style Sheets (CSS) Snapshot*. World Wide Web Consortium. Recuperado de https://www.w3.org/Style/CSS/
3. [Agregar bibliografía o documentación oficial consultada].

```

---

###  ¿Cómo guardarlo rápidamente desde la terminal de VS Code?

Si quieres volcar este contenido directamente en el archivo `REPORTE_PRACTICA.md` que acabas de crear desde VS Code, solo abre el archivo en el editor, copia todo el bloque de arriba y guárdalo (`Ctrl + S`).

```