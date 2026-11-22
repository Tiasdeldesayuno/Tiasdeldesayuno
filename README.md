# Fundación Tías del Desayuno 💛

Sitio web oficial y *landing page* informativa para la **Fundación Tías del Desayuno**, una organización 100% voluntaria dedicada al acompañamiento, apoyo y contención de niños y niñas con cáncer y sus familias en el Hospital Sótero del Río (Puente Alto, Chile).

🌐 **Sitio Web en vivo:** [https://tiasdeldesayuno.github.io/Tiasdeldesayuno/](https://tiasdeldesayuno.github.io/Tiasdeldesayuno/)

---

## 📋 Tabla de Contenidos
- [Características del Sitio](#-características-del-sitio)
- [Secciones de la Página](#-secciones-de-la-página)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Ejecución Local](#-ejecución-local)
- [Despliegue en GitHub Pages](#-despliegue-en-github-pages)
- [Sobre la Fundación y Donaciones](#-sobre-la-fundación-y-donaciones)

---

## ✨ Características del Sitio
* **Diseño Responsivo:** Adaptado para teléfonos móviles, tablets y computadores de escritorio.
* **Carga Rápida y Ligera:** Desarrollado sin frameworks pesados ni librerías innecesarias.
* **Accesible y Semántico:** Estructurado siguiendo buenas prácticas de accesibilidad web (etiquetas semánticas ARIA).
* **Función Copiar Datos:** Facilita la copia de los datos bancarios para transferencias directas.

---

## 🗂️ Secciones de la Página
1. **Inicio / Banner Destacado:** Presentación del propósito y llamados a la acción (CTA) para donar y conocer la labor.
2. **Sobre Nosotras:** Historia de la fundación desde sus inicios en el año 2007.
3. **Propósito, Misión y Visión:** Declaración de valores y metas de acompañamiento hospitalario.
4. **Servicios:** Desayunos solidarios, acompañamiento en etapa terminal, visitas domiciliarias, terapias complementarias (Reiki y regeneración celular) y espacios de bienestar para madres y acompañantes.
5. **Actividades y Celebraciones:** Calendario de eventos anuales (Día del Niño, Navidad, etc.).
6. **Proyectos y Sueños:** Espacio dedicado a las metas logradas e iniciativas para humanizar los espacios hospitalarios.
7. **Voluntariado:** Reconocimiento al equipo de voluntarios, incluyendo ex-pacientes oncológicos que regresan a apoyar.
8. **Ubicación y Horarios:** Información práctica de atención en el Hospital Sótero del Río.
9. **Donaciones:** Sección interactiva con los datos para transferencias bancarias directas.

---

## 🛠️ Tecnologías Utilizadas
* **HTML5:** Estructuración semántica de la página.
* **CSS3:** Estilos personalizados, diseño con Flexbox/Grid y variables CSS.
* **JavaScript (Vanilla):** Lógica del menú navegacional, modales e interacción de copiado al portapapeles.
* **Google Fonts:** Tipografía web.
* **GitHub Pages:** Alojamiento y despliegue continuo.

---

## 📁 Estructura del Proyecto

```text
Tiasdeldesayuno/
├── index.html          # Estructura principal de la página
├── styles.css          # Diseño y colores
├── script.js           # Textos de actividades, proyectos y sueños + interactividad
├── img/                # Fotos del sitio
├── favicon.svg         # Ícono del sitio web
├── sitemap.xml         # Mapa del sitio para Google
├── robots.txt          # Indicaciones para buscadores
└── README.md           # Documentación del proyecto
```

> **Editar contenido:** las fotos se reemplazan en `img/` con el mismo nombre; los textos de actividades, proyectos y sueños están al inicio de `script.js`; los textos fijos y los datos de donación, en `index.html`.

---

## 💻 Ejecución Local
No requiere instalación ni compilación. Descarga el repositorio y abre `index.html` en el navegador, o en Visual Studio Code usa la extensión **Live Server** (clic derecho en `index.html` → *Open with Live Server*).

---

## 🚀 Despliegue en GitHub Pages
1. En el repositorio ve a **Settings → Pages**.
2. En *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y pulsa **Save**.
3. Tras 1 o 2 minutos el sitio queda disponible en `https://tiasdeldesayuno.github.io/Tiasdeldesayuno/`.

Para actualizar el sitio basta con subir los archivos modificados al repositorio (**Add file → Upload files**).

---

## 💜 Sobre la Fundación y Donaciones
Los datos para donar o apadrinar a un niño se encuentran en la sección **Donar ahora** del sitio web. Para consultas: fundaciontiasdeldesayuno@gmail.com
