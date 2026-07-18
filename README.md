# Proyecto de Análisis y Diseño de Sistemas - PetShop Huellitas & Snacks

Este repositorio contiene la plantilla estructurada y maquetada profesionalmente en LaTeX para el informe del caso de estudio de la **Tienda de Venta de Comida de Mascotas** ("PetShop Huellitas & Snacks").

---

## 🛠️ Guía de Configuración de LaTeX (Visual Studio Code)

Para poder visualizar, editar y compilar localmente el archivo principal `Informe.tex` en formato PDF, sigue los siguientes pasos:

### 1. Instalar el Distribuidor de LaTeX
Debes instalar el motor de compilación correspondiente a tu sistema operativo:
- **Windows:** Descarga e instala [MiKTeX](https://miktex.org/download) (selecciona la opción de instalación básica).
- **macOS:** Descarga e instala [MacTeX](https://www.tug.org/mactex/).
- **Linux:** Instala TeX Live desde el gestor de paquetes de tu distribución (ej. `sudo apt install texlive-full` en distribuciones basadas en Debian/Ubuntu).

### 2. Configurar VS Code
Para tener un entorno interactivo y moderno dentro de tu editor de código:
1. Abre **Visual Studio Code**.
2. Dirígete a la sección de Extensiones (`Ctrl + Shift + X` o `Cmd + Shift + X`).
3. Busca e instala la extensión **LaTeX Workshop** (desarrollada por James Yu).

### 3. Abrir y Compilar el Proyecto
1. Abre la carpeta raíz del proyecto en VS Code.
2. Abre el archivo principal `Informe.tex`.
3. Al guardar el archivo (`Ctrl + S` en Windows/Linux o `Cmd + S` en macOS), la extensión compilará automáticamente el código.
4. Para previsualizar el PDF resultante directamente en VS Code, presiona el icono de la lupa ("View LaTeX PDF") en la esquina superior derecha o usa el atajo `Ctrl + Alt + V` (o `Cmd + Option + V`).

---

## 📌 Notas Importantes para la Edición
- **Doble pasada de compilación:** Al realizar modificaciones en los índices (`\tableofcontents`) o agregar referencias dinámicas (`\label` y `\ref`), es necesario compilar el documento **dos veces** consecutivas para que las páginas y numeración se sincronicen correctamente.
- **Logotipos e Imágenes:** Toda imagen de los diagramas debe ubicarse dentro de la carpeta `imagenes/` y referenciarse en el código mediante `imagenes/NombreImagen.extension`.
