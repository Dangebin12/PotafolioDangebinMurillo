# Portafolio de Dangebin Murillo

Un portafolio web moderno y minimalista inspirado en diseños contemporáneos.

## 🚀 Características

- **Diseño Minimalista**: Interfaz limpia y elegante
- **Responsive**: Se adapta a todos los tamaños de pantalla
- **Animaciones Suaves**: Transiciones y efectos visuales fluidos
- **Navegación Intuitiva**: Fácil de usar y navegar
- **Optimizado**: Código limpio y bien estructurado

## 📁 Estructura del Proyecto

```
PotafolioDangebinMurillo/
│
├── index.html          # Página principal con proyectos
├── about.html          # Página sobre mí
├── styles.css          # Estilos globales
├── script.js           # JavaScript interactivo
└── README.md           # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con variables CSS, Grid y Flexbox
- **JavaScript**: Interactividad y animaciones

## 📝 Cómo Personalizar

### 1. Información Personal

Edita `index.html` y `about.html` para actualizar:

- Nombre y descripción
- Enlaces de redes sociales
- Email de contacto

```html
<!-- En index.html, línea ~22 -->
<h1 class="hero-title">
    Hola. Soy <span class="highlight">TuNombre.</span>
</h1>
```

### 2. Proyectos

En `index.html`, actualiza las secciones de proyectos:

```html
<!-- Proyectos Destacados, línea ~35 -->
<a href="#" class="project-card">
    <div class="project-tag">TU TAG</div>
    <h4 class="project-title">Título del Proyecto</h4>
    <p class="project-description">
        Descripción de tu proyecto
    </p>
</a>
```

### 3. Colores y Estilo

Modifica las variables CSS en `styles.css`:

```css
:root {
    --color-bg: #ffffff;
    --color-text: #1a1a1a;
    --color-accent: #0066ff;  /* Cambia este para el color principal */
    /* ... */
}
```

### 4. Habilidades y Experiencia

Edita `about.html` para actualizar:

- Habilidades en la sección `.skills-grid`
- Experiencia en la sección `.timeline`
- Educación

## 🌐 Cómo Ver el Portafolio

### Opción 1: Abrir directamente
Simplemente haz doble clic en `index.html` para abrirlo en tu navegador.

### Opción 2: Servidor local (recomendado)

Con Python:
```bash
# Python 3
python -m http.server 8000

# Luego visita: http://localhost:8000
```

Con VS Code:
- Instala la extensión "Live Server"
- Click derecho en `index.html` → "Open with Live Server"

Con Node.js:
```bash
npx serve
```

## 📤 Cómo Publicar

### GitHub Pages (Gratis)

1. Crea un repositorio en GitHub
2. Sube todos los archivos
3. Ve a Settings → Pages
4. Selecciona la rama `main` y carpeta `root`
5. Tu sitio estará en `https://tuusuario.github.io/nombrerepo`

### Netlify (Gratis)

1. Crea una cuenta en [Netlify](https://netlify.com)
2. Arrastra y suelta la carpeta del proyecto
3. ¡Listo! Tu sitio estará publicado

### Vercel (Gratis)

1. Crea una cuenta en [Vercel](https://vercel.com)
2. Conecta tu repositorio de GitHub
3. Deploy automático

## 🎨 Próximas Mejoras

- [ ] Agregar modo oscuro/claro
- [ ] Crear páginas individuales para cada proyecto
- [ ] Agregar un blog
- [ ] Integrar formulario de contacto funcional
- [ ] Agregar animaciones más complejas
- [ ] Optimizar imágenes y recursos

## 📧 Contacto

- **Email**: tu@email.com
- **GitHub**: [github.com/tuusuario](https://github.com/tuusuario)
- **LinkedIn**: [linkedin.com/in/tuusuario](https://linkedin.com/in/tuusuario)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usarlo y modificarlo.

---

**Hecho con ❤️ por Dangebin Murillo**
