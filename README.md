# Plantilla de Astro con Tailwind css

## 🚀 Estructura del proyecto

Dentro de su proyecto Astro, verá las siguientes carpetas y archivos:

```text
/
├── public/
├── src/
│   └── components/
|       └── layout/
|       └── ui/
|       └── views/
│   └── layouts/
│   └── utils/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se expone como una ruta según su nombre de archivo.

No hay nada especial en `src/components/`, pero ahí es donde nos gusta colocar los componentes Astro/React/Vue/Svelte/Preact.

Cualquier activo estático, como imágenes, se puede colocar en el directorio `public/`.
