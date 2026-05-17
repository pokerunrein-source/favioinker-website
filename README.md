# Favio Inker - DJ & Producer Website

Página web profesional para Favio Inker, DJ y productor especializado en Indie Dance.

## 📁 Archivos

- `index.html` - Estructura principal de la página
- `styles.css` - Estilos y diseño responsivo
- `script.js` - Funcionalidad interactiva
- `README.md` - Este archivo

## 🚀 Cómo usar

1. **Abrir la página localmente:**
   - Haz doble clic en `index.html` o
   - Arrastra `index.html` a tu navegador

2. **Personalizar contenido:**
   - Abre `index.html` en un editor de texto
   - Cambia los textos según sea necesario
   - Actualiza emails, redes sociales, etc.

## 🎨 Secciones

### 1. **Navegación (Header)**
- Logo de FAVIO INKER
- Menú: Home, Tracks, Gigs, About, Contact
- Responsive (menú hamburguesa en móvil)

### 2. **Hero Section**
- Presentación principal
- Subtítulo: "DJ & Producer | Indie Dance Specialist"
- Botones: "Explore Music" y "Get in Touch"

### 3. **Plataformas de Streaming**
- Spotify
- Apple Music
- SoundCloud
- Beatport

### 4. **Latest Releases (Tracks)**
- Muestra los últimos lanzamientos
- Enlaces a plataformas de streaming
- Diseño tipo tarjetas

### 5. **Upcoming Gigs**
- Sección para próximos eventos
- Información de fecha, lugar y venue

### 6. **About**
- Información personal del artista
- Descripción de Slow Cycle Records
- Detalles sobre su sonido

### 7. **Newsletter**
- Suscripción para mantenerse actualizado
- Formulario con nombre, apellido y email

### 8. **Contact**
- Formulario de contacto
- Email para bookings
- Ubicación

### 9. **Footer**
- Enlaces a redes sociales
- Copyright

## 🔧 Personalización

### Cambiar colores
En `styles.css`, busca `:root` y modifica:
```css
:root {
    --primary-color: #000000;
    --secondary-color: #ffffff;
    --accent-color: #ff6b6b;  /* Rojo actualmente */
}
```

### Agregar email de contacto
En `index.html`, busca:
```html
<a href="mailto:booking@favioinker.com">booking@favioinker.com</a>
```
Y reemplaza con el email real.

### Actualizar redes sociales
En `index.html`, sección de footer, actualiza los enlaces:
```html
<a href="https://www.instagram.com/favioinker/" target="_blank">
```

### Agregar nuevos tracks
En la sección "Latest Releases", copia un `.track-card` y personaliza:
```html
<div class="track-card">
    <div class="track-cover">
        <i class="fas fa-compact-disc"></i>
    </div>
    <h4>Nombre del Track</h4>
    <p class="track-label">Label</p>
    <a href="LINK" target="_blank" class="link">Listen</a>
</div>
```

### Agregar gigs/eventos
En la sección "Upcoming Gigs", copia un `.gig-card` y personaliza:
```html
<div class="gig-card">
    <div class="gig-date">
        <span class="month">JUN</span>
        <span class="day">15</span>
    </div>
    <div class="gig-info">
        <h4>Venue Name</h4>
        <p class="venue">City, Country</p>
    </div>
</div>
```

## 📱 Características

- ✅ Diseño responsivo (mobile, tablet, desktop)
- ✅ Navegación suave (smooth scroll)
- ✅ Menú hamburguesa en móvil
- ✅ Efectos hover interactivos
- ✅ Integración con redes sociales
- ✅ Formularios de contacto y newsletter
- ✅ Animaciones sutiles al scroll
- ✅ Diseño minimalista y profesional

## 🌐 Desplegar en línea

### Opción 1: Netlify (Gratis y fácil)
1. Sube los archivos a un repositorio GitHub
2. Ve a [netlify.com](https://netlify.com)
3. Conecta tu repo de GitHub
4. ¡Hecho! Tu sitio estará en línea

### Opción 2: Vercel (Gratis)
1. Sube los archivos a GitHub
2. Ve a [vercel.com](https://vercel.com)
3. Importa tu proyecto
4. Obtén un dominio automático

### Opción 3: Hosting tradicional
Sube los archivos (index.html, styles.css, script.js) a tu servidor web.

## 📧 Funcionalidad de formularios

Actualmente, los formularios muestran una alerta. Para que funcionen realmente:

**Opción 1: Usar un servicio como Formspree**
1. Ve a [formspree.io](https://formspree.io)
2. Crea un formulario
3. Obtén el email de envío
4. Modifica la acción del formulario en `index.html`

**Opción 2: Usar un backend propio**
Configura un servidor Node.js/PHP que reciba los formularios y envíe emails.

## 🎵 Enlaces actualizados

Asegúrate de que estos enlaces estén correctos:
- Instagram: https://www.instagram.com/favioinker/
- SoundCloud: https://soundcloud.com/favio-inker
- Beatport: https://www.beatport.com/artist/favio-inker/806676
- Apple Music: https://music.apple.com/us/artist/favio-inker/1478686946
- Facebook: https://www.facebook.com/inker.favio

## 💡 Tips

- Usa [unsplash.com](https://unsplash.com) para fotos de alta calidad
- Personaliza las imágenes de los tracks con covers reales
- Actualiza regularmente los eventos en la sección de Gigs
- Responde los emails de contacto para mantener una buena relación con fans

## 📝 Licencia

Esta página web fue creada para Favio Inker. Puedes usarla y modificarla libremente.

---

**¿Preguntas o necesitas ayuda?** Contáctame o abre un issue en el repositorio.
