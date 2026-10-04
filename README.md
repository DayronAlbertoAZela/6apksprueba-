# Pizzaroma 🍕

App de pizzería con diseño liquid glass. GitHub compila automáticamente:

- **Pizzaroma-3.0.apk** para Android
- **Pizzaroma-3.0-Windows.zip** con `Pizzaroma.exe` para Windows
- (Opcional) la **versión web** en GitHub Pages

## Cómo obtener el APK y el EXE

1. Crea una cuenta en [github.com](https://github.com).
2. Toca **+ → New repository**. Nombre: `pizzaroma`. Elige **Public** y toca **Create repository**.
3. Toca el enlace **uploading an existing file**.
4. Arrastra **todo el contenido** de esta carpeta (no el zip): `.github`, `www`, `electron`, `assets` y los archivos sueltos. Luego toca **Commit changes**.
5. Entra a la pestaña **Actions**. Verás "Construir Pizzaroma" trabajando (tarda unos 5–10 minutos).
6. Cuando tenga ✅, ve a la página principal del repositorio → **Releases** (columna derecha). Ahí están el `.apk` y el `.zip` para descargar.

Cada vez que cambies algo y lo subas, se genera una **nueva versión** automáticamente (v3.0.1, v3.0.2…).

## Instalar en Android

Abre la página de Releases desde el celular, descarga `Pizzaroma-3.0.apk` y ábrelo. Si Android lo pide, permite "instalar apps de fuentes desconocidas".

## Versión web (opcional)

En el repositorio: **Settings → Pages → Source: GitHub Actions**. En la siguiente compilación tendrás la app en
`https://TU-USUARIO.github.io/pizzaroma/`.

## Si la carpeta `.github` no se subió

Algunos sistemas ocultan las carpetas que empiezan con punto. Si en la pestaña Actions no aparece nada:
**Add file → Create new file**, escribe como nombre `.github/workflows/build.yml`, pega el contenido de ese archivo y toca **Commit changes**.

## Probar en tu PC (opcional)

Con [Node.js](https://nodejs.org) instalado: `npm install` y luego `npm start`.
