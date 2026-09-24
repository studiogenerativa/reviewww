# reviewww — sitio público

Página de Reviewww y su política de privacidad, servidas con GitHub Pages.

- Inicio: https://studiogenerativa.github.io/reviewww/
- Política de privacidad: https://studiogenerativa.github.io/reviewww/privacy/

La URL de la política es obligatoria para publicar en la Chrome Web Store y va en la pestaña
**Privacy practices** del dashboard. Tiene que seguir siendo pública y estable: Google la revisa
al enviar y puede volver a revisarla después.

## Editar

HTML plano, sin build. `style.css` usa los mismos tokens de color y tipografía que la extensión
(sección 8 de `REVIEWWW_SPEC.md`), para que el sitio y el producto se vean iguales.

Si cambias la política, actualiza también la fecha de `Last updated` y la copia en
`docs/PRIVACY.md` del repo de la extensión, para que no se separen.

El archivo `.nojekyll` evita que GitHub Pages procese el sitio con Jekyll.
