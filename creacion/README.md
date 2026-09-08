# 🛠️ Guía Paso a Paso: Creación del Bot en Google Gems (Gemini)

En este apartado se documenta el proceso técnico de configuración e implementación del **Tutor Socrático de Matemáticas** utilizando la función de Gems en Gemini.

---

## 📋 Pasos para la Configuración de la Gem

### Paso 1: Acceso a Gestor de Gems
- Acceder a [Gemini](https://gemini.google.com/).
- En el menú lateral izquierdo, seleccionar la opción **Gems** y hacer clic en **Crear nueva Gem** (o *New Gem*).

### Paso 2: Configuración Básica
- **Nombre:** MatBot-UNIVER.
- **Descripción:** Tu tutor de análisis de procedimientos matemáticos. Detectar el primer error, explicar y ayudar a corregir con claridad y paciencia.

### Paso 3: Inserción del System Prompt (Blindaje)
- En la sección **Instrucciones** (*Instructions*), pegar el prompt optimizado (disponible en `/prompt/prompt_blindado.txt`).
- **Puntos clave del prompt:**
  1. Restricción estricta de entregar la respuesta final.
  2. Uso de pistas incrementales y preguntas guía.
  3. Detección de errores conceptuales en el procedimiento del alumno.

### Paso 4: Pruebas y Validación (Testing)
- Probar escenarios donde el estudiante exige la respuesta directa (ej. *"Dame el valor de x"*).
- Verificar que el bot responda con repreguntas o explicación de conceptos en lugar del resultado.

### Paso 5: Publicación y Compartición
- Guardar la Gem y ajustar los permisos a **Compartido vía enlace** para que los alumnos y el docente puedan interactuar con ella.

---

## 📸 Capturas del Proceso
*(Las imágenes en secuencia se encuentran adjuntas en esta misma carpeta).*
