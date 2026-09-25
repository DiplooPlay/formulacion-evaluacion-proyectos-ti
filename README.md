# Uni 2

Proyecto base para blog y documentación, basado en Astro + Tailwind CSS v4.

## Scripts disponibles

- `pnpm dev`: Inicia el servidor de desarrollo local.
- `pnpm build`: Compila el proyecto para producción en la carpeta `dist/`.
- `pnpm preview`: Previsualiza la compilación localmente.

## Estructura del proyecto

```text
uni-2/
├── public/          # Archivos estáticos públicos
├── src/
│   ├── assets/      # Recursos e imágenes
│   ├── components/  # Componentes reutilizables de Astro/UI
│   ├── layouts/     # Plantillas y layouts principales
│   ├── pages/       # Páginas y rutas del blog
│   └── styles/      # Estilos globales (Tailwind CSS)
├── astro.config.mjs # Configuración de Astro
├── package.json     # Dependencias y scripts
└── tsconfig.json    # Configuración de TypeScript
```
