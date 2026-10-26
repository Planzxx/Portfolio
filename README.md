# Portfolio · Jorge Zambrana

Portfolio personal estático (un solo `index.html`, sin JavaScript, sin dependencias ni cookies).

## Publicar en GitHub Pages

1. En GitHub crea un repositorio **público** llamado `Planzxx.github.io` (así la web quedará en `https://planzxx.github.io`) o cualquier otro nombre (quedará en `https://planzxx.github.io/<nombre>`).
2. Sube estos archivos a la rama `main`: `index.html`, `README.md`, `.gitignore`, `.nojekyll`.
3. Ve a **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. Activa **Enforce HTTPS** (Settings → Pages) cuando aparezca disponible.

## Checklist de seguridad y privacidad

- [x] Sin teléfono ni dirección postal; solo ciudad, email, LinkedIn y GitHub.
- [x] Sin JavaScript, formularios, analítica ni cookies.
- [x] Política CSP (`<meta http-equiv="Content-Security-Policy">`) que bloquea scripts y cualquier recurso no previsto.
- [x] Enlaces externos con `rel="noopener noreferrer"`.
- [x] Sin claves, tokens ni archivos `.env` (y `.gitignore` por si acaso).
- [ ] Activa la **verificación en dos pasos (2FA)** en tu cuenta de GitHub.
- [ ] Comparte en Notion las 3 páginas de proyecto con **"Compartir en la web"**, o los visitantes verán una pantalla de acceso.
- [ ] Revisa en una ventana de incógnito que todos los enlaces funcionan.

## Nota sobre privacidad (opcional)

Las tipografías (Anton, Caveat, Inter) se cargan desde Google Fonts, lo que envía la IP del visitante a Google. Para evitarlo, descarga las fuentes (p. ej. con google-webfonts-helper), súbelas a una carpeta `fonts/`, sustituye el `<link>` por reglas `@font-face` y cambia la CSP a `font-src 'self'; style-src 'unsafe-inline'`.

## Email

El correo aparece en texto claro (`mailto:`), por lo que puede recibir spam de bots. Es una decisión consciente para facilitar el contacto.
