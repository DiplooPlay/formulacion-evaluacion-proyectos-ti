# Formulación y Evaluación de Proyectos TI

Diagnóstico de Brechas (Gap Analysis) y Plan de Adecuación de Infraestructura y Controles Críticos bajo ISO/IEC 27001:2022 para **Coval Servicios Financieros (Sede Perú)**.

Proyecto académico desarrollado con **Astro v7** y **Tailwind CSS v4** bajo estándares del **PMBOK**.

## Scripts disponibles

- `pnpm dev`: Inicia el servidor de desarrollo local.
- `pnpm build`: Compila el proyecto para producción en la carpeta `dist/`.
- `pnpm preview`: Previsualiza la compilación localmente.

## Estructura del proyecto

```text
uni-2/
├── public/          # Archivos estáticos públicos y favicon
├── src/
│   ├── assets/      # Recursos e imágenes
│   ├── components/  # Componentes reutilizables (Matriz, Tabla de Stakeholders, etc.)
│   ├── layouts/     # Plantillas y layout principal con barra de lectura
│   ├── pages/       # Contenido principal y secciones del proyecto
│   └── styles/      # Estilos globales (Tailwind CSS v4)
├── astro.config.mjs # Configuración de Astro
├── package.json     # Dependencias y scripts
└── tsconfig.json    # Configuración de TypeScript
```
