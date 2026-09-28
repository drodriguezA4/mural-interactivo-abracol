# Mural Interactivo ABRACOL — GitHub Pages

Esta carpeta ya está preparada para publicarse como sitio estático.

## 1. Pegar las fotos
Copia las fotos originales dentro de:

- `assets/fotos/UNE CENTRO/`
- `assets/fotos/UNE NORTE/`
- `assets/fotos/UNE OCCIDENTE/`
- `assets/fotos/UNE INDUSTRIA/`
- `assets/fotos/UNE MEDELLIN/`
- `assets/fotos/CUENTAS NACIONALES/`
- `assets/fotos/EXPORTACIONES/`

Conserva el nombre del archivo con el nombre del asesor. El sitio intenta automáticamente
JPG, JPEG, PNG y WEBP, y también variantes en mayúsculas/minúsculas.

## 2. CSV
Los CSV actuales ya están en `data/` y los valores actuales también están embebidos en `index.html`.

En GitHub Pages, si reemplazas un archivo CSV dentro de `data/` manteniendo su nombre:
- `centro.csv`
- `norte.csv`
- `occidente.csv`
- `industria.csv`
- `medellin.csv`
- `exportaciones.csv`

la página intentará leer la versión nueva automáticamente al cargar.

## 3. Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Descomprime este ZIP.
3. Sube **el contenido de esta carpeta**, de modo que `index.html` quede en la raíz del repositorio.
4. En GitHub: `Settings` → `Pages`.
5. En `Build and deployment`, selecciona `Deploy from a branch`.
6. Elige la rama `main` y la carpeta `/ (root)`.
7. Guarda.

GitHub mostrará la URL pública cuando termine el despliegue.

## Importante
Los nombres de carpetas son sensibles a mayúsculas/minúsculas cuando el sitio está en Internet.
No cambies los nombres de las carpetas indicadas arriba.

No necesitas subir los archivos `PEGAR_FOTOS_AQUI.txt`; puedes borrarlos después de pegar las fotos.
