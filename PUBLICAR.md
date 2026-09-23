# Cómo publicar el portfolio en GitHub Pages

El sitio ya está listo y el repositorio local ya tiene el primer commit hecho.
Falta solo crear la cuenta y subirlo. Son 10 minutos.

No puedo hacer esta parte por vos porque necesita tu mail, tu contraseña y la
verificación por correo.

---

## Paso 1 — Crear la cuenta (3 min)

1. Entrá a **github.com** y hacé clic en *Sign up*.
2. Usá **belencaa.90@gmail.com**.
3. Elegí un nombre de usuario. **Este nombre va a formar parte de la URL**, así
   que conviene algo limpio y profesional:
   - `belencaamano` → la URL queda `belencaamano.github.io/portfolio`
   - `bcaamano` → `bcaamano.github.io/portfolio`

   Evitá números o guiones raros: esta dirección va en el CV.
4. Confirmá el mail.

---

## Paso 2 — Crear el repositorio (1 min)

1. Arriba a la derecha, botón **+** → *New repository*.
2. **Repository name:** `portfolio`
3. Marcá **Public** (obligatorio: Pages gratis solo funciona en repos públicos).
4. **No** marques "Add a README" ni ninguna otra casilla.
5. *Create repository*.

---

## Paso 3 — Subir los archivos (3 min)

La forma más simple, sin instalar nada:

1. En la página del repo recién creado, hacé clic en
   **uploading an existing file**.
2. Abrí la carpeta `portfolio-belen` en el explorador de Windows.
3. Seleccioná **`index.html`**, **`README.md`** y la carpeta **`assets`**
   completa, y arrastralos a la ventana del navegador.
4. Esperá a que termine de subir (son 1,6 MB).
5. Abajo, botón verde **Commit changes**.

> No subas las carpetas `assets/img/tublood`, `assets/img/luxus` ni
> `assets/img/00-perfil`: son los originales pesados y no hacen falta online.
> El sitio usa solo `assets/img/web`.

---

## Paso 4 — Activar GitHub Pages (2 min)

1. En el repo, andá a **Settings** (arriba) → **Pages** (menú izquierdo).
2. En *Source*, elegí **Deploy from a branch**.
3. En *Branch*, elegí **main** y carpeta **/ (root)**. Guardá con *Save*.
4. Esperá 1 o 2 minutos y recargá la página: arriba va a aparecer tu dirección.

**Tu portfolio va a quedar en:**
`https://TUUSUARIO.github.io/portfolio/`

---

## Paso 5 — Avisame

Pasame la URL y hago dos cosas:

1. La agrego a los dos CV, en la línea de contacto.
2. Corrijo el `README.md` del repo, que ahora dice `USUARIO` de ejemplo.

---

## Para actualizar el sitio más adelante

Cuando cargues fotos nuevas y yo actualice el `index.html`, repetís el Paso 3:
subís los archivos cambiados y GitHub republica solo. Tarda un minuto.

Si preferís algo más cómodo que arrastrar archivos, instalá **GitHub Desktop**
(desktop.github.com): te deja sincronizar la carpeta con un botón.
