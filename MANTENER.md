# El portfolio ya está publicado

https://luxusfotografia-coder.github.io/portfolio/

Repositorio: https://github.com/luxusfotografia-coder/portfolio

---

## Cómo se actualiza

Cuando cargues fotos nuevas en `assets/img/`, yo actualizo el sitio y lo subo.
El cambio aparece online en 1 o 2 minutos.

Si lo querés hacer vos desde la terminal, parada en esta carpeta:

    git add -A
    git commit -m "que cambie"
    git push

La sesión ya quedó autenticada como luxusfotografia-coder, así que el push no
vuelve a pedir contraseña.

---

## Qué se publica y qué no

Se publica: `index.html`, `README.md` y `assets/` (fuentes + `img/web`).

NO se publica, por `.gitignore`:
- `assets/img/tublood/`, `assets/img/luxus/`, `assets/img/00-perfil/` — los
  originales pesados, que quedan solo en tu disco
- `LEEME.md` y este archivo — notas internas

El sitio usa únicamente las imágenes optimizadas de `assets/img/web/`.

---

## Bloques esperando fotos

| Sección | Carpeta |
|---|---|
| Catálogo web | `assets/img/tublood/02-catalogo-digital/` |
| Video institucional | `assets/img/tublood/07-video-institucional/` |
| Generador de firmas | `assets/img/tublood/08-herramientas-internas/` |
| Invitación web | `assets/img/luxus/invitaciones-web/` |
| Eventos empresariales | `assets/img/luxus/empresariales/` |
| Eventos sociales | `assets/img/luxus/sociales/` |
| Fotolibros y tarjetas | `assets/img/luxus/fotolibros/` y `tarjetas/` |

Ver `LEEME.md` para el detalle de qué conviene subir en cada una.
