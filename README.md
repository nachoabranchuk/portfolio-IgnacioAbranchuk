# Portfolio - Ignacio Abranchuk

Portfolio personal de Ignacio Abranchuk, desarrollador web y estudiante de Ingeniería en Sistemas en la UAI (Rosario).

**Sitio online:** https://portfolio-ignacio-abranchuk.vercel.app/

## Secciones

- **Inicio:** presentación, rol y botones de acción.
- **Sobre mí:** biografía y habilidades agrupadas por categoría.
- **Proyectos:** Futbolle, Camiones App (frontend) y Camiones App (backend).
- **Contacto:** email, GitHub y LinkedIn.

## Stack

- [Astro](https://astro.build/): generación de sitio estático y componentes.
- [Tailwind CSS](https://tailwindcss.com/) v4: estilos y diseño responsive.
- HTML semántico y accesibilidad básica (alt en imágenes, foco visible, contraste legible).
- Deploy en [Vercel](https://vercel.com/).

## Cómo correrlo localmente

Requisitos: Node.js 20 o superior y npm.

```bash
git clone https://github.com/nachoabranchuk/portfolio-IgnacioAbranchuk.git
cd portfolio-IgnacioAbranchuk
npm install
npm run dev
```

El sitio queda disponible en `http://localhost:4321`.

## Comandos

| Comando           | Acción                                     |
| :---------------- | :----------------------------------------- |
| `npm run dev`     | Inicia el servidor de desarrollo           |
| `npm run build`   | Genera el sitio final en la carpeta `dist` |
| `npm run preview` | Previsualiza el build localmente           |

## Estructura

```
src/
├── assets/       # Imágenes que Astro optimiza
├── components/   # Navbar, Hero, About, Projects, Contact, Footer
├── layouts/      # Layout base
├── pages/        # index.astro
└── styles/       # CSS global con Tailwind
```

## Opcionales implementados

- Modo oscuro y claro (respeta la preferencia del sistema y recuerda la elección).
- Animaciones sutiles que respetan `prefers-reduced-motion`.
- Lighthouse 100 en Performance, Accessibility, Best Practices y SEO.