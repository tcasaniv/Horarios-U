# Horarios-U

Una web para mostrar los horarios desde una API en varias vistas distintas.

## ✨ Visualiza diferentes vistas de horarios

> 🔰 **Horarios por año**

> 🔰 **Horarios por aula**

> 🔰 **Horarios por docente**

> 🔰 **Horarios por curso**

## 🛠️ Tecnologías usadas

- Astro
- Node.js
- HTML
- JS
- CSS

![Imagen](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Estructura del proyecto

Dentro del proyecto hecho con Astro, se encuentran las siguiente carpetas y archivos:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se expone como una ruta basada en su nombre de archivo.

No hay nada especial en `src/components/`, pero es donde generalmente se coloca cualquier componente Astro/React/Vue/Svelte/Preact.

Cualquier activo estático, como imágenes, puede colocarse en el directorio `public/`.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde un terminal:

| Comando                   | Acción                                                       |
| :------------------------ | :----------------------------------------------------------- |
| `npm install`             | Instala las dependencias                                     |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321`.  |
| `npm run build`           | Construya su sitio de producción en `./dist/`.               |
| `npm run preview`         | Previsualice su compilación localmente, antes de desplegarla |
| `npm run astro ...`       | Ejecutar comandos CLI como `astro add`, `astro check`.       |
| `npm run astro -- --help` | Ayuda para utilizar Astro CLI                                |
