# Proyecto de Análisis y Diseño de Sistemas - PetShop Huellitas & Snacks

Este repositorio contiene la plantilla estructurada y maquetada profesionalmente en LaTeX para el informe del caso de estudio de la **Tienda de Venta de Comida de Mascotas** ("PetShop Huellitas & Snacks").

---

## 👥 Integrantes del Equipo
1. **Xavier Sig**
2. **[Nombre Estudiante 2]**
3. **[Nombre Estudiante 3]**

---

## 🛠️ Guía de Configuración de LaTeX para el Equipo

Para editar y compilar el archivo principal `Informe.tex` en formato PDF, todos los integrantes deben contar con un entorno de LaTeX configurado. A continuación se presentan las opciones recomendadas:

### Opción 1: En la Nube (Recomendada y sin instalación)
La forma más rápida de trabajar de forma colaborativa sin instalar nada en tu computadora es usando **Overleaf**:
1. Crea una cuenta gratuita en [Overleaf](https://www.overleaf.com/).
2. Sube los archivos del repositorio (especialmente `Informe.tex` y la carpeta `imagenes/` con su contenido).
3. Asegúrate de configurar el compilador en **pdfLaTeX** en la sección *Menu* (esquina superior izquierda de Overleaf).
4. Haz clic en **Recompile** para generar el PDF.

---

### Opción 2: Escritorio con Visual Studio Code (Ideal para desarrolladores)
Si prefieres trabajar localmente en tu editor de código:
1. **Instala el Distribuidor de LaTeX:**
   - **Windows:** Descarga e instala [MiKTeX](https://miktex.org/download) (selecciona la instalación básica).
   - **macOS:** Descarga e instala [MacTeX](https://www.tug.org/mactex/).
   - **Linux:** Instala TeX Live mediante el gestor de paquetes (ej. `sudo apt install texlive-full`).
2. **Configura VS Code:**
   - Abre Visual Studio Code e instala la extensión **LaTeX Workshop** (creada por James Yu).
3. **Abre el proyecto:**
   - Abre la carpeta del proyecto en VS Code y abre `Informe.tex`. La extensión compilará automáticamente al guardar (`Ctrl + S` o `Cmd + S`) y podrás visualizar el PDF directamente en una pestaña lateral.

---

### Opción 3: Escritorio con TeXstudio (Editor clásico de LaTeX)
Si deseas un entorno dedicado clásico:
1. Instala **MiKTeX** (Windows) o **TeX Live** (Linux/Mac) como se indica en la opción anterior.
2. Descarga e instala [TeXstudio](https://www.texstudio.org/).
3. Abre `Informe.tex` en TeXstudio, y presiona **F5** (o el botón verde de "Compilar y Ver") para generar el documento.

---

## 📌 Notas Importantes para la Edición
- **Doble pasada de compilación:** Al realizar modificaciones en los índices (`\tableofcontents`) o agregar referencias dinámicas (`\label` y `\ref`), es necesario compilar el documento **dos veces** consecutivas para que las páginas y numeración se sincronicen correctamente.
- **Logotipos e Imágenes:** Toda imagen de los diagramas debe ubicarse dentro de la carpeta `imagenes/` y referenciarse en el código mediante `imagenes/NombreImagen.extension`.
