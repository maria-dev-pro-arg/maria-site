# maria — sitio personal

Sitio estático, responsive y sin build step.

## Archivos
- `index.html`
- `styles.css`

## Cómo verlo en tu compu
Abrí `index.html` con doble clic.

## Cómo subirlo a GitHub
1. Creá un repositorio nuevo.
2. Subí `index.html` y `styles.css` a la raíz.
3. Si querés publicarlo con GitHub Pages:
   - Settings
   - Pages
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
   - Save

## Qué tenés que cambiar después
### Email
En `index.html`, buscá:
`mailto:tuemail@ejemplo.com`

y reemplazalo por tu email real.

### Redes
Reemplazá los `href="#"` del footer por tus enlaces reales.

### Links de proyectos
Cada tarjeta tiene un `href="#"`. Podés reemplazarlo por:
- la web del proyecto
- una subpágina
- un repo
- o dejarlo sin link por ahora

### Foto
El bloque grande de la portada está hecho como placeholder.
Cuando tengas la foto, podemos reemplazar ese bloque por una imagen real sin cambiar el diseño.

## Colores
- Cereza: `#7a1731`
- Cereza oscuro: `#5b1025`
- Trigo / amarillo: `#fcba03`
- Fondo crema: `#fff9ef`

## Microinteracciones
Esta versión agrega microinteracciones solo con CSS, sin JavaScript:
- cambio de color y subrayado en navegación
- botones que se elevan al pasar el mouse y se hunden al tocar/clickear
- tarjetas con movimiento leve, sombra y cambio de fondo
- flechas de proyectos con feedback táctil
- movimiento sutil de las estrellas
- respuesta visual del nombre `maria`
- soporte para `prefers-reduced-motion`
