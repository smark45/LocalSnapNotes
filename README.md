# 🎨 Local Image Annotator & Step Collector

Una herramienta web ligera, interactiva y **100% local (Client-Side)** diseñada para documentadores, desarrolladores y creadores de contenido que necesitan estructurar capturas con pasos numerados, notas explicativas y colecciones ordenadas sin subir sus imágenes a servidores externos.

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
![Privacidad](https://img.shields.io/badge/Privacidad-100%25%20Local%20(Sin%20Backend)-blue.svg)
![Tecnologías](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JS-orange.svg)

---

## 🚀 Características Principales

- **🔒 Privacidad y Procesamiento Local:** Todo se ejecuta en la memoria del navegador y mediante HTML5 Canvas. Cero peticiones de red para procesar o guardar imágenes.
- **📂 Gestión de Colecciones Temporales:**
  - Sube múltiples imágenes a la vez o pega capturas de pantalla continuas con `Ctrl + V`.
  - Reorganiza el orden de las capturas mediante **Drag & Drop** (arrastrar y soltar) o con botones de avance/retroceso.
  - Navega y edita individualmente cada imagen sin perder el avance de las demás.
- **✏️ Anotación Visual Rica:**
  - Flechas direccionales con selector de color.
  - Elipses y círculos envolventes.
  - Insignias numéricas (`1`, `2`, `3`...) correlativas automáticas en flechas y figuras.
  - **Soporte táctil completo:** Dibujo y arrastre adaptado para móviles, tablets y stylus.
- **📝 Documentación al Pie:**
  - Título principal con viñeta opcional (`•`).
  - Notas de pie de imagen numeradas automáticamente (`1 .-`, `2 .-`) sincronizadas con las figuras creadas.
- **📦 Opciones de Exportación:**
  - Descarga individual en formato PNG en alta resolución.
  - Copiado rápido directo al portapapeles del sistema operativo (`Clipboard API`).
  - **Descarga masiva en archivo `.zip`:** Exporta en un solo clic todas las imágenes editadas o todas las originales numeradas.

---

## 🎯 Ideal Para

- **Documentación Técnica & DevOps:** Manuales de instalación, diagramas de configuración y guías paso a paso.
- **QA & Soporte:** Reportar bugs visuales con pasos de reproducción sin filtrar datos confidenciales.
- **Tutoriales y Wikis:** Crear secuencias de imágenes listas para Markdown, Notion, Jira o Confluence.

---

## 💻 ¿Cómo Usarlo?

No requiere `npm install`, Node.js ni bases de datos:

1. Clona o descarga este repositorio
