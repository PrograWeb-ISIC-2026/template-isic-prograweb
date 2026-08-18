# 📓 Bitácora de Uso de Inteligencia Artificial Generativa y Curaduría

**Práctica / Unidad:** [Ejemplo: Práctica 2 - Maquetación y Formularios]  
**Fecha:** [DD/MM/AAAA]

---

### 1. Registro de Interacción (Prompting)
* **Herramienta utilizada:** (ChatGPT / Claude / GitHub Copilot / Gemini)
* **Prompt Principal Enviado:**
> *"Escribe un formulario HTML5 con validación JS para registro de usuarios..."*

---

### 2. Análisis Crítico y Curaduría
* **Respuesta recibida:** La IA generó el código base con los campos de entrada y la estructura.
* **Errores, Alucinaciones o Ineficiencias Detectadas:**
  * *Error 1:* La IA utilizó código JS obsoleto (`var` en lugar de `const`/`let`).
  * *Error 2:* No incluyó etiquetas de accesibilidad (`aria-label`) ni soporte para pantallas pequeñas.
* **Acción de Refactorización / Corrección Aplicada:**
  * Se reescribió la lógica de validación usando `addEventListener` y sintaxis moderna de ES6.
  * Se ajustaron las reglas CSS con Flexbox/Grid para asegurar diseño responsivo.

---

### 3. Validación y Pruebas
* **Prueba realizada:** Pruebas manuales en navegador + verificación con GitHub Actions.
* **Resultado:** [Pasa con éxito / Requiere ajustes]