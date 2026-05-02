# 💒 Sitio Web de Boda - Orlando & Daniela

Invitación digital interactiva para la celebración de nuestra boda. Desarrollada con [Astro](https://astro.build) y [Tailwind CSS](https://tailwindcss.com), esta web ofrece una experiencia elegante, rápida y totalmente adaptada a móviles y escritorio.

## ✨ Características
- 📱 **Diseño Responsive** - Optimizado para todos los dispositivos y tamaños de pantalla
- ⏳ **Cuenta Regresiva** - Timer en tiempo real con calendario visual hasta el día del evento
- 🖼️ **Galería Interactiva** - Lightbox con navegación por teclado y efectos de hover
- 🎵 **Reproductor de Audio** - Música ambiental personalizada con controles de volumen y tiempo
- 🎁 **Lluvia de Sobres** - Información de regalos con QR para transferencias bancarias
- 📥 **Plantillas Descargables** - Marcos exclusivos para fotos de invitados con QR integrados
- 🚀 **Rendimiento Óptimo** - Imágenes WebP optimizadas automáticamente por Astro
- 🔍 **SEO Integrado** - Meta tags, Open Graph y Twitter Cards preconfigurados

## 🛠️ Tech Stack
- [Astro 5](https://astro.build) - Framework web centrado en contenido
- [Tailwind CSS 4](https://tailwindcss.com) - Estilos utility-first con Vite
- [Lucide Icons](https://lucide.dev) - Iconografía moderna y ligera

## 🚀 Guía de Desarrollo

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Iniciar servidor de desarrollo:**
   ```bash
   npm run dev
   ```
   Abre `http://localhost:4321` en tu navegador.

3. **Generar build para producción:**
   ```bash
   npm run build
   ```
   Los archivos estáticos optimizados se generarán en la carpeta `dist/`.

## 📁 Estructura del Proyecto
```
/
├── public/
│   ├── plantillas/          # Marcos descargables para invitados
│   └── images/              # Assets estáticos (logo, favicon)
├── src/
│   ├── assets/              # Imágenes, audios y fuentes procesadas
│   ├── components/          # Componentes modulares (Hero, Contador, Galería, etc.)
│   ├── layout/              # Layout principal y navegación
│   ├── pages/               # Rutas y página de entrada
│   └── styles/              # CSS global, animaciones y tema Tailwind
├── astro.config.mjs
├── netlify.toml             # Configuración de despliegue
└── package.json
```

## 🌐 Despliegue
Este proyecto está listo para plataformas de hosting estático.

- **Netlify:** Configurado mediante `netlify.toml`. Solo conecta el repositorio en [app.netlify.com](https://app.netlify.com) o arrastra la carpeta `dist/` a [Netlify Drop](https://app.netlify.com/drop).
- **Vercel / GitHub Pages:** Compatible sin configuración adicional.

## 🎨 Personalización
- **Colores y Tipografía:** Modifica `@theme` en `src/styles/global.css`
- **Fecha del Evento:** Ajusta la fecha en `src/components/Contador.astro`
- **Música Ambiental:** Reemplaza el archivo en `src/assets/audio/`
- **Imágenes de Fondo:** Actualiza las referencias en `Hero.astro` y `SplashScreen.astro`

## 📝 Licencia
Uso personal y privado para la celebración de bodas.
