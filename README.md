# Proyecto NFC para GitHub Pages

Este proyecto muestra un PDF mediante una página web estática y está pensado para usarse con etiquetas NFC.

## Estructura

- `index.html` — página principal.
- `style.css` — diseño de la página.
- `pdf/documento.pdf` — coloca aquí el PDF que quieres mostrar.

## Cómo actualizar el PDF sin cambiar el enlace NFC

1. Graba en el NFC la dirección de tu página de GitHub Pages.
2. Mantén el mismo nombre: `documento.pdf`.
3. Cuando necesites actualizarlo, reemplaza `pdf/documento.pdf` por el nuevo PDF.
4. No cambies la dirección de la página ni el nombre del archivo.
5. El NFC seguirá apuntando al mismo enlace.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `style.css` y la carpeta `pdf`.
3. En GitHub entra a `Settings` → `Pages`.
4. En "Build and deployment" selecciona `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda y espera a que GitHub Pages publique el sitio.

La dirección normalmente tendrá este formato:

https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/

## Importante

GitHub Pages es público. Cualquier persona que tenga el enlace puede intentar acceder al documento. No uses este sistema para información que deba permanecer privada o confidencial.

## Para varios documentos

Puedes crear:

`pdf/001.pdf`
`pdf/002.pdf`
`pdf/003.pdf`

y crear páginas o enlaces separados para cada uno. Para un sistema con muchos NFC, conviene usar una estructura con identificadores permanentes.
