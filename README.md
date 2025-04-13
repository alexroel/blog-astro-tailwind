# Blog con Astro y TailwindCSS


## 🚀 Creación del Proyecto

El proyecto fue creado utilizando Astro con el template de blog y TailwindCSS. A continuación, se detallan los pasos seguidos:

1. **Inicialización del proyecto**  
   Ejecuta el siguiente comando para crear un nuevo proyecto con Astro utilizando el template de blog:
    ```sh
    npm create astro@latest
    ```

2. **Configuración inicial**  
   Durante la configuración, se seleccionaron las siguientes opciones:
   - Directorio del proyecto: `./astro-blog-tailwind`
   - Template: Blog
   - Instalar dependencias: Sí
   - Inicializar un repositorio Git: Sí

3. **Inicio del servidor de desarrollo**  
   Una vez creado el proyecto, navega al directorio del proyecto y ejecuta el servidor de desarrollo:
   ```sh
   cd ./astro-blog-tailwind
   npm run dev
   ```

   Esto iniciará el servidor en `http://localhost:4321/`.

   Sigue las instrucciones proporcionadas por Astro para completar la configuración.

### 🚀 Estructura del Proyecto

Dentro de tu proyecto de Astro, verás las siguientes carpetas y archivos:

```text
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada archivo se expone como una ruta basada en su nombre.

No hay nada especial sobre `src/components/`, pero ahí es donde solemos colocar componentes de Astro/React/Vue/Svelte/Preact.

El directorio `src/content/` contiene "colecciones" de documentos relacionados en Markdown y MDX. Usa `getCollection()` para recuperar publicaciones de `src/content/blog/` y verifica el frontmatter usando un esquema opcional. Consulta la [documentación de colecciones de contenido de Astro](https://docs.astro.build/en/guides/content-collections/) para aprender más.

Cualquier recurso estático, como imágenes, puede colocarse en el directorio `public/`.

### 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, en una terminal:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                         |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321` |
| `npm run build`           | Construye tu sitio de producción en `./dist/`    |
| `npm run preview`         | Previsualiza tu sitio construido localmente antes de desplegarlo |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtén ayuda sobre el CLI de Astro                |

---
## Instalar TailwindCSS


