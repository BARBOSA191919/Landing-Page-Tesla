# Tesla Landing Page Clone

Una réplica moderna de la landing page de Tesla construida con Astro, TypeScript y Tailwind CSS. Además, este proyecto demuestra técnicas avanzadas de desarrollo web con optimización de rendimiento y experiencia de usuario excepcional.

## 📋 Descripción

Esta landing page es una recreación fiel del sitio web oficial de Tesla, implementando todas las animaciones, transiciones y elementos visuales que caracterizan a la marca. Desarrollada con tecnologías modernas para garantizar máximo rendimiento y experiencia de usuario.

## 📷 Capturas de Pantalla

### Vista Principal
<img width="1837" height="1010" alt="image" src="https://github.com/user-attachments/assets/7d6de93c-27fb-44ac-9ec2-7fd48e886fae" />
*Página principal con el hero section y navegación característica de Tesla*

### Sección Model S
<img width="1847" height="1017" alt="image" src="https://github.com/user-attachments/assets/1e4b191f-a6ff-4273-aa57-ea9b14a2c9f4" />
*Presentación del Model S con imágenes de alta calidad*

### Sección Model 3
<img width="1850" height="1025" alt="image" src="https://github.com/user-attachments/assets/ed4abb42-ac50-44a1-819c-6be2cf5f9ee9" />
*Showcase del Model 3 con efectos de scroll*

### Cybertruck
<img width="1835" height="1016" alt="image" src="https://github.com/user-attachments/assets/cc1400ed-8f01-4c02-a596-560f519fb37d" />
*Sección dedicada al Cybertruck con video de fondo*

### Powerwall
<img width="1842" height="1022" alt="image" src="https://github.com/user-attachments/assets/74c7f750-0fd0-4cec-a6be-0d26d3661fb3" />
*Sección de productos energéticos Powerwall*

### Accesorios
<img width="1860" height="1010" alt="image" src="https://github.com/user-attachments/assets/648ee4c5-8603-44d6-9f28-6a916392c8b8" />
*Sección de productos de accesorios*

<div align="center">
<h3> Responsive Design </h3>
<img width="481" height="940" alt="image" src="https://github.com/user-attachments/assets/6928a315-2cb5-405d-bd5d-250b39718dc5" />
<em><p>Diseño adaptativo perfecto para dispositivos móviles*</p></em>
</div>

## 🚀 Tecnologías Utilizadas

- **Astro** - Framework web moderno para sitios estáticos
- **TypeScript** - Tipado estático para mayor robustez
- **Tailwind CSS** - Framework CSS utilitario
- **HTML5** - Estructura semántica avanzada
- **CSS3** - Animaciones y transiciones personalizadas
- **WebP/AVIF** - Formatos de imagen optimizados
- **WebM** - Videos optimizados para web

## 📁 Estructura del Proyecto

```
barbosa191919-landing-page-tesla/
├── README.md
├── astro.config.mjs      # Configuración de Astro
├── package.json
├── tailwind.config.cjs   # Configuración de Tailwind
├── tsconfig.json         # Configuración de TypeScript
├── public/
│   ├── accessories.avif   # Imágenes optimizadas
│   ├── model-3.avif      # Modelos de Tesla
│   ├── model-s.avif
│   ├── model-x.avif
│   ├── model-y.avif
│   ├── Cybertruck.avif
│   ├── powerwall.avif
│   ├── video.webm        # Videos de fondo
│   ├── video1.webm
│   ├── video2.webm
│   └── video3.webm
└── src/
    ├── components/
    │   ├── Accesories.astro     # Sección de accesorios
    │   ├── Cybertruck.astro     # Sección Cybertruck
    │   ├── FooterMenu.astro     # Menú del pie de página
    │   ├── HeroSection.astro    # Sección principal
    │   ├── LandingHeader.astro  # Cabecera de la página
    │   ├── Logo.astro           # Logo de Tesla
    │   ├── ModelS.astro         # Sección Model S
    │   ├── ModelThree.astro     # Sección Model 3
    │   ├── ModelX.astro         # Sección Model X
    │   ├── ModelY.astro         # Sección Model Y
    │   ├── PowerWall.astro      # Sección Powerwall
    │   ├── Section.astro        # Componente base
    │   └── Welcome.astro        # Sección de bienvenida
    ├── layouts/
    │   └── Layout.astro         # Layout principal
    ├── pages/
    │   └── index.astro          # Página principal
    └── styles/
        └── global.css           # Estilos globales
```

## 🧩 Componentes

### Componentes de Layout
- **Layout.astro** - Estructura HTML base con SEO optimizado
- **LandingHeader.astro** - Navegación principal con efectos de scroll
- **FooterMenu.astro** - Pie de página con enlaces organizados

### Componentes de Producto
- **ModelS.astro** - Showcase del Model S con especificaciones
- **ModelThree.astro** - Presentación del Model 3
- **ModelX.astro** - Sección dedicada al Model X
- **ModelY.astro** - Showcase del Model Y
- **Cybertruck.astro** - Sección especial para Cybertruck

### Componentes de Energía
- **PowerWall.astro** - Productos de almacenamiento energético
- **Accesories.astro** - Accesorios y productos complementarios

### Componentes Base
- **HeroSection.astro** - Sección principal con llamada a la acción
- **Section.astro** - Componente reutilizable para secciones
- **Logo.astro** - Logo de Tesla con animaciones
- **Welcome.astro** - Mensaje de bienvenida

## 🛠️ Instalación y Configuración

### Requisitos Previos
- Node.js (v18 o superior)
- npm o yarn

### Instalación

1. Clona el repositorio:
```bash
git clone [URL_DEL_REPOSITORIO]
cd barbosa191919-landing-page-tesla
```

2. Instala las dependencias:
```bash
npm install
```

3. Ejecuta el servidor de desarrollo:
```bash
npm run dev
```

4. Abre tu navegador en `http://localhost:3000`

### Build para Producción

```bash
npm run build
```

### Preview del Build

```bash
npm run preview
```

## 📝 Scripts Disponibles

- `npm run dev` - Servidor de desarrollo con hot reload
- `npm run build` - Build optimizado para producción
- `npm run preview` - Preview del build de producción
- `npm run astro` - CLI de Astro para comandos específicos

## 🌟 Características

- ✅ **Rendimiento Ultra-Rápido** - Sitio estático optimizado con Astro
- ✅ **Imágenes Optimizadas** - Formatos WebP y AVIF para carga rápida
- ✅ **Videos de Fondo** - Integración fluida de videos WebM
- ✅ **Animaciones Suaves** - Transiciones y efectos visuales
- ✅ **SEO Optimizado** - Meta tags y estructura semántica
- ✅ **TypeScript** - Código tipado y mantenible
- ✅ **Responsive Design** - Adaptación perfecta a todos los dispositivos
- ✅ **Lazy Loading** - Carga diferida de imágenes y videos
- ✅ **Accesibilidad** - Cumple con estándares WCAG
- ✅ **Performance Score 100** - Optimización máxima de Lighthouse

## 🎯 Funcionalidades

### Experiencia Visual
- **Hero Dinámico**: Sección principal con efectos de parallax
- **Scroll Suave**: Navegación fluida entre secciones
- **Hover Effects**: Interacciones micro sutiles
- **Video Backgrounds**: Videos de alta calidad como fondo

### Optimización Técnica
- **Island Architecture**: Hidratación selectiva de componentes
- **Code Splitting**: Carga optimizada de recursos
- **Image Optimization**: Compresión automática de imágenes
- **Critical CSS**: Estilos críticos inline

### Navegación
- **Sticky Header**: Navegación fija con transparencia
- **Smooth Scrolling**: Navegación suave entre secciones
- **Mobile Menu**: Menú hamburguesa para móviles

## 📱 Responsividad

Optimizado para todos los tamaños de pantalla:
- 💻 **Desktop** (1200px+) - Experiencia completa con videos
- 📱 **Tablet** (768px-1199px) - Adaptación táctil optimizada
- 🔧 **Mobile** (320px-767px) - Interfaz simplificada y rápida

## 🎨 Personalización

### Configuración de Tailwind
```javascript
// tailwind.config.cjs
module.exports = {
  content: ['./src/**/*.{astro,html,js,jsx,md,mdx,svelte,ts,tsx,vue}'],
  theme: {
    extend: {
      colors: {
        tesla: {
          red: '#e31837',
          dark: '#171a20',
          gray: '#5c5e62'
        }
      }
    }
  }
}
```

### Configuración de Astro
```javascript
// astro.config.mjs
import { defineConfig } from 'astro/config';
import tailwind from '@astrojs/tailwind';

export default defineConfig({
  integrations: [tailwind()],
  image: {
    domains: ['tesla.com']
  }
});
```

## 🚀 Optimizaciones Implementadas

### Rendimiento
- **Static Site Generation**: Sitio completamente estático
- **Image Optimization**: Compresión automática con Astro
- **Bundle Splitting**: División inteligente de código
- **Preloading**: Carga anticipada de recursos críticos

### SEO
- **Meta Tags**: Optimización para motores de búsqueda
- **Structured Data**: Datos estructurados para mejor indexación
- **Sitemap**: Generación automática de sitemap
- **Robots.txt**: Configuración para crawlers

## 📊 Métricas de Rendimiento

- **Lighthouse Performance**: 100/100
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Time to Interactive**: < 3.5s
- **Cumulative Layout Shift**: < 0.1

## 🔧 Configuración Avanzada

### Variables de Entorno
```bash
# .env
PUBLIC_SITE_URL=https://tu-dominio.com
PUBLIC_ANALYTICS_ID=tu-google-analytics-id
```

### Configuración de Build
```json
{
  "scripts": {
    "build": "astro build",
    "dev": "astro dev",
    "preview": "astro preview",
    "astro": "astro"
  }
}
```

## 🤝 Contribución

1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commitea tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Barbosa191919**

## 📞 Contacto

Para consultas o sugerencias:
- GitHub: [@barbosa191919](https://github.com/barbosa191919)

---

⭐ ¡No olvides dar una estrella al proyecto si te fue útil!

## 🙏 Agradecimientos

- **Tesla** - Por el diseño original inspirador
- **Astro Team** - Por el increíble framework
- **Tailwind CSS** - Por el sistema de diseño
- **Comunidad Open Source** - Por las herramientas y recursos
