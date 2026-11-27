# CSS Esencial

Manual práctico para aprender los fundamentos de CSS desde cero. El sitio está creado con [Astro](https://astro.build/) y combina explicaciones, ejemplos y actividades para practicar.

## Contenido

1. Primeros pasos con CSS.
2. Selectores básicos.
3. Cascada, especificidad y herencia.
4. Colores, fondos y texto.
5. Modelo de caja esencial.
6. Visualización de elementos.
7. Flexbox esencial.
8. CSS Grid esencial.
9. Diseño responsive esencial.
10. Proyecto práctico de integración.

Las lecciones incluyen objetivos, ejemplos de HTML y CSS, infografías, prácticas y preguntas de repaso. El último tema propone crear una página web aplicando lo aprendido.

## Requisitos

- Node.js compatible con Astro 5 y npm.

## Instalación y desarrollo

Desde la carpeta del proyecto:

```powershell
npm install
npm run dev
```

Abre la dirección que aparece en la terminal, normalmente [http://localhost:4321/](http://localhost:4321/). Para detener el servidor, pulsa **Ctrl + C** en esa terminal.

Si el puerto está ocupado, puedes indicar otro:

```powershell
npm run dev -- --port 4322
```

## Generar el sitio

```powershell
npm run build
```

El sitio estático generado se guarda en la carpeta `dist`.

## Estructura

```text
cssesencial/
├── public/images/       Imágenes e infografías
├── src/
│   ├── components/      Componentes compartidos de las lecciones
│   ├── data/            Índice de temas
│   ├── layouts/         Estructura común de las páginas
│   ├── pages/           Portada y páginas de los temas
│   └── styles/          Estilos generales
├── astro.config.mjs     Configuración de Astro
└── package.json         Dependencias y comandos
```

## Para ampliar conocimientos

Consulta el [manual completo de CSS](https://resumencss.vercel.app/).
