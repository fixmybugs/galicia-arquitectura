# GALICIA ARQUITECTURA

Portafolio web moderno de arquitectura construido con Astro y TailwindCSS.

## 🚀 Despliegue en Vercel

### Requisitos Previos
- Cuenta en [GitHub](https://github.com)
- Cuenta en [Vercel](https://vercel.com)
- Repositorio del proyecto en GitHub

### Pasos para Desplegar

1. **Subir a GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/tu-usuario/galicia-arquitectura.git
   git push -u origin main
   ```

2. **Conectar con Vercel**
   - Ve a [vercel.com](https://vercel.com)
   - Inicia sesión con GitHub
   - Click en "New Project"
   - Selecciona tu repositorio `galicia-arquitectura`

3. **Configuración del Proyecto**
   - **Framework Preset**: Astro (detectado automáticamente)
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
   - **Install Command**: `npm install`

4. **Desplegar**
   - Click en "Deploy"
   - Espera el proceso de build
   - ¡Listo! Tu sitio estará en producción

### Variables de Entorno (Opcional)
Si necesitas variables de entorno:
- En Vercel Dashboard → Project Settings → Environment Variables
- Agrega las variables necesarias (ej: API keys, URLs de servicios)

## 🛠️ Desarrollo Local

```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Previsualizar producción local
npm run preview
```

## 📁 Estructura del Proyecto

```
src/
├── components/          # Componentes Astro
│   ├── Navbar.astro
│   ├── HeroModern.astro
│   ├── ParallaxSection.astro
│   ├── ServicesModern.astro
│   ├── ProjectsModern.astro
│   ├── ContactModern.astro
│   ├── FooterModern.astro
│   └── LoaderModern.astro
├── layouts/            # Layouts
│   └── Layout.astro
├── pages/              # Páginas
│   ├── index.astro     # Página principal
│   ├── proyectos.astro # Galería de proyectos
│   ├── acerca.astro    # Acerca de nosotros
│   └── contacto.astro  # Contacto y FAQs
└── styles/             # Estilos
    └── global.css

public/                 # Archivos estáticos
├── parallax.webp
└── favicon.svg

astro.config.mjs        # Configuración de Astro
tailwind.config.mjs     # Configuración de TailwindCSS
vercel.json            # Configuración de Vercel
package.json           # Dependencias y scripts
```

## 🎨 Características

- ✅ **Diseño Responsive**: Mobile-first con breakpoints optimizados
- ✅ **Loader Animado**: Solo en página principal con animación de texto
- ✅ **Efecto Parallax**: Optimizado para desktop, deshabilitado en móvil
- ✅ **Menú Móvil**: Animaciones suaves y stagger effects
- ✅ **SEO Optimizado**: Meta tags y estructura semántica
- ✅ **Performance**: Imágenes optimizadas y cache configurado
- ✅ **Localización**: Contenido adaptado para Guatemala

## 🌐 Tecnologías

- **Astro 5.15.1**: Framework de sitios estáticos
- **TailwindCSS 3.4.18**: Utilidades de CSS
- **Google Material Icons**: Iconos modernos
- **IBM Plex Sans**: Tipografía principal

## 📄 Licencia

© 2025 GALICIA ARQUITECTURA - Todos los derechos reservados
