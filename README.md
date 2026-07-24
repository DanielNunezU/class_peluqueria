# Class Peluquería — Sitio Web

Sitio web de una sola página para **Class Peluquería**, salón de belleza ubicado en Duitama, Boyacá (Colombia).

## Contenido

- `index.html` — estructura del sitio (inicio, servicios, nosotros, galería, testimonios, contacto).
- `styles.css` — estilos, tema claro/oscuro automático, diseño responsive.
- `script.js` — menú móvil, animaciones al hacer scroll y contador de estadísticas.
- `images/` — carpeta para agregar fotos reales del salón (ver `images/README.md`).

## Información del negocio

- **Dirección:** Cra. 17 #13-22, Centro-Sur, Duitama, Boyacá
- **Teléfono / WhatsApp:** +57 310 225 7957
- **Horario:** Lunes a sábado 8:00 a.m. – 6:00 p.m. · Domingo 10:00 a.m. – 12:00 p.m.
- **Facebook:** https://www.facebook.com/classpeluqueriaoficial/
- **Instagram:** https://www.instagram.com/classpeluqueria01/

## Cómo verlo localmente

Abre `index.html` directamente en tu navegador, o sirve la carpeta con cualquier servidor estático:

```bash
npx serve .
```

## Publicarlo (GitHub Pages)

1. Ve a **Settings → Pages** en este repositorio.
2. En "Source", selecciona la rama `main` y la carpeta `/ (root)`.
3. Guarda; tu sitio quedará disponible en `https://<usuario>.github.io/<repo>/`.

## Personalización

- Reemplaza las imágenes decorativas de la galería y del "about" agregando tus propias fotos en `images/` (ver instrucciones en `images/README.md`).
- Los colores del sitio se controlan con variables CSS en la parte superior de `styles.css` (`:root`).
