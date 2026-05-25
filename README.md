# Cursillo de LaTeX - 3 Sesiones

**Un curso práctico e intensivo de LaTeX orientado a estudiantes universitarios y profesores.**

Este repositorio contiene todo el material del **Cursillo de LaTeX de 3 sesiones** diseñado para enseñar lo esencial de LaTeX de forma rápida y aplicada.
Después de cada sesión habrán tareas sencillas, para la elaboración de contenido para los cursos.

---

## Objetivo del curso

Enseñar los fundamentos de LaTeX suficientes para que los participantes puedan escribir exámenes, controles, tareas, talleres y documentos académicos con calidad profesional en poco tiempo.

---

## Estructura del curso

### **Sesión 1: Introducción y bases**

- Instalación de LaTeX en **Windows** (MiKTeX + TeXstudio) y **macOS** (MacTeX + TeXShop / TeXstudio)
- Estructura básica de un documento: **Preambulo** vs **Documento**
- Paquetes más utilizados (casi siempre necesarios):
  - `inputenc`, `fontenc`, `babel`
  - `amsmath`, `amssymb`, `amsthm`
  - `geometry`, `graphicx`, `enumitem`, etc.
- Sintaxis básica de ecuaciones en modo math
- Ecuaciones básicas: polinomios, fracciones, potencias
- **Template principal**: `plantilla-prueba.tex` (y sus variantes)

**Plantillas incluidas:**
- `plantilla-prueba.tex` / `plantilla-examen.tex`
- `plantilla-tarea.tex`
- `plantilla-control.tex`
- `plantilla-taller.tex`
- `plantilla-guía.tex`

---

### **Sesión 2: Ecuaciones avanzadas (Núcleo del curso)**

- Escritura avanzada de ecuaciones con `amsmath`
- Símbolos más utilizados:
  - Integrales, sumatorias, productorias
  - Derivadas y derivadas parciales
  - Límites, fracciones continuas
  - Matrices y determinantes
  - Alineación de ecuaciones (`align`, `gather`, `cases`, etc.)
- Entornos matemáticos importantes
- Cómo crear **tablas** (`tabular`)

---

### **Sesión 3: Listas y Gráficos**

- Listas numeradas (`enumerate`) y con viñetas (`itemize`)
- Personalización de listas
- **Inserción de gráficos**:
  - Formatos aceptados (`png`, `jpg`, `pdf`, `eps`)
  - Cómo insertar imágenes con `graphicx`
  - Ubicación y escalado (`figure`, `center`, `[h!tp]`, escalado porcentual)
- Gráficos de funciones con **plantilla TikZ** (solo uso del template, sin explicación profunda de TikZ)

---

## Estructura del repositorio

 ## FALTA DETALLE CON TREE

# Requisitos

- **Windows**: MiKTeX + TeXstudio (recomendado)
- **macOS**: MacTeX + TeXstudio o TeXShop
- Editor recomendado: **TeXstudio** (para principiantes)

---

## Cómo usar las plantillas

1. Copia la plantilla correspondiente
2. Cambia los datos en el preámbulo (nombre, asignatura, fecha, etc.)
3. Escribe tu contenido
4. Compila con **pdfLaTeX**

---

## Público objetivo

- Estudiantes universitarios
- Profesores que quieran mejorar la presentación de sus materiales

---

## Autor

**José Alejandro Aburto, PhD**  
Creado para el cursillo de LaTeX 2026

---

## Licencia

Este material es de uso libre para fines educativos. Se agradece la mención al autor si se reutiliza o modifica.

