# 🔮 GLAMOUR MAGICK: El Arte de la Fascinación

Landing page de alto impacto para el taller online **GLAMOUR MAGICK: El Arte de la Fascinación y Presencia**. Un espacio donde la estética tecnológica se encuentra con la praxis esotérica moderna.

## 🛠️ Stack Tecnológico

- **Framework:** [Astro 6.1.8](https://astro.build/) (Optimizado para performance)
- **Estilos:** [Tailwind CSS v4](https://tailwindcss.com/) (Plugin de Vite para máxima velocidad)
- **Animaciones:** [GSAP 3](https://gsap.com/) + ScrollTrigger (Interacciones fluidas y orgánicas)
- **Iconos:** [Lucide React](https://lucide.dev/)
- **Tipografías:** Google Fonts (Instrument Serif, Sora, Fira Code)

## 🎨 Concepto Visual: "Tech-Occult"

El proyecto sigue una estética **Cyberpunk Oscura / Vapor Clinic**, caracterizada por:
- Fondo negro puro (`#000000`) con texturas de ruido digital.
- Acentos en Púrpura Plasma (`#7B61FF`) y Cyan Neón (`#00F0FF`).
- Tipografía dramática con contrastes de escala.
- Micro-interacciones magnéticas y efectos de "vidrio" (glassmorphism).

## 📂 Estructura del Proyecto

```text
/
├── public/              # Assets estáticos (Hero images, favicon)
├── src/
│   ├── layouts/         # Layout.astro (Base con SEO y Scripts)
│   ├── components/      # Componentes React/Astro reutilizables
│   ├── pages/
│   │   ├── index.astro  # Landing Page principal
│   │   ├── terms.astro  # Términos de Servicio
│   │   └── privacy.astro# Política de Privacidad
│   └── styles/
│       └── global.css   # Sistema de diseño y variables Tailwind v4
└── astro.config.mjs     # Configuración de integraciones
```

## 🚀 Comandos Rápidos

| Comando | Acción |
| :--- | :--- |
| `pnpm install` | Instala las dependencias del protocolo. |
| `pnpm dev` | Inicia el servidor de desarrollo en `localhost:4321`. |
| `pnpm build` | Compila el artefacto para producción en `./dist/`. |
| `pnpm preview` | Previsualiza la build de producción localmente. |

## 🌐 Despliegue

Optimizado para despliegue automático en **Vercel** o **Netlify**. Cada commit en la rama `main` dispara una nueva construcción astral del sitio.

---

**© 2026 GLAMOUR MAGICK** - *El conocimiento es un virus. Al leer esto, ya fuiste infectado.*
