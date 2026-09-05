# Retro 80s Car Launcher — política de privacidad

Este repositorio existe para una sola cosa: dar una **URL pública** a la
política de privacidad de la aplicación, que es un requisito de Google Play.

Se publica con GitHub Pages desde la rama `main`, carpeta raíz.

| Página | Fichero |
|---|---|
| Portada | `index.html` |
| Política de privacidad (español) | `privacidad.html` |
| Privacy policy (English) | `privacy.html` |

## Si cambia la política

El original vive con el código de la aplicación, en `CarLauncher/docs/`. Ahí es
donde hay que editarla; aquí solo se copia:

```bash
cp ../CarLauncher/docs/privacidad.html ../CarLauncher/docs/privacy.html .
git commit -am "Actualiza la politica de privacidad"
git push
```

Las dos versiones tienen que decir lo mismo que la aplicación: el correo de
contacto de aquí es el mismo que `REPORT_EMAIL` en `LauncherViewModel.kt`.
