<div align="center">

# 🚀 Mike Mejía · Landing Page

### Data Engineer & Data Analyst · Professional Portfolio

[![Website](https://img.shields.io/badge/Website-codexstudiove.com-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white)](https://www.codexstudiove.com)
[![GitHub](https://img.shields.io/badge/GitHub-@sebastiancoronadev-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sebastiancoronadev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sebastiancoronadev)
[![Email](https://img.shields.io/badge/Email-sebastiancorona@codexstudiove.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sebastiancorona@codexstudiove.com)

---

### Created by:

<h1>@sebastiancoronadev&nbsp;<sub><a href="https://github.com/sebastiancoronadev" target="_blank" title="Verified because I deliver excellence"><img src="https://i.ibb.co/1F3qqjd/verified.gif" width="30"></a></sub></h1>

**Lead Developer** · [codexstudiove.com](https://www.codexstudiove.com)

---

</div>

---

# 🇺🇸 ENGLISH SECTION

## 📋 Project Overview

**Mike Mejía Landing Page** is a professional static portfolio website designed to showcase the profile of a Data Engineer & Data Analyst. The page presents a modern, bilingual interface with a clean aesthetic, interactive elements, and comprehensive SEO implementation.

Developed as a fully static, self-contained web application, the site runs entirely in the browser with zero external dependencies beyond CDN-hosted libraries. All content is managed client-side with a built-in internationalization system supporting both English and Spanish.

This project was created as a practice landing page by Sebastián Corona to demonstrate the professional profile of Mike Mejía.

---

## 🏗️ Project Structure

```
portafolio-miguel/
├── index.html          # Main entry point
├── robots.txt          # Search engine configuration
├── sitemap.xml         # SEO site map
├── css/
│   └── style.css       # Complete stylesheet
├── js/
│   └── app.js          # JavaScript with translations & animations
└── images/
    ├── miguel.jpg      # Profile photo of Mike Mejía
    └── codex-logo-web.png  # Creator logo (Codex Studio)
```

---

## 🛠 Technology Stack

<div align="center">

<!-- TECHNOLOGIES -->
<a href="https://www.google.com/search?q=HTML5+explanation" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=html" title="HTML5 - Semantic Structure" />
</a>
<a href="https://www.google.com/search?q=CSS3+explanation" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=css" title="CSS3 - Styling & Animations" />
</a>
<a href="https://www.google.com/search?q=JavaScript+explanation" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=js" title="JavaScript ES6+ - Business Logic" />
</a>
<br>

<!-- TOOLS -->
<a href="https://www.google.com/search?q=Git+version+control+explanation" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=git" title="Git - Version Control" />
</a>
<a href="https://www.google.com/search?q=GitHub+explanation" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=github" title="GitHub - Repository Hosting" />
</a>

</div>

### Core Technologies

| Technology | Usage |
|------------|-------|
| **HTML5** | Semantic page structure. Single `index.html` containing all sections. |
| **CSS3** | Single `style.css` with custom variables, keyframe animations, flexbox, grid, media queries, pseudoelements, backdrop-filter, transitions, and gradients. |
| **JavaScript (Vanilla ES6+)** | Single `app.js` with i18n system, IntersectionObserver for scroll reveal, animated counters, canvas particles, language dropdown, form simulation, and typewriter effect. |

### External Libraries (CDN)

| Library | Version | Usage |
|---------|---------|-------|
| **Font Awesome Free** | 6.5.1 | Vector icons (GitHub, LinkedIn, email, gears, cloud, servers, chevron, etc.) |
| **Flag Icons** | 7.0.0 | Country flags (Colombia, United States) for language selector |
| **Devicons** | Latest | Technology logos (Python, PostgreSQL, JavaScript, Bash, Apache, Spark, Pandas, NumPy, AWS, Docker, Linux, Node.js, Express, MySQL) |
| **Google Fonts** | Latest | Inter (sans-serif) and JetBrains Mono (monospace for code) |

### What Was NOT Used

- **No Tailwind CSS** — All CSS is custom, hand-written in `style.css`
- **No TypeScript** — Pure Vanilla JavaScript (ES6+)
- **No React, Vue, Angular, or any framework**
- **No Node.js, npm, webpack, or bundlers**
- **No database or backend**

---

## ✨ Implemented Features

### Navigation
- Fixed navigation bar with 5 internal links (About, Stack, Projects, Experience, Contact)
- Transparent at page start
- Becomes dark with blur (backdrop-filter) and teal border on scroll

### Bilingual Language Selector (ES/EN)
- Custom dropdown with Colombia and United States flags
- Complete i18n translation object
- localStorage persistence
- Chevron rotates on open/close. Flags do NOT rotate.
- Translations for: navigation, hero, stats, about, stack, projects, experience, contact, footer, and disclaimer

### Hero Section
- Dark background with 3-tone gradient
- Animated particles generated with Canvas API (pure JavaScript)
- Decorative blobs (blurred circles)
- SVG wave shape divider at bottom for smooth transition
- Circular profile photo with teal border and glow shadow
- Animated name "Mejía" with tilde and animated white gradient

### Stats
- 4 cards with animated counters triggered on scroll
- Circular SVG icons with solid color background (no opacity)
- Numbers animate with cubic easing

### About
- Descriptive text in 3 paragraphs
- Code block with typewriter effect (activated on scroll)
- Blinking cursor

### Stack (Technologies)
- 4 categories with custom SVG icons
- Technology chips with Devicons logos
- Hover effect: 360° spin + elevation + shadow + teal border
- On hover removal, spin returns to original position

### Projects
- 3 cards with colored backgrounds (teal, amber, indigo)
- Shimmer effect (glare) on hover
- Bullet-list for technologies used
- Central project with "Featured Project" badge and star SVG

### Experience (Timeline)
- Vertical timeline with 3-color gradient
- Colored dots on each entry
- Cards with period, role, and description

### Contact
- Centered form with no hover effect
- Fields: name, email, subject, message
- Submit button with loading animation and confirmation
- No contact information sidebar (removed)

### Footer
- 3 columns: Email, Location, Modality (white icons)
- Social networks: GitHub and LinkedIn (real links), X and Email (disabled with prohibition icon)
- Codex Studio logo linking to codexstudiove.com
- Bilingual disclaimer about copyright

---

## 🔍 SEO Implementation

| Element | Status |
|---------|--------|
| `<title>` | Mike Mejía \| Data Engineer & Data Analyst |
| `<meta name="description">` | 160-character description |
| `<meta name="keywords">` | Relevant keywords |
| `<meta name="author">` | Mike Mejía |
| `<meta name="robots">` | index, follow |
| `<link rel="canonical">` | Canonical URL |
| `<link rel="alternate" hreflang="es">` | Spanish version |
| `<link rel="alternate" hreflang="en">` | English version |
| Open Graph (`og:title`, `og:description`, `og:image`, `og:url`, `og:locale`) | Complete |
| Twitter Card (`twitter:card`, `twitter:title`, `twitter:description`) | Complete |
| Schema.org JSON-LD (Person) | Structured data |
| `robots.txt` | Allow all, point to sitemap |
| `sitemap.xml` | Main URL with hreflang alternates |
| Favicon | 🎯 emoji via inline SVG |

---

## 🔒 Security

### Current Status
- **No SSL certificate implemented**. GitHub Pages offers free HTTPS, but it must be enabled in repository settings.
- **Currently the page uses HTTP** (not secure). Browsers will show a "Not Secure" warning.

### Security Risks
- **Contact Form**: Does not send data to any server. It's purely a visual simulation with `setTimeout`. No SQL injection or XSS risk due to no backend.
- **External CDNs**: Libraries loaded from public CDNs. This implies trust in third parties. Subresource Integrity (SRI) is recommended.
- **External Links**: Use `target="_blank"` with `rel="noopener"` to prevent tabnabbing.

### Pending Security Improvements
- Enable HTTPS on GitHub Pages
- Add SRI to CDN resources
- Implement a real backend for the form with sanitization and rate limiting
- Add Content Security Policy (CSP)

---

## 📊 Performance

### Strengths
- **Single CSS and JS request** — Files are manually minified
- **No heavy frameworks** — No React, Vue, or Tailwind
- **Profile image**: Loaded with `loading="eager"` (critical). Should be optimized to WebP format, max 100-150 KB.
- **Fonts**: Only 2 families (Inter + JetBrains Mono) loaded from Google Fonts

### Areas for Improvement
- **Unoptimized images**: `miguel.jpg` should be converted to WebP and resized to exactly 320×320
- **No lazy loading**: Devicons images lack `loading="lazy"`
- **No compression**: GitHub Pages handles Gzip/Brotli automatically
- **No custom cache configuration**: GitHub Pages applies default caching

---

## 📦 Dependencies

| Dependency | URL | Purpose |
|------------|-----|---------|
| Font Awesome 6.5.1 | `cdnjs.cloudflare.com` | Icons |
| Flag Icons 7.0.0 | `cdn.jsdelivr.net` | Country flags |
| Google Fonts (Inter) | `fonts.googleapis.com` | Main typography |
| Google Fonts (JetBrains Mono) | `fonts.googleapis.com` | Monospace code font |
| Devicons (Multiple) | `cdn.jsdelivr.net/gh/devicons` | Technology logos |

---

## 🚀 Deployment

### Local Execution

```bash
# Navigate to project directory
cd /path/to/portafolio-miguel

# Open in browser
start index.html      # Windows
open index.html       # macOS
xdg-open index.html   # Linux
```

### Hosting Deployment

**Option 1: GitHub Pages (Free)**
```bash
# Create repository: MikeMejia-Data-Dev.github.io
git init
git add .
git commit -m "Deploy landing page"
git remote add origin https://github.com/MikeMejia-Data-Dev/MikeMejia-Data-Dev.github.io.git
git push -u origin main
# Enable GitHub Pages in Settings > Pages
# Enable HTTPS in Settings > Pages > Enforce HTTPS
```

**Option 2: Custom Domain (Optional)**
- Purchase `mikemejia.dev` (Namecheap, Cloudflare Registrar, ~$12/year)
- Configure DNS (CNAME or A records) pointing to GitHub Pages
- Add `CNAME` file in repository root

**Option 3: Cloudflare (Free, Recommended)**
- Add domain to Cloudflare for CDN, free SSL, analytics, and DDoS protection
- Configure SSL Flexible or Full

---

## 📋 Pending Tasks

| Task | Priority | Description |
|------|----------|-------------|
| **Enable HTTPS** | **Critical** | In GitHub Pages Settings > Enforce HTTPS |
| **Purchase domain** | High | Register `mikemejia.dev` and configure DNS |
| **Optimize images** | High | Convert `miguel.jpg` to WebP, resize to 320×320 |
| **Push to GitHub** | High | Create repository and enable GitHub Pages |
| **Configure Cloudflare** | Medium | Add CDN, SSL, analytics, DDoS protection |
| **Google Analytics** | Medium | Add tracking tag for visitor statistics |
| **Google Search Console** | Medium | Verify site ownership and submit sitemap |
| **Functional Form** | Low | Implement backend (Formspree, Netlify Forms, or custom API) |
| **SRI** | Low | Add integrity hashes to CDN resources |
| **Content Security Policy** | Low | Add CSP header to prevent XSS |
| **PWA** | Optional | Add manifest.json and service worker |

---

## 📄 License & Credits

This site is a practice landing page developed by **Sebastián Corona** to showcase the professional profile of **Mike Mejía**.

All copyrights belong to **Mike Mejía** and **Sebastián Corona**.

> ℹ️ **Disclaimer**: If Mike Mejía prefers not to appear on this website, the content will be respectfully removed immediately.

---

## 📬 Contact

**Developer:** Sebastián Corona  
📍 Valencia, Carabobo, Venezuela  
✉️ sebastiancorona@codexstudiove.com  
🌐 [www.codexstudiove.com](https://www.codexstudiove.com)  

**Profile Owner:** Mike Mejía  
🔗 [github.com/MikeMejia-Data-Dev](https://github.com/MikeMejia-Data-Dev)

---

---

# 🇪🇸 SECCIÓN EN ESPAÑOL

## 📋 Descripción del Proyecto

**Landing Page de Mike Mejía** es un sitio web de portafolio estático profesional diseñado para mostrar el perfil de un Data Engineer & Data Analyst. La página presenta una interfaz moderna y bilingüe con una estética limpia, elementos interactivos y una implementación SEO completa.

Desarrollada como una aplicación web completamente estática y autocontenida, el sitio se ejecuta completamente en el navegador sin dependencias externas más allá de las librerías alojadas en CDN. Todo el contenido se gestiona en el lado del cliente con un sistema de internacionalización integrado que soporta inglés y español.

Este proyecto fue creado como una landing page de práctica por Sebastián Corona para demostrar el perfil profesional de Mike Mejía.

---

## 🏗️ Estructura del Proyecto

```
portafolio-miguel/
├── index.html          # Punto de entrada principal
├── robots.txt          # Configuración para motores de búsqueda
├── sitemap.xml         # Mapa del sitio para SEO
├── css/
│   └── style.css       # Hoja de estilos completa
├── js/
│   └── app.js          # JavaScript con traducciones y animaciones
└── images/
    ├── miguel.jpg      # Foto de perfil de Mike Mejía
    └── codex-logo-web.png  # Logo del creador (Codex Studio)
```

---

## 🛠 Stack Tecnológico

<div align="center">

<!-- TECHNOLOGIES -->
<a href="https://www.google.com/search?q=HTML5+que+es" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=html" title="HTML5 - Estructura Semántica" />
</a>
<a href="https://www.google.com/search?q=CSS3+que+es" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=css" title="CSS3 - Estilizado y Animaciones" />
</a>
<a href="https://www.google.com/search?q=JavaScript+que+es" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=js" title="JavaScript ES6+ - Lógica de Negocio" />
</a>
<br>

<!-- TOOLS -->
<a href="https://www.google.com/search?q=Git+que+es" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=git" title="Git - Control de Versiones" />
</a>
<a href="https://www.google.com/search?q=GitHub+que+es" target="_blank" style="cursor: pointer;">
  <img src="https://skillicons.dev/icons?i=github" title="GitHub - Alojamiento del Repositorio" />
</a>

</div>

### Tecnologías Base

| Tecnología | Uso |
|------------|-----|
| **HTML5** | Estructura semántica de la página. Un solo archivo `index.html` |
| **CSS3** | Un solo archivo `style.css` con variables CSS, animaciones keyframe, flexbox, grid, media queries, pseudoelementos, backdrop-filter, transiciones y gradientes |
| **JavaScript (Vanilla ES6+)** | Un solo archivo `app.js` con sistema i18n, IntersectionObserver, contadores animados, partículas canvas, dropdown de idiomas, formulario y typewriter |

### Librerías Externas (CDN)

| Librería | Versión | Uso |
|----------|---------|-----|
| **Font Awesome Free** | 6.5.1 | Iconos vectoriales |
| **Flag Icons** | 7.0.0 | Banderas de países para selector de idiomas |
| **Devicons** | Última | Logos de tecnologías |
| **Google Fonts** | Última | Fuentes Inter y JetBrains Mono |

### Lo que NO se usó

- **No se usó Tailwind CSS** — Todo el CSS es propio
- **No se usó TypeScript** — JavaScript Vanilla puro
- **No se usó React, Vue, Angular ni ningún framework**
- **No se usó Node.js, npm, webpack ni bundlers**
- **No se usó base de datos ni backend**

---

## ✨ Funcionalidades Implementadas

### Navegación
- Barra de navegación fija con 5 enlaces internos
- Transparente al inicio de la página
- Al hacer scroll, se vuelve oscura con blur y borde teal

### Selector de Idiomas Bilingüe (ES/EN)
- Dropdown personalizado con banderas de Colombia y Estados Unidos
- Sistema i18n completo
- Persistencia en localStorage
- Traducciones para: navegación, hero, stats, about, stack, proyectos, experiencia, contacto, footer y disclaimer

### Hero Section
- Fondo oscuro con gradiente de 3 tonos
- Partículas animadas con Canvas API
- Blobs decorativos
- Shape divider con wave SVG
- Foto de perfil circular con borde teal y glow
- Nombre "Mejía" con tilde y gradiente animado

### Stats
- 4 tarjetas con contadores animados al hacer scroll
- Iconos SVG circulares con fondo de color sólido
- Números con easing cúbico

### About
- Texto descriptivo en 3 párrafos
- Bloque de código con efecto typewriter
- Cursor parpadeante

### Stack (Tecnologías)
- 4 categorías con iconos SVG personalizados
- Chips de tecnología con logos Devicons
- Efecto hover: giro 360° + elevación + sombra + borde teal

### Proyectos
- 3 tarjetas con fondos de color
- Efecto shimmer (reflejo) al pasar el cursor
- Viñetas para tecnologías usadas
- Insignia "Proyecto destacado"

### Experiencia (Timeline)
- Línea de tiempo vertical con gradiente de 3 colores
- Puntos de colores en cada entrada
- Tarjetas con período, cargo y descripción

### Contacto
- Formulario centrado sin efecto hover
- Campos: nombre, email, asunto, mensaje
- Botón con animación de carga y confirmación

### Footer
- 3 columnas: Email, Ubicación, Modalidad
- Redes sociales con enlaces reales y deshabilitados
- Logo de Codex Studio
- Disclaimer bilingüe sobre derechos de autor

---

## 🔍 SEO Implementado

| Elemento | Estado |
|----------|--------|
| `<title>` | Mike Mejía \| Data Engineer & Data Analyst |
| `<meta name="description">` | Descripción de 160 caracteres |
| `<meta name="keywords">` | Palabras clave relevantes |
| `<meta name="author">` | Mike Mejía |
| `<meta name="robots">` | index, follow |
| `<link rel="canonical">` | URL canónica |
| `<link rel="alternate" hreflang="es">` | Versión en español |
| `<link rel="alternate" hreflang="en">` | Versión en inglés |
| Open Graph (`og:title`, `og:description`, `og:image`, `og:url`, `og:locale`) | Completo |
| Twitter Card (`twitter:card`, `twitter:title`, `twitter:description`) | Completo |
| Schema.org JSON-LD (Person) | Datos estructurados |
| `robots.txt` | Permitir todo, apuntar a sitemap |
| `sitemap.xml` | URL principal con alternates hreflang |

---

## 🔒 Seguridad

### Estado Actual
- **No hay certificado SSL implementado**. GitHub Pages ofrece HTTPS gratis, pero debe activarse.
- **Actualmente la página usa HTTP** (no seguro).

### Riesgos de Seguridad
- **Formulario de contacto**: No envía datos a ningún servidor. Es solo simulación visual.
- **CDN externos**: Librerías cargadas desde CDN públicos. Se recomienda usar SRI.
- **Enlaces externos**: Tienen `target="_blank"` y `rel="noopener"`.

### Mejoras de Seguridad Pendientes
- Activar HTTPS en GitHub Pages
- Agregar SRI a los CDN
- Implementar backend real para el formulario
- Agregar Content Security Policy (CSP)

---

## 📊 Rendimiento

### Puntos Fuertes
- **Una sola solicitud CSS y una JS**
- **Sin frameworks pesados**
- **Solo 2 familias de fuentes**

### Puntos a Mejorar
- **Imágenes no optimizadas**: Convertir a WebP y redimensionar
- **Sin lazy loading**: Agregar a imágenes Devicons
- **Sin compresión**: GitHub Pages lo maneja automáticamente

---

## 📦 Dependencias

| Dependencia | URL | Propósito |
|-------------|-----|-----------|
| Font Awesome 6.5.1 | `cdnjs.cloudflare.com` | Iconos |
| Flag Icons 7.0.0 | `cdn.jsdelivr.net` | Banderas de países |
| Google Fonts (Inter) | `fonts.googleapis.com` | Tipografía principal |
| Google Fonts (JetBrains Mono) | `fonts.googleapis.com` | Tipografía mono |
| Devicons (Múltiples) | `cdn.jsdelivr.net/gh/devicons` | Logos de tecnologías |

---

## 🚀 Despliegue

### Ejecución Local

```bash
# Navegar al directorio del proyecto
cd /ruta/portafolio-miguel

# Abrir en navegador
start index.html      # Windows
open index.html       # macOS
xdg-open index.html   # Linux
```

### Despliegue en Hosting

**Opción 1: GitHub Pages (Gratis)**
```bash
# Crear repositorio: MikeMejia-Data-Dev.github.io
git init
git add .
git commit -m "Deploy landing page"
git remote add origin https://github.com/MikeMejia-Data-Dev/MikeMejia-Data-Dev.github.io.git
git push -u origin main
# Habilitar GitHub Pages en Settings > Pages
# Activar HTTPS en Settings > Pages > Enforce HTTPS
```

**Opción 2: Dominio Personalizado (Opcional)**
- Comprar `mikemejia.dev` (~$12/año)
- Configurar DNS apuntando a GitHub Pages
- Agregar archivo `CNAME` en la raíz

**Opción 3: Cloudflare (Gratis, Recomendado)**
- Agregar dominio a Cloudflare para CDN, SSL gratis, analíticas y protección DDoS

---

## 📋 Tareas Pendientes

| Tarea | Prioridad | Descripción |
|-------|-----------|-------------|
| **Activar HTTPS** | **Crítica** | En GitHub Pages Settings > Enforce HTTPS |
| **Comprar dominio** | Alta | Registrar `mikemejia.dev` y configurar DNS |
| **Optimizar imágenes** | Alta | Convertir `miguel.jpg` a WebP, redimensionar a 320×320 |
| **Subir a GitHub** | Alta | Crear repositorio y activar GitHub Pages |
| **Configurar Cloudflare** | Media | Agregar CDN, SSL, analíticas y protección DDoS |
| **Google Analytics** | Media | Agregar tag de medición |
| **Google Search Console** | Media | Verificar propiedad y enviar sitemap |
| **Formulario funcional** | Baja | Implementar backend para recibir mensajes |
| **SRI** | Baja | Agregar hashes de integridad a CDN |
| **Content Security Policy** | Baja | Agregar header CSP |
| **PWA** | Opcional | Agregar manifest.json y service worker |

---

## 📄 Licencia y Créditos

Este sitio es una landing page de práctica desarrollada por **Sebastián Corona** para mostrar el perfil profesional de **Mike Mejía**.

Todos los derechos de autor pertenecen a **Mike Mejía** y **Sebastián Corona**.

> ℹ️ **Aviso**: Si Mike Mejía prefiere no aparecer en este sitio web, el contenido será retirado de inmediato con total respeto.

---

## 📬 Contacto

**Desarrollador:** Sebastián Corona  
📍 Valencia, Carabobo, Venezuela  
✉️ sebastiancorona@codexstudiove.com  
🌐 [www.codexstudiove.com](https://www.codexstudiove.com)  

**Propietario del Perfil:** Mike Mejía  
🔗 [github.com/MikeMejia-Data-Dev](https://github.com/MikeMejia-Data-Dev)

---

<div align="center">

**⭐ If you like this project, give it a star on GitHub!** 💜  
**⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!** 💜

</div>

---

**Released with 💜 by Sebastián Corona**  
*Crafting professional digital experiences with precision and care.*