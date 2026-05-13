---
page: recursos
---
Actualizar la sección de "Video Educativo" en la página de Recursos para que sea más impactante visualmente. En lugar de una simple tarjeta, convertirla en una sección destacada con una miniatura grande que simule un reproductor de video.

**DISEÑO REQUERIDO:**
- Usar la paleta de colores del Design System (Navy 800, Trust Blue).
- Crear un contenedor con bordes redondeados generosos y sombra suave.
- Incluir un icono de "Play" grande en el centro de la miniatura.
- El texto debe explicar que es un tutorial paso a paso para configurar la verificación en dos pasos en WhatsApp.

**DESIGN SYSTEM (REQUIRED):**
[Design System: Senior Safety (Phishing Awareness)]

## 1. Visual Theme & Atmosphere
Un entorno "Gallery-Airy" de baja densidad (Density 2) y alta predictibilidad. El diseño prioriza la calma y la claridad absoluta a través de una estructura 100% lineal. Se eliminan distracciones laterales para reducir la carga cognitiva en usuarios con baja alfabetización digital.

## 2. Color Palette & Roles
- **Canvas Bone** (#F9FAFB) — Fondo principal (reduce el deslumbramiento frente al blanco puro).
- **Pure Surface** (#FFFFFF) — Fondo de tarjetas y contenedores de información.
- **Deep Security** (#0d1f23) — Texto principal y encabezados (Máximo contraste).
- **Trust Blue** (#2d4a53) — Color de acción para botones y elementos interactivos.
- **Pearl Border** (#afb3b7) — Bordes de tarjetas y divisores estructurales.
- **Muted Guidance** (#5a636a) — Texto secundario y leyendas de apoyo.

## 3. Typography Rules
- **Display/Headlines:** Satoshi — Peso Bold (700), Track-tight (-0.02em). Tamaño mínimo en Hero: 48px.
- **Body:** Satoshi — Peso Regular (400), Interlineado relajado (1.8), Máximo 60 caracteres por línea.
- **Banned:** Inter, fuentes con serif finas, texto gris sobre fondo blanco (bajo contraste).

## 4. Component Stylings
* **Buttons:** Formato grande (mínimo 56px de altura). Color sólido #2d4a53 con texto blanco. Sin sombras complejas ni efectos de neón. Feedback táctil claro al hacer clic.
* **Cards:** Bordes redondeados generosos (1.5rem). Borde sólido de 1px en #afb3b7. Sin sombras (evita sensación de borrosidad).
* **Inputs:** Etiquetas siempre visibles arriba del campo (no usar placeholders como etiquetas). Borde de foco en #2d4a53 con grosor de 3px.

## 5. Layout Principles
- **Estructura Lineal:** Flujo vertical estricto. Prohibido el uso de múltiples columnas que requieran escaneo horizontal complejo.
- **Espaciado:** Padding interno de secciones mínimo de 4rem para separar visualmente los conceptos educativos.
- **Max-width:** Contenedores limitados a 900px para evitar líneas de texto demasiado largas que dificulten el retorno de la vista al inicio de línea.

## 6. Motion & Interaction
- **Transiciones:** Suaves y lentas (Spring physics: stiffness 80, damping 25).
- **Micro-interacciones:** Los elementos clicables deben tener un cambio de estado visual obvio (cambio de color de fondo o subrayado grueso).

## 7. Anti-Patterns (Banned)
- No usar iconos sin texto descriptivo.
- No usar terminología técnica ("Phishing", "Malware") sin una tarjeta de definición previa.
- No usar animaciones rápidas o parpadeantes.
- No usar menús hamburguesa ocultos si hay espacio para navegación textual clara.
- No usar colores de alerta agresivos (Rojo puro) sin contexto de peligro extremo.
