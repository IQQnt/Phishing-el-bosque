# Seguridad Digital El Bosque

Página web educativa para la prevención del phishing, desarrollada como proyecto comunitario para la Urbanización El Bosque, Cumaná, Estado Sucre.

**Autores:** Sharon Asaeda, Zobeida Nahhas, Fabián Aparicio, Sair Espín  
**Institución:** UPTOS "Clodosbaldo Russián" - PNF en Informática  
**Año:** 2025

---

## 📁 Estructura del sitio

| Archivo             | Descripción 
|---------------------|-------------
| `index.html`        | Página de inicio 
| `phishing.html`     | Sección "¿Qué es el phishing?" |
| `ejemplos.html`     | Sección "Ejemplos reales" |
| `prevenir.html`     | Sección "Cómo prevenir" |
| `recursos.html`     | Sección "Recursos útiles" |
| `assets/js/main.js` | Funcionalidades compartidas (menú hamburguesa, año dinámico, simulación de descargas) |
| `assets/images/`    | Imágenes del sitio |
| `downloads/`        | Infografías descargables (PNG) |

---

## 🔧 Cómo actualizar el contenido

### 1. Cambiar textos o ejemplos

Abre el archivo `.html` correspondiente y busca el texto que quieres modificar. Los textos están escritos en español, dentro de etiquetas como `<p>`, `<h1>`, `<h2>`, etc.

**Ejemplo:** Para cambiar un ejemplo de phishing en la página `ejemplos.html`, busca la sección `<article>` que contiene el caso que deseas modificar.

### 2. Agregar una nueva infografía descargable

1. Coloca el nuevo archivo (PNG, JPG o PDF) en la carpeta `downloads/`
2. Abre el archivo `recursos.html`
3. Copia una de las tarjetas existentes (dentro de `<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">`) y pégala al final
4. Cambia los siguientes elementos:
   - `src="downloads/tu-imagen.png"` (ruta de la imagen)
   - El texto del título
   - El texto descriptivo
   - El enlace `href="downloads/tu-imagen.png"` en el botón de descarga

### 3. Modificar el menú de navegación

El menú está en cada archivo `.html`. Busca la sección `<nav>`. Si agregas o quitas una página, debes actualizar:
- El menú de escritorio (dentro de `<div class="hidden lg:flex space-x-6">`)
- El menú móvil (dentro de `<div id="mobile-menu">`)

### 4. Publicar los cambios en GitHub Pages

1. Guarda los cambios en tu computadora
2. Sube los archivos modificados al repositorio de GitHub (puedes hacerlo desde la web de GitHub o desde GitHub Desktop)
3. GitHub Pages publica automáticamente los cambios en pocos minutos

> 💡 **Importante:** El sitio está alojado en GitHub Pages. No toques los archivos `.github` ni cambies la configuración del repositorio a menos que sepas lo que haces.

---

## 📞 Contacto

Para dudas o reportar problemas, comunicarse con la Junta de Vecinos de la Urbanización El Bosque.

---

**Última actualización:** 2025
