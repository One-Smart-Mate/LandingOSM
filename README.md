# 🏭 OSM - One Smart Mate Landing Page

Landing page profesional para el software de mantenimiento autónomo industrial OSM (One Smart Mate), especializado en metodologías TPM, CILT y OPL.

## ✨ Características

- **Diseño Moderno**: Landing page responsive con animaciones de scroll reveal
- **Metodología TPM**: Sección educativa sobre los 8 pilares del TPM
- **Tecnología Avanzada**: Tailwind CSS con variables personalizadas
- **Animaciones Suaves**: Efectos de aparición con Intersection Observer API
- **Optimizado**: Performance optimizada sin afectar la experiencia de usuario

## 🚀 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **Tailwind CSS v4** - Framework CSS con variables `@theme`
- **JavaScript ES6+** - Funcionalidades interactivas
- **Inter Font** - Tipografía moderna y legible
- **SVG Icons** - Iconografía vectorial escalable

## 📁 Estructura del Proyecto

```
.landingOSM/
├── index.html              # Página principal
├── src/
│   ├── input.css           # Estilos Tailwind con variables personalizadas
│   └── output.css          # CSS compilado (generado automáticamente)
├── fonts/
│   └── inter/              # Fuente Inter (variable font)
├── img/                    # Imágenes SVG de undraw.co
├── ejemplos/               # Ejemplos de landing pages de referencia
├── AntiguaLanding/         # Landing page anterior
├── .gitignore              # Archivos excluidos de Git
└── README.md               # Este archivo
```

## 🛠️ Instalación y Desarrollo

### Prerrequisitos
- Node.js (versión 14 o superior)
- npm o yarn

### Instalación
```bash
# Clonar el repositorio
git clone <tu-repositorio>
cd .landingOSM

# Instalar dependencias
npm install

# Compilar CSS (desarrollo)
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

# Compilar CSS (producción)
npx tailwindcss -i ./src/input.css -o ./src/output.css --minify
```

### Desarrollo Local
```bash
# Iniciar servidor de desarrollo (opcional)
npx serve .

# O simplemente abrir index.html en el navegador
```

## 🎨 Personalización

### Colores Principales
Los colores están definidos en `src/input.css` usando variables CSS:

```css
--color-primary: #4C5B91;
--color-primary-dark: #001E40;
--color-white: #ffffff;
```

### Fuentes
- **Inter Variable Font**: Fuente principal con soporte completo para acentos
- Configurada para pesos de 100 a 900

### Animaciones
- **Scroll Reveal**: Aparición suave de secciones al hacer scroll
- **Staggered Animations**: Efectos escalonados para elementos múltiples
- **Hover Effects**: Interacciones sutiles en botones y tarjetas

## 📱 Secciones de la Landing

1. **Hero Section** - Introducción impactante
2. **Stats** - Métricas clave de la industria
3. **Features** - 4 pasos principales del proceso
4. **AM (Mantenimiento Autónomo)** - Metodología TPM
5. **CILT** - Cleaning, Inspection, Lubrication, Tightening
6. **OPL** - One Point Lessons
7. **Benefits** - Transformación industrial
8. **Technology** - Capacidades técnicas reales
9. **TPM Methodology** - Los 8 pilares del TPM
10. **Contact** - Información de contacto

## 🔧 Configuración de Producción

### Optimización
```bash
# Compilar CSS optimizado para producción
npx tailwindcss -i ./src/input.css -o ./src/output.css --minify

# Verificar tamaño del bundle
ls -la src/output.css
```

### Despliegue
La landing page es estática y puede desplegarse en:
- GitHub Pages
- Netlify
- Vercel
- Cualquier servidor web estático

## 📊 Performance

- **Lighthouse Score**: Optimizado para rendimiento
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

## 📞 Contacto

**One Smart Mate** - Tu compañero inteligente para el mantenimiento autónomo industrial.

- **Email**: [tu-email@ejemplo.com]
- **WhatsApp**: [tu-número]
- **Sitio Web**: [tu-sitio-web]

---

Desarrollado con ❤️ para revolucionar el mantenimiento industrial.
